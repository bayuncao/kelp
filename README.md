# kelp(beta) - AI赋能的智能代码审计工程

`kelp`是一款智能AI审计工具，内置`prompt`集成工程，内置了各类主流编程语言的软件工程逻辑和逆向工程`prompt`提示词。kelp兼具代码审计、静态程序分析、图分析、流分析能力，以及进阶的漏洞代码验证能力(`Proof of concept`)和无害化攻击载荷(`Harmless Attack Payload`)编写能力。



## 获取授权码

`kelp`采用一机一码绑定授权，在各操作系统中执行一下命令后，通过邮箱联系我们获取授权。

### Windows

```cmd
for /f "skip=1 delims=" %a in ('wmic cpu get name ^| findstr /v /r "^$"') do @if not defined cpuName set "cpuName=%a" & echo|set /p ="CPU Model: %cpuName% | CPU Cores: %NUMBER_OF_PROCESSORS% | OS: %OS% | Architecture: %PROCESSOR_ARCHITECTURE%"
```

### Linux

```bash
当前版本暂不支持Linux操作系统。
```

### Mac

```bash
echo "CPU Model: $(sysctl -n machdep.cpu.brand_string) | CPU Cores: $(sysctl -n hw.ncpu) | OS: $(uname -s) | Architecture: $(uname -m)"
```