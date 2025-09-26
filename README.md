# WPS for Mac 文档格式错误修复指南

## 问题描述
在 macOS 系统下使用 WPS Office 时，可能会遇到文档格式显示错误、字体缺失或排版混乱的问题。这通常是由于缺少必要的系统字体导致的。

## 解决方案
通过安装缺失的字体文件并复制到 WPS Office 的字体目录中，可以解决文档格式显示问题。

## 准备工作
1. 确保已安装最新版本的 WPS Office for Mac
2. 关闭所有正在运行的 WPS Office 程序（Word、Excel、PowerPoint）

## 安装步骤

### 第一步：安装字体到系统
1. 打开本目录下的 `fonts` 文件夹
2. 选择所有字体文件（可以使用 `Command + A` 全选）
3. 右键点击选中的字体文件，选择"打开"
4. 在弹出的字体预览窗口中，点击"安装字体"按钮
5. 重复此过程直到所有字体都安装完成

### 第二步：复制字体到 WPS 字体目录
1. 打开"访达"(Finder)，进入"应用程序"文件夹
2. 找到 `WPS Office.app` 应用程序
3. 右键点击 `WPS Office.app`，选择"显示包内容"
4. 依次进入以下目录：
   ```
   Contents → Resources → office6 → font
   ```
5. 将本目录下 `fonts` 文件夹中的所有字体文件复制到这个 `font` 文件夹中
6. 如果系统提示需要权限，请输入管理员密码授权

### 第三步：重启 WPS Office
1. 完全退出 WPS Office 所有程序
2. 重新启动 WPS Office
3. 打开之前有格式问题的文档，检查格式是否已恢复正常

## 字体文件下载目录
所有必需的字体文件都位于本 README 文件同级的 `fonts` 目录中,可以单独下载，也可以下载"所有字体.zip"文件:https://pan.quark.cn/s/6d238aba840e。

**下载目录：** `./fonts/`

### 包含的字体文件列表
- `fonts/仿宋_常规.ttf`
- `fonts/宋体_常规.ttc`
- `fonts/华文仿宋.TTF`
- `fonts/黑体_常规.ttf`
- `fonts/楷体_常规.ttf`
- `fonts/Mac楷体GB2312.ttf`
- `fonts/Mac仿宋GB2312.ttf`
- `fonts/Mac方正小标宋简体.ttf`
- `fonts/Mac方正小标宋GBK.ttf`
- `fonts/华文宋体.TTF`
- `fonts/华文中宋.TTF`
- `fonts/华文楷体.TTF`
- `fonts/华文行楷.TTF`
- `fonts/FZXBSJW.TTF`
- `fonts/msyh.ttc` (微软雅黑)
- `fonts/msyhl.ttc` (微软雅黑 Light)
- `fonts/Fsong_GB2312.ttf`
- `fonts/Kaiti_GB2312.ttf`

## 文件结构
```
项目根目录/
├── README.md          # 本说明文件
└── fonts/             # 字体文件目录
    ├── 所有字体.zip
    ├── 仿宋_常规.ttf
    ├── 宋体_常规.ttc
    ├── 华文仿宋.TTF
    ├── 黑体_常规.ttf
    ├── 楷体_常规.ttf
    ├── Mac楷体GB2312.ttf
    ├── Mac仿宋GB2312.ttf
    ├── Mac方正小标宋简体.ttf
    ├── Mac方正小标宋GBK.ttf
    ├── 华文宋体.TTF
    ├── 华文中宋.TTF
    ├── 华文楷体.TTF
    ├── 华文行楷.TTF
    ├── FZXBSJW.TTF
    ├── msyh.ttc
    ├── msyhl.ttc
    ├── Fsong_GB2312.ttf
    └── Kaiti_GB2312.ttf
```

## 注意事项
1. **权限问题**：如果复制字体时遇到权限错误，请确保使用管理员账户操作
2. **备份重要文档**：在进行任何系统修改前，建议备份重要文档
3. **WPS 版本**：本方法适用于 WPS Office for Mac 各版本
4. **系统兼容性**：支持 macOS 10.12 及以上版本
5. **字体来源**：所有字体文件均已包含在 `fonts` 目录中，无需额外下载

## 故障排除
如果问题仍未解决：
1. 检查是否所有字体都已正确安装到系统和 WPS 字体目录
2. 尝试重启电脑后再次测试
3. 确保 WPS Office 为最新版本
4. 检查文档本身是否损坏

## 联系支持
如果按照以上步骤操作后问题仍然存在，请联系 WPS 官方技术支持或查看官方文档获取更多帮助。

---
*最后更新日期：2024年12月*  
*适用于：WPS Office for Mac*
