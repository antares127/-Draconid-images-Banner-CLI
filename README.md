# Draconid 横幅命令行工具

这是一个用 Python 编写的命令行小工具，用于在终端中打印一组 ASCII 横幅艺术。

## 运行方式

```bash
python Draconid.py
```

随后在命令提示符中输入横幅名，例如：

```text
August
lark
granny
casp
finn
lind
reyna
nami
solie
Draconid
```

输入 `help` 可以查看当前可用的横幅列表。

## 命令行参数

```bash
python Draconid.py --ascii
python Draconid.py --image
python Draconid.py --anim
```

- `--ascii` / `-a`：为 August 使用 ASCII 模式
- `--image` / `-i`：为 August 使用图片参考模式
- `--anim`：启用动画打印

默认情况下，动画是关闭的。

## 退出方式

在提示符中输入下面任一命令即可退出：

```text
exit
quit
q
```

## 说明

- 该脚本适用于 Windows、Linux 和 macOS 的命令行终端。
- 横幅列表会自动从脚本中以 `_` 开头的字符串变量中收集。
- 项目主文件是 [Draconid.py](Draconid.py)。
