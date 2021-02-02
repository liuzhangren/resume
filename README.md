##   基本信息 

姓名： 刘章仁 	

工作经验：4年

Tel： 18986700600

Email：liuzhangren110@gmail.com

GitHub:  https://github.com/liuzhangren

往届毕业生/本科/武汉东湖学院

## 技能描述

> 熟悉HTML/CSS，了解经典的网页布局开发，能使用其解决移动端适配问题；

> 了解DOM，熟悉原生JavaScript，掌握JS概念。熟悉ES6开发；

> 了解前后端联合开发的技术原理：Ajax, Json，axios；

> 使用过CSS预处理器SASS；pug、stylus 等预编html、css;

> 熟悉gulp、webpack、rollup等打包构建工具；

> 了解网络基础知识，了解前端性能优化策略；

> 熟练使用react+redux+antd, 封装过底层组件;

> 熟练使用dva or umi 开发react项目，有过大型互联网React项目开发经验;

> 熟悉React-Native，能迅速开发移动端应用;

> 熟悉Taro 能快速开发小程序；

> 熟练使用nodejs，熟悉koa2、express、 micro、熟悉prisma+mongodb开发后端接口;

> 熟悉微信小程序微服务编写中间层sdk;

> 熟悉websocket即时通讯

> 熟悉antv、echarts、openlayers等图表、地图插件

> 熟练使用git、遵循git flow工作流程;

> 熟悉 lerna包管理 工具、npm 推送封装库;

> 熟悉pixi webGL框架 编写类游戏canvas应用;

> 熟悉TypeScript;

> 熟悉使用jsonwebtoken， 利用cookie进行存储、鉴权;

> 熟悉docker容器，以及汇编shell脚本，自配mac pro;

## 其他

> 闲暇阅读掘金，有良好的关注新技术的习惯；

> 有自己的学习方式，会使用官方文档，MDN，Google来学习前端知识；

> 遇到新技术会边学边写demo 推送github；

## 工作经历

> 2020.01 ~ 至今 云峰核信（武汉）股份有限公司

> 2017.09 ~ 2019.12 举手帮租（武汉）有限公司

## 项目经验
  #### 405生产管理支持平台(前端)
  <span style="color: black">项目周期: 2020 01 ～ 至今</span>

​  中国核电旗下陕西铀矿405所的生产管理支持平台 

    - 负责前端项目的构建
    
    - 负责前端应用技术的调研
    
    - 负责团队的代码管理
    
    - 使用技术栈: React、redux、dva、es6、rollup、storybook、antd、antv、websocket、echart、openlayers；
    
    - 所遇问题: 
      - 组件库外提封装打包支持css-modules、global，lernajs支持批量操作以及脚本集成
      解决方案： 翻看文档
    
      - 动态换肤功能
      解决方案: 使用css的var()函数读取缓存中的变量 达到切换主题的效果；
      
      - 自定义流程功能，手写流程图兼容activity流程引擎框架，数据结构对不上需要转换
      解决方案: 递归算法；
    
      - 批量展示的table、tree、list的数据量需要达到10000+条，antd的表格组件、组件状态切换卡顿；
      解决方案：使用react-virtualize 做新的支持虚拟滚动的table组件；
    
    - 参与业务:
    
      - 设备变动模块


  #### MDR(PC) (前端)

  <span style="color: black">项目周期: 2019 01 ～ 2019 11</span>
  展示地址: https://www.marinedigitalrepublic.com

    基于船舶的虚拟区块链官网
    
    - 负责所有页面的开发
    
    - 完成所有功能
    
    - 使用技术栈:  react、redux、axios、es6、webpack、gulp、react-intl、echarts、express、nodejs

  #### 灵犀平台(PC) (前端)
  <span style="color: black">项目周期: 2018 07 ～ 2019 01</span>
  展示地址: https://lingxi.di-an.com

    基于流程控制的团队协作OA系统
    
    - 参与灵犀平台的流程控制管理模块的开发
    
    - dva + react + antd 构建视图，封装了step流程步骤控制组件，包含增删改查 表单功能，表单收集在redux层中完成。
    
    - 完成流程控制功能
    
    - 遇到的问题: 逻辑复杂 表单的收集、清空、编辑、删除一环节点需要在redux层中做，导致了工作量太大，花了大量的时间考虑组件的封装，逻辑的分层。
    
    - 使用技术栈:  ES6、React、node.js、Redux、dva、antd；
  #### 参与租房管理系统的开发(前端)
   <span style="color: black">项目周期: 2017 09 ～ 2018 07</span>
   展示地址: http://fangguan.jsbz365.com:3088/

    搭建 wrapper组件层、view视图层、page数据层、umi发布环境
    
    - 参与了系统平台的 人员管理、渠道管理、工单管理模块的页面构建
    
    - react+redux+antd 构建视图 按需求在周期中撰逻辑
    
    - 按需求对接业务逻辑，并且抽象周期中的逻辑代码 已迭代15个版本
    
    - 并且完成了中间件 user-sdk、 business-sdk、 lock-sdk 将后端返回统一格式塞进store并
    
    - connet ReactComponents 进行数据交互
    
    - 使用技术栈：ES6; coffeeScript；React；node.js；Redux ; antd; gulp; webpack; umi



  #### 参与租房管理系统的开发 (后端 user模块)
  <span style="color: black">项目周期: 2017 09 ～ 2018 07</span>
  开发user相关的功能模块

    - 完成了系统管理员角色、渠道用户角色、渠道用户名下员工等角色，以及登陆分发token
    
    - 鉴权功能，以及基础的crud
    
    - 使用技术栈: ES6; coffeeScript; nodejs ; microjs; jwt ; base64



  #### 参与租房管理系统的开发 (后端 business模块)
  <span style="color: black">项目周期: 2017 09 ～ 2018 07</span>
  开发需求相关对象(business)的功能模块

    - 完成了N+1个对象的crud和getby功能, 并抽象核心crud代码成库，可复用，
    
    - 组织私有 npm上可查 https://www.npmjs.com/package/cfx.service.baseapi
    
    - 使用技术栈: ES6; coffeeScript; microjs ; base64 ; nodejs


## 自我评价
  技术宅、苹果重度患者、自信乐观、适应性强、抗压. 努力朝架构方向发展！
