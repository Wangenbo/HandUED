# 掌上大学UED团队

## 一、包含
- [CSS 开发规范](https://github.com/Wangenbo/HandUED/blob/master/%E6%8E%8C%E4%B8%8A%E5%A4%A7%E5%AD%A6CSS%E5%BC%80%E5%8F%91%E8%A7%84%E8%8C%83.md)
- [HTML 开发规范](https://github.com/Wangenbo/HandUED/blob/master/%E6%8E%8C%E4%B8%8A%E5%A4%A7%E5%AD%A6HTML%E5%BC%80%E5%8F%91%E8%A7%84%E8%8C%83.md)
- [JavaScript 开发规范](https://github.com/Wangenbo/HandUED/blob/master/%E6%8E%8C%E4%B8%8A%E5%A4%A7%E5%AD%A6Javascript%E5%BC%80%E5%8F%91%E8%A7%84%E8%8C%83.md)

## 二、前端开发流程
1. 查看需求文档，记录文档中有疑问或有建议的点。
2. 参加需求评审会议，产品经理详细介绍需求文档中内容，针对自己疑问点进行解答。
3. 项目经理进行任务分配
4. 评估每个模块负责人开发周期，完善开发管理进度表
5. 确定测试上线日期
6. 与设计师沟通设计图实现细节及完善交互流程
7. 界面开发
8. 交互开发
9. 接口数据对接
10. 功能联调
11. 一轮测试修复问题
12. 二轮测试修复问题
13. 产品经理验收
14. 上线同步脚本及代码
15. 线上产品验收


## 三、前端开发FAQ

1. 与设计师对接过程有哪些注意的地方？
    - 在开发开发之前前端开发工程师要和设计师进行需求沟通，用最好的交互和设计实现来完成本次开发需求
    - 注意设计图的单位
    - 沟通通用设计元素全局使用
    - 图片和图标的使用要遵从阿里巴巴 iconfont 协议

2. 前端性能优化
    - 语义化标签及代码结构优化
    - 图片压缩
    - 代码压缩
    - 预加载
    - 懒加载
    - CDN
3. overflow hidden 在IOS卡顿问题
    ```
    -webkit-overflow-scrolling: touch;
    ```
4.  与产品经理对接有哪些需要注意的地方？
    - 在开发开始之前要对自己负责模块的需求进行梳理, 对于逻辑不清晰或者有问题的部分及时与产品沟通并完善需求.   了解对应模块的原始需求以及项目整体需求有助于保证不对开发需求的理解造成偏差.
    - 注意新需求对已有项目造成的影响, 并及时与产品沟通
    - 调整及补充的需求需要产品及时更新到prd上
    - 项目开发过程中新增及调整的需求, 以及对开发周期造成的影响, 要及时与产品及项目负责人沟通,判断需求是否做延期处理.

5. 与后端开发工程师对接有哪些需要注意的地方？
    - 项目开发开始后,尽早地完成接口文档
    - 接口文档需要结合产品的设计图根据产品交互方式进行编写
    - 接口文档完成后, 及时与前端沟通, 对于接口设计不当或遗漏的及时进行调整