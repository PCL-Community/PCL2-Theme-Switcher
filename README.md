# 一个能切换 PCL2 自定义主题的颜色的东西
目前由 [@Ad_closeNN](https://github.com/Ad-closeNN) 开发，~~不过源代码是一坨大便~~还在早期阶段（？不过能用就是了。

# 使用方法
> [!IMPORTANT]
> 很重要，务必仔细查阅

> [!CAUTION]
> 在执行**加载**（覆盖 `PCL\setup.ini` ） `.ini` 文件到 setup.ini 文件
## 安装
- 在 [Releases](https://github.com/PCL-Community/PCL2-Theme-Switcher/Releases) 中下载 `PCL2.Theme.Switcher.exe`（~~由于 GitHub Release Assets 里面不能包含空格所以空格就变成**点**了~~）。
- 将其放在与 PCL2 启动器（一般为 `Plain Craft Launcher 2.exe`）**同一目录下**，并确保存在**PCL**文件夹以及**PCL\setup.ini**。
- **打开**本程序，**等待初始化完毕**：**PCL2 启动器同一目录下**出现 `PCL2 Theme Switcher` 文件夹。随后请**手动关闭**本程序并**重新打开**。

## 使用
- **完成**上述**说明：** [安装](#安装) 后，打开本程序。
- 按下键盘上的 `1` 为保存 **PCL2 自定义主题**的**颜色值及透明度**。填写完保存文件的名字后，程序会将**颜色数值、透明度**保存到 `PCL2 Theme Switcher\saves\<保存文件的名字>.ini` 。
- 按下键盘上的 `2` 为**加载**（覆盖 `PCL\setup.ini`） `PCL2 Theme Switcher\saves\` 里的 `.ini` 存档文件。注意：执行前请务必做好对 `PCL\setup.ini` 备份，尽管本程序**会**自动备份（保存为 `PCL2 Theme Switcher\setup.ini`。

> [!NOTE]
> 不会将其他数值覆盖（如窗口标题），只会覆盖颜色值

# 信息
- `UiLauncherTransparent` : 获取当前透明度，0为40%不透明，600为100%不透明
- `UiLauncherDelta` : **主题色调渐变**，0为-90色调渐变，180为+180色调渐变
- `UiLauncherSat` : **主题饱和度**，0为0%饱和度，100为100%饱和度
- `UiLauncherHue` : **主题色调**，0为0°色调，360为360°色调
- `UiLauncherLight` : **主题亮度**，0为-20亮度，40为+20亮度

