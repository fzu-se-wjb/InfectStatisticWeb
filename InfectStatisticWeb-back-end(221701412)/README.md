# InfectStatistic-Pair-Work
InfectStatistic-Pair-Work of 221701412 and 221701420

+ 本次后端开发使用maven + springboot + ~~web magic~~(更改思路直接爬取api的数据) 进行开发

+ 使用SpringBoot的推荐项目目录结构
    + 代码层的结构
        + 1.工程启动类(ApplicationServer.java)置于com.springboot包下
        + 2.实体类(domain)置于com.springboot.domain
        + 3.数据访问层(Dao)置于com.springboot.repository
        + 4.数据服务层(Service)置于com,springboot.service,数据服务的实现接口(serviceImpl)至于com.springboot.service.impl
        + 5.前端控制器(Controller)置于com.springboot.controller
        + 6.工具类(utils)置于com.springboot.utils
        + 7.常量接口类(constant)置于com.springboot.constant
        + 8.配置信息类(config)置于com.springboot.config
        + 9.数据传输类(vo)置于com.springboot.vo

+ 资源文件的结构
    + 根目录:src/main/resources
        + 配置文件(.properties/.json等)置于config文件夹下