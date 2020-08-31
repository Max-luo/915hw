# 915hw
python code for 915hw

 MY SOURCE
 IRAS            RA            DEC      V_lsr  Distance   R_GC   Radius    T_dust 
 I16037-5223  16:07:38.10  -52:31:00.2   -80      9.84    4.9     2.15     31.4 


内容1：作出⼤大尺度的温度和柱密度分布图
下载herschel 的五个波段数据（70，160， 250，350，500um）并做逐像素的SED拟合，得出温度和柱密度分布图 下载区域大小为10个角分


内容2：求出7M数据中clump的质量，柱密度，以及尘埃温度。从7M 连续谱数据中⽤用Gauss函数 拟合出源 的⼤大⼩小，并测出源的流量量，⽤用于SED拟合 获取该源的ATLASGAL，Herschel 流量量数据
#SED fitter可得clump的质量、柱密度、尘埃温度


内容3：找出与源对应的可能的年年轻星后选体，以及下载中红外波段的图像 
Spitzer or WISE: 
a. 查看⾃自⼰己的坐标是否包括在Spitzer 的 GLIMPSE巡天⾥里里⾯面，若没有尝试去 WISE的全天巡天数据去搜索点源数据， 搜索半径2个角分，并下载图像，图像 搜索半径为5个角分 
b. 画出中红外的三色图
d. https://irsa.ipac.caltech.edu/frontpage/

内容4：尝试获取厘⽶米波段数据
a. ⻅见课件数据库⽹网址，并查看⾃自⼰己的源是 否有厘⽶米波连续谱资料料，若有下载，并画图

内容5：尝试获取厘⽶米波段数据
a. 找出12M数据⾥⾯的所有core,并用 gauss 函数拟合给出相应的观测参量量 
b. 尝试计算每个core的质量量和密度（假设 core的温度为clump的温度，距离请⻅见 Liu T. et al. 2020a,b

内容6：计算12M数据中core的参量
a. 找出12M数据⾥里里⾯面的所有core,并⽤用 gauss 函数拟合给出相应的观测参量量 
b. 尝试计算每个core的质量量和密度（假设 core的温度为clump的温度，距离请⻅见 Liu T. et al. 2020a,b）

内容7：计算12M数据中core的⼏几条分⼦子谱线的平均光谱 （HCO，H13CO+， CCH）
a. 抽出core 周围1.0arcsecond 的所有谱 并做平均

内容8：12M数据的Moment图
a. Moment 0/1/2
