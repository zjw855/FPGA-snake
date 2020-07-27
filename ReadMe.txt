//////////////////////////////////////////////////////////////
编写环境：vivado2018.3
开发板：xc7s15ftgb196-1
//////////////////////////////////////////////////////////////
下属文件：
pld3/srcs/sources_1/ip       //两个IP核

clk_wiz_0                             //时钟
rgb2dvi_0                            //RGB转DVI

pld3/srcs/sources_1/new： //v文件

Apple_generate_module.v   //苹果生成模块
HDMI.v                                //HDMI模块
DIS.v                                    //HDMI显示
Driner_HDMI.v                     //HDMI驱动
vga_control.v                       //vga控制（与HDMI不一起使用）
Game_control_module.v      //游戏状态模块
Key_check_module.v            //按键消抖（未来是陀螺仪的信号滤波）
Snake_ctrl_module.v            //蛇身控制模块
top.v                                    //顶层模块

pld3/srcs/constrs_1/new：  //xdc文件

pld3.xdc                 

