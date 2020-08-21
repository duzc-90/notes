## antd（3.x）简述  
antd 是基于 Ant Design 设计体系的 React UI 组件库，主要用于研发企业级中后台产品
## 特性
  - 提炼自企业级中后台产品的交互语言和视觉风格
  - 开箱即用的高质量 React 组件
  - 使用 TypeScript 开发，提供完整的类型定义文件
  - 全链路开发和设计工具体系
  - 数十个国际化语言支持
  - 深入每个细节的主题定制能力
## 支持环境
  - 现代浏览器和 IE9 及以上（需要 polyfills）。
  - 支持服务端渲染。
  - Electron
## 版本3.x -> 版本4.x
  - 代码重构
    - Form 重写
    - DatePicker 重写
    - Tree、Select、TreeSelect、AutoComplete 重新写
    - Button 的 danger 现在作为一个属性而不是按钮类型
    - Input、Select 的 value 为 undefined 时改为非受控状态
    - Table 重写
    - Pagination 自 4.1.0 起大于 50 条数据默认会展示 pageSize 切换器，这条规则同样会运用于 Table 上
    - Tabs 重写（4.3.0）  
    ......更详尽的信息可在[官方网站](https://ant.design/docs/react/migration-v4-cn)查看