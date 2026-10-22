# xgui

[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**xgui** - 占位分发包。

> **Note:** 本包只用于占用 PyPI 上的 `xgui` 名字，尚未发布任何功能。

## 安装

```bash
pip install xgui
```

## 发布

正式版由 tag 触发，GitHub Actions 通过 trusted publishing 上传到 PyPI：

```bash
git tag v0.1.0
git push origin v0.1.0
```

tag 的 `X.Y` 必须与 `pyproject.toml` 里的版本同一条线，否则构建阶段就失败。
