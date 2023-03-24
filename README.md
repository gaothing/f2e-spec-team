# 前端开发规范约定及配套工具

---

##简介

「中大前端开发规范」是中大内部前端开发规范的约束和指导。旨在统一代码风格、代码缺陷检查 、提高代码阅读性、降低前端开发成本，提升项目的可维护性和稳定性。

本项目是基于[「 阿里巴巴前端规约及配套工具」](https://gitee.com/mirrors_alibaba/f2e-spec)结合公司实际情况整理而来。

规范主要通过***「文档约定」***和***「配套工具」***两部分。

## 文档约定

文档约定分为编码约定和工程化约定

- 编程约定
  - [html编码约定](./docs/html.md) 
  - [css编码约定](./docs/css.md)
  - [javascript编码约定](./docs/js.md)
  - vue 编码约定
  - react编码约定
  - [node编码约定](./docs/node.md)
- 工程化约定
  - [更新日志约定 ](./docs/log.md)
  - [文档阅读](./docs/doc.md)
  - [git约定](./docs/log.md)

## 配套工具
多个规约工具和对应的规则包
|规约|Lint工具|规则包|
| --- | --- | --- |
|《Javascript编码规约》 <br/> 《TypeScript 编码规约》 <br/> 《Vue 编码规约》 <br/> 《React 编码规约》 <br/> 《Node.js 开发规约》  | ESLint | eslint-config-zd|
| 《CSS 编码规约》     |  [stylelint](https://stylelint.io/)  | [stylelint-config-ali](https://www.npmjs.com/package/stylelint-config-ali) |
| 《Git 规约》     |  [commitlint](https://commitlint.js.org/#/)  | [commitlint-config-ali](https://www.npmjs.com/package/commitlint-config-ali) |
| 《文档通用规约》     |  [markdownlint](https://github.com/DavidAnson/markdownlint)  | [markdownlint-config-ali](https://www.npmjs.com/package/markdownlint-config-ali) |









