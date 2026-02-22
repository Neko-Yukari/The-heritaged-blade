# The-heritaged-blade
上海交通大学x网易高校游戏设计大赛请输入文本小组作品

## 开发环境准备

### macOS 上安装 Clash / ClashMeta

ClashMeta（Mihomo）本身是命令行内核，推荐使用带 GUI 的客户端 **Clash Verge Rev** 进行安装，它完整支持 macOS（包括 Apple Silicon 和 Intel）。

**安装步骤：**

1. 前往官方 GitHub Releases 页面下载最新版 DMG：  
   <https://github.com/clash-verge-rev/clash-verge-rev/releases>  
   - Apple Silicon (M1/M2/M3)：下载 `Clash.Verge_x.x.x_aarch64.dmg`  
   - Intel Mac：下载 `Clash.Verge_x.x.x_x64.dmg`

2. 打开 DMG，将 **Clash Verge** 拖入 Applications 文件夹。

3. 如果 macOS 提示"无法验证开发者"或"已损坏"，在终端运行：
   ```bash
   sudo xattr -r -d com.apple.quarantine /Applications/Clash\ Verge.app
   ```

4. 首次启动后，进入 **设置 → 服务模式**，安装 TUN 服务（需要管理员权限）。

5. 在 **订阅** 页面导入你的代理订阅链接，选择节点后开启 **系统代理** 或 **TUN 模式** 即可。

> **提示：** 从旧版本升级时，建议先卸载旧 TUN 服务再安装新版，避免权限冲突。
