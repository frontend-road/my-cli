# 开发cli辅助开发
- `npm init -y`
- package.json 文件中新增 bin
- 本地开发时使用 `npm link` 将 bin 命令链接到 npm 全局
- `npm -g list --depth=0` 查看全局命令

## 演示命令
```sh
my-cli
# 查看版本号
my-cli -V
# 模仿vue cli或cra，从远端仓库clone项目生成项目模板
my-cli create hello-world
```
