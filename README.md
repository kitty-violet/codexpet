# Codex Pet Share

一组可用于 Codex 的自定义宠物资源，包含 Dora、咕咕嘎嘎和 Miku 三个宠物。

## 内容

```text
dora/
  pet.json
  spritesheet.webp
gugu-gaga/
  pet.json
  spritesheet.webp
miku/
  pet.json
  spritesheet.webp
```

每个宠物目录都包含一个描述文件 `pet.json` 和一张精灵图 `spritesheet.webp`。

## 安装

1. 完全退出 Codex。
2. 将 `dora`、`gugu-gaga`、`miku` 文件夹复制到：

   ```text
   %USERPROFILE%\.codex\pets
   ```

3. 重新启动 Codex。
4. 在 Codex 的宠物设置中选择需要使用的宠物。

如果目标目录不存在，可以手动创建 `pets` 文件夹。

## 配置

通常不需要修改配置。每个 `pet.json` 负责定义宠物的 ID、显示名称、描述、精灵版本和精灵图路径。

配置字段说明见 [配置说明](docs/配置说明.md)。

## 文件说明

详细目录结构和资源说明见 [文件说明](docs/文件说明.md)。

## 隐私与安全

本仓库只包含宠物描述文件和精灵图，不包含账号凭据、`auth.json`、API 密钥或访问令牌。

使用其他 Codex 配置时，请不要把个人配置、认证文件或密钥复制到本仓库。

## 许可证

本项目使用 MIT License，具体内容见 [LICENSE](LICENSE)。

