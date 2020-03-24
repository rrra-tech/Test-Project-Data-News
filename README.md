  中文文本分类数据集  
  ===  
  
  研究主题：  
  探讨短视频与直播的共生关系  
  研究对象：  
  央视新闻、人民日报、新华视点   
  采集范围：  
  1月20日~2月9日，共计21天  
  数据来源：  
  微博后台  
  
  数据格式：  
  >1月20日 #100 #钟南山肯定新型冠状病毒肺炎人传人 #5456 #钟南山，新型冠状病毒  
  
  每行为一条数据，以"#"为分割的字段，从前往后分别是：发布时间，分类code及名称（见下文），新闻标题，收看人数，关键词  
  
  分类code与名称：  
    101 央视新闻 短视频 short video of CCTV  
    102 央视新闻 直播 live broadcast of CCTV  
    103 人民日报 短视频 short video of People's Daily  
    104 人民日报 直播 live broadcast of People's Daily  
    105 新华视点 短视频 short video of Xinhua News Agency  
    106 新华视点 直播 live broadcast of Xinhua News Agency  
  
  数据规模：  
  共1308条，分布于6个分类中  
  采集时间：  
  2020年02月  
  实验结果：  
  以0.8作分割，验证数据准确性  
  
    test result:0.8  
    code | mounts | views   
    101 | 370 | 333641   
    102 | 130 | 102140   
    103 | 318 | 323752   
    104 | 54 | 35507   
    
