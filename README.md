直播项目api入口项目

命名规范 
    1.包名  com.sanshengit.chicha
    2.netease 包 为网易服务器接口调用代码包
    3.api.v1  为直播平台所有api接口包
    4.channel 直播频道包
        dto 为数据传输对象包
        entity  实体对象包
        repository 数据持久层代码包
        service  业务服务接口层包
        service.impl 为业务服务接口层具体实现包
        
本项目使用gradle进行构建，使用docker进行打包