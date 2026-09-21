<div align="center">

  <!-- Waybar Status Bar Mockup -->
  <p>
    <a href="https://archlinux.org"><img src="https://img.shields.io/badge/OS-Arch%20Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white" alt="Arch Linux" /></a>
    <a href="https://hyprland.org"><img src="https://img.shields.io/badge/WM-Hyprland%20(Wayland)-00C8FF?style=for-the-badge&logo=wayland&logoColor=white" alt="Hyprland" /></a>
    <a href="https://github.com/catppuccin/catppuccin"><img src="https://img.shields.io/badge/Theme-Catppuccin%20Mocha-CBA6F7?style=for-the-badge&logo=catppuccin&logoColor=white" alt="Catppuccin" /></a>
    <a href="https://www.rust-lang.org"><img src="https://img.shields.io/badge/Core-Rust%202024-FAB387?style=for-the-badge&logo=rust&logoColor=white" alt="Rust 2024" /></a>
    <a href="https://flutter.dev"><img src="https://img.shields.io/badge/UI-Flutter%20Desktop-89B4FA?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" /></a>
  </p>

  <!-- Waybar Workspaces & Indicators -->
  <p>
    <code>[ 1: tui ]</code>
    <code>[ 2: gui ]</code>
    <code>[ 3: core ]</code>
    <code>[ 4: media ]</code>
    &nbsp;&nbsp;───&nbsp;&nbsp;
    <code>󰍛 ~5MB RAM</code> &nbsp;•&nbsp; 
    <code>⚡ &lt;10ms Boot</code> &nbsp;•&nbsp; 
    <code>󰌌 Keyboard-Driven</code>
  </p>

</div>

---

### 🖥️ Fastfetch System Information

```text
╭── aimy@hyprland:~ ─────────────────────────────────────────────────────────── [●][●][●] ──╮
│                                                                                            │
│        /\         aimy@hyprland                                                            │
│       /  \        -------------                                                            │
│      /\   \       OS          :: Arch Linux x86_64                                         │
│     /      \      Compositor  :: Hyprland (Wayland / Catppuccin Mocha)                     │
│    /   ,,   \     Kernel      :: Linux (Zen / Rolling)                                     │
│   /   |  |  -\    Terminal    :: kitty (Sixel & Kitty Graphic Protocol)                    │
│  /_-''    ''-_    Shell       :: zsh + starship prompt                                     │
│                   Tech Stack  :: Rust 2024, Flutter & Dart, C/C++, Mihomo Core             │
│                   Focus Area  :: High-Performance TUI, TUN Networking, Desktop GUI         │
│                   Benchmarks  :: Sub-millisecond latency · ~5MB footprint · Zero bloat     │
│                                                                                            │
╰────────────────────────────────────────────────────────────────────────────────────────────╯
```

---

### 🪟 Workspace 01 // TUI & Systems Core

> *Low-level systems and keyboard-centric terminal utilities built with Rust & Ratatui.*

<table>
  <thead>
    <tr>
      <th width="28%">Window / Application</th>
      <th width="24%">Stack</th>
      <th width="48%">Highlights & Architecture</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/aimy1/Rune"><b>⚡ Rune</b></a><br>
        <sub>极速键盘驱动终端启动器 & 工作台</sub>
      </td>
      <td>
        <code>Rust 2024</code><br>
        <code>Ratatui</code><br>
        <code>Sixel / Kitty Graphics</code>
      </td>
      <td>
        • 极致流畅的全键盘操控流，桌面应用毫秒级索引直达<br>
        • Dolphin 风格双栏响应式文件管理（支持字符与终端高清图像预览）<br>
        • 集成 SSH 快速会话、容器管理与终端内嵌 AI 助手
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/aimy1/Mimo"><b>🛡️ Mimo</b></a><br>
        <sub>极轻量终端代理控制中心</sub>
      </td>
      <td>
        <code>Rust 2024</code><br>
        <code>TUN Mode</code><br>
        <code>Ratatui</code>
      </td>
      <td>
        • 冷启动仅 <b>&lt;10ms</b>，常驻内存仅 <b>~5MB</b>，极致精简无任何冗余依赖<br>
        • 全局 TUN 透明网络接管，底层路由直控<br>
        • 完美融入 Hyprland / Wayland 键盘流工作流，支持 IPC 联动
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/aimy1/tune"><b>🎵 tune</b></a><br>
        <sub>现代化分栏终端网易云音乐播放器</sub>
      </td>
      <td>
        <code>Rust</code><br>
        <code>Ratatui</code><br>
        <code>Linux MPRIS</code>
      </td>
      <td>
        • 终端内 Kitty / Sixel 协议超高清专辑封面直出<br>
        • 优雅的平滑阻尼侧边栏动画与交互<br>
        • 实时 Braille 盲文音频波形频谱渲染，支持全局 MPRIS 多媒体按键
      </td>
    </tr>
  </tbody>
</table>

---

### 🪟 Workspace 02 // GUI & Desktop Workspaces

> *Modern, fluid cross-platform desktop experiences crafted with Flutter & Catppuccin design.*

