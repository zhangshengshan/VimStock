# VimStock
基于vim命令行的炒股插件

![Alt text](https://github.com/guofh/VimStock/blob/master/VimStock.png)

## 注意事项

1. 需要添加vim对python2的支持
2. 需要安装的python包:requests,pandas

## MiniStock的使用命令

1. #### **:Vallstock [关键字] [正倒序] [页码]**  
    
    说明：Vimstock命令为显示所有股票最新信息，并按照[关键字]进行排序。[关键字]有涨跌幅(zdf)，涨速(zs)等。关键字变量为表头的中文首字母缩写，如市盈率为  syl。排序1为正序，0为倒序。例：`Vallstock zdf 1 1` 为显示所有股票按涨跌幅由高向低排序，显示第一页内容。`Vallstock zs 0 2` 为显示所有股票按涨速由低向高排序，显示第二页内容。
    
2. #### *:Vggzjl [关键字] [正倒序] [页码]**  
    
    说明：Vggzjl命令为显示所有股票资金流信息，并按照[关键字]进行排序。[关键字]中比Vallstock增加了包括大单净量，流入，流出，净额等资金流信息。关键字变量为表头的中文首字母缩写。排序1为正序，0为倒序。例：`Vggzjl lrzj 1 1` 为显示所有股票按流入资金排序，显示第一页内容。
    
3. #### **:Vgnzjl [关键字] [正倒序] [页码]**  
    
    说明：Vgnzjl命令为显示概念板块信息包括资金流信息，并按照[关键字]进行排序。[关键字]关键字变量为表头的中文首字母缩写。排序1为正序，0为倒序。例：`Vgnzjl je 1 1` 为显示所有概念板块按净流入资金排序，显示第一页内容。
    
4. #### **:Vhyzjl [关键字] [正倒序] [页码]**  
    
    说明：Vhyzjl命令为显示行业板块信息包括资金流信息，并按照[关键字]进行排序。[关键字]关键字变量为表头的中文首字母缩写。排序1为正序，0为倒序。例：`Vhyzjl zdf 1 1` 为显示所有行业板块按涨跌幅排序，显示第一页内容。
    
4. #### **:Vr**  
    
    说明：Vr命令为刷新当前行情。如果当前开了多个窗口，则所有窗口信息全部刷新为最新的行情。
    
5. #### **:Vrun**  
    
    说明：Vrun命令VimStock默认的一种窗口显示。默认为四个窗口，第一窗口显示涨速排名，第二窗口显示概念板块涨跌幅，第三窗口显示行业板块涨跌幅，第四窗口显示所有股票信息按涨幅排序。用户也可以根据平时自己的习惯设置自己的界面信息。
     
## 联系方式

微博：@一口大黑郭 
微信：g635852898 
邮箱：heiguo88@gmail.com 

