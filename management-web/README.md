## 前端项目启动

```bash
# 代码位置
git clone https://gitee.com/y_project/RuoYi-Vue

# 进入项目目录
cd ruoyi-ui

# 安装依赖
npm install

# 强烈建议不要用直接使用 cnpm 安装，会有各种诡异的 bug，可以通过重新指定 registry 来解决 npm 安装速度慢的问题。
npm install --registry=https://registry.npm.taobao.org

# 本地开发 启动项目
npm run dev
```

# 访问端口 http://localhost:80

## ����

```bash
# �������Ի���
npm run build:stage

# ������������
npm run build:prod
```