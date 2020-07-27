# @ihr/preset
`温馨提醒：创建项目依赖于wnpm源，请提前做好注册和设置。详情查看 `[WNPM](http://git.midea.com/hrms/ihr-cli/blob/master/docs/npm私有源.md)
> 基于vue-cli4 远程preset项目，用于配合vue-cli 创建一个 基于typescript实现MSV架构的项目

+ 远程创建
```
# 使用 @ihr/preset 创建一个项目 my-project 
npx vue create --preset direct:https://github.com/WayneXiao/ihr-preset.git --clone my-project
```
+ 本地创建
```
# 克隆到本地
git clone https://github.com/WayneXiao/ihr-preset.git

# 使用本地预设创建一个项目 my-project
npx vue create --preset ./ihr-preset my-project
```

+ 备选方案
```
# 使用手动预设创建一个项目 my-project [本架构基于typescript，请选上typescript]
npx vue create my-project

# 进入my-project 目录
cd my-project

# 安装 @ihr/vue-cli-plugin-lib 插件 并调用生成器
npx vue add @ihr/lib
```

