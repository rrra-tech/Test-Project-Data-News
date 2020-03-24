  中文文本分类数据集  
  ===  
  
  研究主题/Topic：  
  探讨短视频与直播的共生关系/Relationship between short video and live broadcast    
  
  研究对象/Object：  
  央视新闻、人民日报、新华视点/Top3 Media in China     
  
  采集范围/Range：  
  1月20日~2月9日，共计21天/20th Jan to 9th Feb, totally 21days    
  
  数据来源/Source：  
  微博Weibo  
  
  数据格式/Data form：  
  >1月20日 #101 #钟南山肯定新型冠状病毒肺炎人传人 #5456 #钟南山，肺炎  
  
  每行为一条数据，以"#"为分割的字段，从前往后分别是：发布日期，分类code及名称（见下文），新闻标题，收看人数（单位：万人次），关键词  
  
  分类code及名称/name：  
  
    101 央视新闻 短视频 short video of CCTV  
    102 央视新闻 直播 live broadcast of CCTV  
    103 人民日报 短视频 short video of People's Daily  
    104 人民日报 直播 live broadcast of People's Daily  
    105 新华视点 短视频 short video of Xinhua News Agency  
    106 新华视点 直播 live broadcast of Xinhua News Agency  
  
  数据规模/Data scale：  
  共1308条，分布于6个分类中  
  
  采集时间/Time：  
  2020年02月28日  
  
  实验结果/result：  
  以0.8作为分割，验证数据准确性  
  
    Test Loss: 0.27, Test Acc:  93.81%  
    code | mounts | views (unit:millons)   
    101 | 370 | 333641   
    102 | 130 | 102140   
    103 | 318 | 323752   
    104 | 54 | 35507   
    ...
