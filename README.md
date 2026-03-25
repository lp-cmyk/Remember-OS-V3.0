# Remember-OS-V3.0
一个基于网页技术的轻量级操作系统，支持多语言、多平台运行。

## 项目结构
- `index.html`：系统入口页，加载开机动画
- `Startup_animation.mp4`：开机动画视频
- `desktop.html`：桌面主界面
- `Index.js`：核心交互逻辑（应用管理、窗口控制等）
- `apps.xml`：已安装应用配置清单
- `settings.json`：系统全局配置（主题、分辨率等）
- `style.json`：界面样式配置
- `gui.py`：Python 版图形界面工具
- `safemode.cs`：C# 实现的安全模式模块

## 快速启动
### 方式 1：PHP 内置服务器
```bash
php -S 0.0.0.0:8080
