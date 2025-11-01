# three

一个用 C 语言编写的井字棋小游戏，仓库既包含 Visual Studio 解决方案，也提供了原始源文件，可在 Windows 或命令行环境下构建。

## 项目结构

- `for tie/for tie/main.c`、`for tie/for tie/f.c`、`for tie/for tie/f.h` —— 游戏逻辑与菜单处理代码。
- `for tie/for tie/for tie.vcxproj` —— Visual Studio 工程文件。
- `for tie/x64/` —— Visual Studio 生成的预编译 Windows 可执行文件（调试版与发布版）。

## 使用 Visual Studio 构建

1. 在 Visual Studio 2022 或更高版本中打开 `for tie/for tie.sln`。
2. 选择 **Build → Build Solution**（生成 → 生成解决方案）以编译可执行文件。
3. 生成的程序位于 `for tie/x64/<Configuration>/for tie.exe`。

## 使用 GCC（MinGW 或 Linux）构建

1. 进入源代码目录：
   ```bash
   cd "for tie/for tie"
   ```
2. 编译程序：
   ```bash
   gcc main.c f.c -o tic_tac_toe
   ```
3. 运行游戏：
   ```bash
   ./tic_tac_toe
   ```

## 游戏玩法

启动可执行文件，输入 `1` 开始游戏，输入 `0` 退出。在对局过程中，根据提示输入 3×3 棋盘上的位置，直至一方获胜或平局结束。

## 许可证

本项目遵循 MIT 许可证发布，详情参见 [LICENSE](LICENSE)。
