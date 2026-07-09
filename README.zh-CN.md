# FocusDot

[English](README.md) | [Simplified Chinese](README.zh-CN.md)

**FocusDot** 是一款用于 **macOS 菜单栏** 的专注工作应用，帮助你开始并管理专注工作时段。

这个公开仓库用于发布 **FocusDot 版本更新**、收集 **问题反馈**，以及接收 **产品改进建议**。

## 版本发布

请前往 GitHub Releases 页面下载 **最新版本**。

### 更新器提示

FocusDot 的应用内更新器已迁移到 **CrabNebula Cloud**。后续自动更新检查与下载将通过
CrabNebula Cloud 提供。

### macOS Gatekeeper 提示

当前 FocusDot 发布包 **尚未使用 Apple Developer 证书签名**。如果安装后 macOS 提示：

```text
"FocusDot" is damaged and can't be opened. You should move it to the Trash.
```

可以使用下面的命令移除隔离属性：

```sh
sudo xattr -rd com.apple.quarantine /Applications/FocusDot.app
```

## 反馈

请通过 **GitHub Issues** 提交 Bug、功能建议或其他产品反馈。

## 许可证

**MIT License**。详情请查看 [LICENSE](LICENSE)。
