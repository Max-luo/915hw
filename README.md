# 915hw
python code for 915hw

 MY SOURCE
 IRAS            RA            DEC      V_lsr  Distance   R_GC   Radius    T_dust 
 I16037-5223  16:07:38.10  -52:31:00.2   -80      9.84    4.9     2.15     31.4 


内容1：作出⼤大尺度的温度和柱密度分布图
下载herschel 的五个波段数据（70，160， 250，350，500um）并做逐像素的SED拟 合，得出温度和柱密度分布图 下载区域⼤大⼩小为5个⻆角分

1.download herschel and others data.
  https://irsa.ipac.caltech.edu/irsaviewer/
  
2.download ATLASGAL 870 micron cutout image
  https://atlasgal.mpifr-bonn.mpg.de/cgi-bin/ATLASGAL_DATABASE.cgi
  
3.download Planck+ATLASGAL data
  https://atlasgal.mpifr-bonn.mpg.de/cgi-bin/ATLASGAL_DATASETS.cgi
  
4.SED fitter
  https://hi-gal-sed-fitter.readthedocs.io/en/latest/higal_sedfitter/index.html#example  #example
  https://github.com/XFengwei/HMSCs_cat/blob/master/scripts/sedFitting/008sedFitting.py  #by fengwei
  
5.
