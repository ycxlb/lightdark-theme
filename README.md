HA明暗主题
# Homeassistant 明暗主题

深海蓝配色的 Home Assistant。

## 特点
- 🌊 深海蓝色调，护眼舒适
- ☀️🌙 支持明暗双模式自动切换
- 🎨 精心调色的状态图标和卡片样式

## 安装

### 通过 HACS
1. 打开 HACS → 右上角菜单 → 自定义仓库
2. 添加仓库 URL，类别选择 **Theme**
3. 安装后在 用户资料 → 主题 中切换

### 手动安装
1. 复制 `themes/lightdark-theme.yaml` 到 `config/themes/`
2. `configuration.yaml` 中添加：
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes/
开发者工具 → 服务 → 调用 frontend.reload_themes
