# @moneko

项目开发工具，致力于提供友好的开发语言，使用它能快速进行微前端（乾坤）、组件库、门户网站、中台管理、h5移动端项目的开发，目前支持React、Solidjs

特点：
1. 自己实现的虚拟化文本国际化、路由、文档生成、案例生成、changelog生成等功能
2. 多环境启动配置分离、缓存分离、极速打包
3. 支持打包 apk，mock、支持通过yapi进行mock。
4. 文件结构声明式路由、补充路由
5. 虚拟模块
6. 集成commitlint进行提交检验
7. 模块联邦
8. 打包阶段进行seo优化
9. 快速部署GitHub pages并进行seo优化，支持history路由模式
10. 智能化生成API文档（library模式）
11. library案例实时编辑实时渲染，支持直接在浏览器中写JSX语法
12. 微前端(乾坤)
13. 模块按需导入
14. 使用 swc 进行react、solidjs的jsx语法转换转译

文档：https://monako97.github.io/neko-ui/cli (暂定)

## 安装

```sh
npm install @moneko/cli -g
```

## 使用

```sh
mo create 应用名称
```

## 启动

```sh
mo start 应用类型 框架
```

## 打包

```sh
mo build 应用类型 框架
```
