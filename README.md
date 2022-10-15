# lostsongdb
人工整理的 mv 匹配清单开源，不定期更新

[点击这里查看清单](https://github.com/lostsongdb/lostsongdb/blob/main/lostsongdb.csv)

## 表格各字段说明

 列名             |   描述                                               
----------------|----------------------------------------------------
 name           |   音乐名称                                             
 url            |   MV链接，访问这个地址可以打开视频链接                              
 start\_ts      |   当一个视频中包含了多首歌，指定当前音乐在视频中的开始时间。当这个视频中只有单独一首歌，该字段为空 
 end\_ts        |   当一个视频中包含了多首歌，指定当前音乐在视频中的结束时间。当这个视频中只有单独一首歌，该字段为空 
 singer\_name   |   歌手名称，多个歌手用逗号分隔                                   
 album\_name    |   专辑名称                                             
 on\_website    |   MV来源网站，比如 bilibili、youtube                       
 on\_official   |   是官方发布的视频吗？是为1，否为0                                
 p              |   当up主上传了多p视频，指明对应p                                

