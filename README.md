<p align="center">
  <!-- Logo -->
  <img src="img/logo.png" alt="Logo">
</p>

<div align="center">
  <!-- Badges -->
  <img src="https://img.shields.io/badge/Windows-supported-0078D6.svg">
  <img src="https://img.shields.io/badge/Mac-supported-BFBFBF.svg">
</div>

<p align="center">
  <!-- Title -->
  <h1>kelp(beta) - AI赋能的智能代码审计工程</h1>
</p>



## 简介

`Kelp`是一款智能AI审计工具，内置`prompt`集成工程，内置了各类主流编程语言的软件工程逻辑和逆向工程`prompt`提示词。`Kelp`兼具代码审计、静态程序分析、图分析、流分析能力，以及进阶的漏洞代码验证能力(`Proof of Concept`)和无害化攻击载荷(`Harmless Attack Payload`)编写能力。

- [文档链接](https://zalw1ah0mdh.feishu.cn/docx/M6ludduTloxmEExAeo5cScUcnTg?from=from_copylink)


## 授权码

`Kelp`采用一机一码绑定授权，在各操作系统中执行一下命令后，通过邮箱联系我们获取授权。

### Windows

```cmd
for /f "skip=1 delims=" %a in ('wmic cpu get name ^| findstr /v /r "^$"') do @if not defined cpuName set "cpuName=%a" & echo|set /p ="CPU Model: %cpuName% | CPU Cores: %NUMBER_OF_PROCESSORS% | OS: %OS% | Architecture: %PROCESSOR_ARCHITECTURE%"
```

### Linux

```bash
当前版本暂不支持Linux操作系统，计划后续支持。
```

### Mac

```bash
echo "CPU Model: $(sysctl -n machdep.cpu.brand_string) | CPU Cores: $(sysctl -n hw.ncpu) | OS: $(uname -s) | Architecture: $(uname -m)"
```


## 社区

|    |    |
|--------|--------|
| ![微信](img/wechat.png)  | ![微信](img/planet.png) |


## Star 趋势
[![Stargazers over time](https://starchart.cc/bayuncao/Kelp.svg?variant=adaptive)](https://starchart.cc/bayuncao/Kelp)


