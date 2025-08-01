# Claude Code 项目记忆

## 项目信息
这是一个打地鼠游戏项目，使用 HTML、CSS 和 JavaScript 实现。

## 游戏特性
- 4x4 网格游戏界面
- 地鼠每1-2秒随机出现
- 点击地鼠得分（每次10分）
- 30秒倒计时
- 开始/重新开始按钮
- 实时分数显示
- 游戏结束显示最终分数

## 技术实现
- HTML5 语义化结构
- CSS3 动画和响应式设计
- JavaScript ES6+ 类结构
- 移动端适配

## 项目结构
- `index.html` - 完整的游戏实现

## 开发说明
- 代码结构清晰，具有良好的可读性
- 使用面向对象的设计模式
- 包含完整的游戏生命周期管理
- 响应式设计适配不同屏幕尺寸

## Claude Code 背景修改方法

### 方法一：修改终端/命令行工具的背景

**macOS Terminal:**
- Terminal → Preferences → Profile
- 选择或创建新的配置文件
- 修改背景颜色或图片

**iTerm2:**
- iTerm2 → Preferences → Profiles → Colors → Background
- 可以设置纯色或渐变背景

**VS Code 集成:**
- 修改 VS Code 的主题会同步影响集成终端
- 安装不同的主题扩展

### 方法二：检查 Claude Code 配置文件

目前没有找到 Claude Code 的特定配置文件。你可以：

1. **检查环境变量**：
   ```bash
   echo $EDITOR
   echo $VISUAL
   ```

2. **查看是否有主题设置**：
   ```bash
   claude --help
   ```

3. **检查用户配置目录**：
   - `~/.config/claude/`
   - `~/.claude/`

### 方法三：使用终端主题

**安装终端主题工具**：
- `oh-my-zsh` 主题
- `starship` 提示符
- `tmux` 主题

**示例配置**：
```bash
# 在 ~/.zshrc 或 ~/.bashrc 中添加
export TERM=xterm-256color
```

### 推荐主题
- **Dracula**: 紫色系主题
- **Solarized**: 暖色调主题
- **Monokai**: 深色主题
- **Nord**: 蓝灰色主题

## 自定义背景设置
要修改 Claude Code 的背景，你可以：

1. **修改终端背景**：
   - macOS Terminal: Terminal → Preferences → Profile
   - iTerm2: iTerm2 → Preferences → Profiles → Colors → Background
   - VS Code Terminal: 修改 VS Code 的主题或终端主题

2. **修改编辑器主题**：
   - VS Code: 更换不同的主题扩展
   - 其他编辑器类似

3. **Claude Code 特定设置**：
   - 检查是否有主题相关的配置选项
   - 查看 Claude Code 文档获取更多自定义选项

## 常用命令
- `/help` - 显示帮助信息
- `/cost` - 显示使用成本统计
- `/memory` - 打开项目记忆文件
- `/exit` - 退出 Claude Code