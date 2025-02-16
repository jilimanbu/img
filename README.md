# img图床仓库
## PicGo接入github图床
### 支持功能
* 可视化界面上传，自动复制Markdown格式链接
* 图片删除自动同步

### 接入指南
1. PicGo下载配置

下载链接：https://picgo.github.io/PicGo-Doc/zh/guide/

注：
* mac建议使用2.4.9.beta以上版本，可使用插件市场找到插件
* 使用插件市场的前提是安装node.js，下载链接：https://nodejs.org/zh-cn/download
  * 安装npm
  * npm安装TypeScript
  * 配置node环境变量

2. github图床配置

![图床配置项展示](https://github.com/user-attachments/assets/760dff63-10aa-4dcb-ab38-1438d3e91788)

3. picgo-plugin-github-plus插件下载
* 插件市场安装时会发现页面展示已安装，但切换页面发现插件仍然未安装不可用，查看日志确认问题
  * https://github.com/wayjam/picgo-plugin-s3/issues/51
    * 检索插件的npm package：https://www.npmjs.com/package/package
    * 查看picgo的插件资源文件夹（mac：/Users/xxxx/Library/Application Support/picgo/node_modules），确认插件资源是否与npm发布的数据一致
    * 删除不一致的插件资源
    * 重新通过picgo插件市场下载
  * 手动导入不能直接导入github仓库资源，因为与npm实际发布资源不一致
 
4. todo 快捷键设置
5. todo 截屏上传

