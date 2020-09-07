# 微前端项目
#### 基座应用为layout，基座应用又可以叫做主应用
#### 子应用为app1，app2
#### 基座应用与子应用都是采用vue-cli脚手架搭建出来的单页面应用
#### 子应用既可以独立开发，也可以在主项目中去进行开发，子应用的开发，部署详情可以查看子应用对饮的README文件

##### 注意在主项目向本地拉代码的时候，直接运行 git clone 是生成不了完整的文件的,可能app1,app2,layout目录是空，解决这个问题，需要在后面加上：--recursive，克隆代码如下：
`
git clone https://github.com/DAHU123/micro-front-end.git --recursive
`

## 启动基座应用
```
cd layout
npm install
npm run serve
```
_启动基座应该之后，也要把对应的子应用都跑起来，要不然无法访问到子项目对应的模块_
### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
