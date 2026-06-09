# snowdreamtech/homebrew-tap

[Homebrew](https://brew.sh/) tap，用于安装 [snowdreamtech](https://github.com/snowdreamtech) 维护的 formulae 和 casks。

> 🇬🇧 [English](README)

## 可用 Casks

| Cask                                              | 描述                                                              |
| ------------------------------------------------- | ----------------------------------------------------------------- |
| [unirtm](https://github.com/snowdreamtech/UniRTM) | UniRTM (Uni Runtime and Tools Manager) — 跨平台开发者工具链管理器 |

## 安装

### 添加 Tap

```sh
brew tap snowdreamtech/tap
```

### 安装 UniRTM

```sh
brew install --cask unirtm
```

或者一步完成：

```sh
brew install --cask snowdreamtech/tap/unirtm
```

### 升级

```sh
brew upgrade --cask unirtm
```

### 卸载

```sh
brew uninstall --cask unirtm
```

## 支持平台

| 平台  | 架构                  |
| ----- | --------------------- |
| macOS | Intel (x86_64)        |
| macOS | Apple Silicon (arm64) |
| Linux | Intel (x86_64)        |
| Linux | ARM (arm64)           |

## 关于 UniRTM

UniRTM 是一个跨平台的开发者工具链管理器，用于统一管理各种运行时和开发工具。

更多信息请访问 [UniRTM 项目主页](https://github.com/snowdreamtech/UniRTM)。

## 许可证

[MIT](LICENSE)