<table>
  <thead>
    <tr>
      <th width="28%">Window / Application</th>
      <th width="24%">Stack</th>
      <th width="48%">Highlights & Architecture</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/aimy1/Wmimo"><b>🌐 Wmimo</b></a><br>
        <sub>现代化跨平台代理与流量管理客户端</sub>
      </td>
      <td>
        <code>Flutter 3.x</code><br>
        <code>Mihomo Core</code><br>
        <code>Desktop</code>
      </td>
      <td>
        • 天青蓝品牌视觉与圆角微卡片交互设计<br>
        • 全功能系统托盘集成：实时上下行网速看板、毫秒级一键测速、节点无缝直切<br>
        • 深度整合 Mihomo 高性能内核，高并发下依然保持低资源占用
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/aimy1/Marka"><b>📝 Marka IDE</b></a><br>
        <sub>极简工作区 Markdown 编辑器</sub>
      </td>
      <td>
        <code>Flutter Desktop</code><br>
        <code>Catppuccin Mocha</code><br>
        <code>Multi-Platform</code>
      </td>
      <td>
        • 专为专注写作与工业美学打造，5万+字大文本秒开秒滚无延迟<br>
        • VS Code 风格树状配置面板与工程化工作区管理<br>
        • 提供 Linux (RPM / AppImage / DEB) 及 macOS / Windows 原生打包支持
      </td>
    </tr>
  </tbody>
</table>

---

### ⌨️ Hyprland Keybindings & Quick Navigation

```ini
# ─── ~/.config/hypr/hyprland.conf ──────────────────────────────────────────
# Projects Navigation Map ($mainMod = SUPER)

bind = $mainMod, 1, exec, xdg-open https://github.com/aimy1/Rune      # Terminal Launcher
bind = $mainMod, 2, exec, xdg-open https://github.com/aimy1/Mimo      # TUN Proxy Center
bind = $mainMod, 3, exec, xdg-open https://github.com/aimy1/tune      # Terminal Music Player
bind = $mainMod, 4, exec, xdg-open https://github.com/aimy1/Wmimo     # Mihomo GUI Client
bind = $mainMod, 5, exec, xdg-open https://github.com/aimy1/Marka     # Markdown Workspace
```

<div align="center">
  <p>
    <a href="https://github.com/aimy1/Rune"><code>[ SUPER + 1: Rune ]</code></a> &nbsp;
    <a href="https://github.com/aimy1/Mimo"><code>[ SUPER + 2: Mimo ]</code></a> &nbsp;
    <a href="https://github.com/aimy1/tune"><code>[ SUPER + 3: tune ]</code></a> &nbsp;
    <a href="https://github.com/aimy1/Wmimo"><code>[ SUPER + 4: Wmimo ]</code></a> &nbsp;
    <a href="https://github.com/aimy1/Marka"><code>[ SUPER + 5: Marka ]</code></a>
  </p>
</div>

---

### 🛠️ Developer Toolchain

<div align="center">
  <img src="https://skillicons.dev/icons?i=rust,dart,flutter,cpp,c,ts,arch,linux,bash,git,docker,neovim&theme=dark" alt="Toolchain" />
</div>

---

### 📊 开发者战绩 (GitHub Stats & Activity)

<div align="center">
  <table border="0" style="border: none;">
    <tr>
      <td width="50%" align="center" style="border: none;">
        <img src="https://github-stats-extended.vercel.app/api?username=aimy1&show_icons=true&locale=cn&theme=catppuccin_mocha&hide_border=true&bg_color=1E1E2E&title_color=CBA6F7&icon_color=89B4FA&text_color=CDD6F4" width="100%" alt="GitHub 战绩统计" />
      </td>
      <td width="50%" align="center" style="border: none;">
        <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=aimy1&layout=donut&locale=cn&theme=catppuccin_mocha&hide_border=true&bg_color=1E1E2E&title_color=CBA6F7&text_color=CDD6F4" width="100%" alt="主力语言分布" />
      </td>
    </tr>
  </table>

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aimy1&theme=catppuccin_mocha&locale=zh_Hans&hide_border=true&background=1E1E2E&ring=CBA6F7&fire=FAB387&currStreakLabel=CBA6F7" width="100%" alt="连续打卡战绩" />
</div>

---

### ☕ Sponsor / Fuel the Machine

<details>
  <summary><b>📫 支持独立开发者的开源探索 (USDT / Crypto)</b></summary>
  <br/>
  <div align="center">
    <table>
      <tr>
        <td align="center" width="220">
          <img src="./assets/donate_qr.png" width="180" alt="USDT (APTOS) 捐赠二维码" /><br/>
          <sub><b>扫码转入 USDT</b></sub>
        </td>
        <td align="left">
          <p>💰 <b>资产币种 (Asset)：</b> <code>USDT</code></p>
          <p>🌐 <b>所属网络 (Network)：</b> <code>APTOS</code></p>
          <p>📫 <b>钱包地址 (Wallet Address)：</b><br/>
          <code>0xce0c3a1d7d8547eb7effd887095da438b89e3edd70e7c7e7927c244c2dd7f345</code></p>
          <p><sub>⚠️ 提示：转账时请务必确认选择 <b>APTOS</b> 链网络。非常感谢对开源项目的认可与支持！</sub></p>
        </td>
      </tr>
    </table>
  </div>
</details>

<br/>

<div align="center">
  <sub>Configured with ♥ in Hyprland Wayland Compositor • Catppuccin Mocha Palette</sub>
</div>
