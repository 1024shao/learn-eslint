# 在React项目中使用ESLint

> 经过之前的实战，我们对ESLint的理解应该是比较深入了，接下来我们就应该在实际的框架级应用中去使用ESLint来为我们的应用保驾护航了🚢～

## 目标

- 初始化react项目
- 初始化ESLint
- 在react项目中运行ESlint

## Coding

- 使用`pnpm dlx create-react-app ./react-project` 创建react项目

![image-20220701000815553](https://tva1.sinaimg.cn/large/e6c9d24egy1h3qpybcyh7j213a0hy0uf.jpg)

- 创建好项目后，进入项目根目录，运行`eslint --init`进入命令行界面初始化ESLint

![image-20220630233825420](https://tva1.sinaimg.cn/large/e6c9d24egy1h3qp3bcfltj20xg0dqacz.jpg)

- 在项目添加lint的script并运行`pnpm run lint`

![image-20220701001449392](https://tva1.sinaimg.cn/large/e6c9d24egy1h3qq55bwksj20ru0jkgo9.jpg)

## 效果

运行lint脚本后的效果

![image-20220701002252640](https://tva1.sinaimg.cn/large/e6c9d24egy1h3qqditw9mj215i0q6grq.jpg)

如何修复上面的错误呢，我们需要在`.eslintrc`中配置一些参数来修复它们

![image-20220701002459095](https://tva1.sinaimg.cn/large/e6c9d24egy1h3qqfpwa6dj20yn0u0785.jpg)

再次运行lint，可以看见没有任何`lint`错误信息了

![image-20220701002547095](https://tva1.sinaimg.cn/large/e6c9d24egy1h3qqgjpavuj21660by74y.jpg)