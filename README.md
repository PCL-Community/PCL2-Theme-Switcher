# 一个能切换 PCL2 自定义主题的颜色的工具
目前由 [@Ad_closeNN](https://github.com/Ad-closeNN) 开发，~~不过源代码是一坨大便~~ 还在早期阶段（？不过能用就是了。

# 使用方法
> [!IMPORTANT]
> 很重要，务必仔细查阅。

> [!CAUTION]
> 在执行**加载**（覆盖 `PCL\setup.ini` ） `.ini` 文件覆盖到 `setup.ini` 文件**前**切记要把 `setup.ini` 备份（当然**不**备份也行，程序会自动帮你备份，看你对 `setup.ini` 有多重视）。
## 安装
> [!NOTE]
> 如果你在 GitHub Release 下载很**慢**，可以试试由 [jsdelivr](https://www.jsdelivr.com) 提供的 [CDN](https://baike.baidu.com/item/%E5%86%85%E5%AE%B9%E5%88%86%E5%8F%91%E7%BD%91%E7%BB%9C/4034265) 。阅读完下面的注意事项后可以使用该 [下载地址](https://cdn.jsdelivr.net/gh/PCL-Community/PCL2-Theme-Switcher/PCL2%20Theme%20Switcher.abc) 进行下载。

> [!WARNING]
> 注意：**jsdelivr 无法直接下载仓库内的 .exe 文件，如果使用上一个链接进行下载，需要把后缀名从 `.abc` 改为 `.exe`**。

- 在 [Releases](https://github.com/PCL-Community/PCL2-Theme-Switcher/releases) 中下载 `PCL2.Theme.Switcher.exe`（~~由于 GitHub Release Assets 里面不能包含空格所以空格就变成**点**了~~）。
- 将其放在与 PCL2 启动器（一般为 `Plain Craft Launcher 2.exe`）**同一目录下**，并确保存在 **PCL** 文件夹以及 **PCL\setup.ini** 。
- **打开**本程序，**等待初始化完毕**：**PCL2 启动器同一目录下**出现 `PCL2 Theme Switcher` 文件夹。随后请**手动关闭**本程序并**重新打开**。

## 使用
- **完成**上述**说明：** [安装](#安装) 后，打开本程序。
- 按下键盘上的 `1` 为保存 **PCL2 自定义主题**的**颜色值及透明度**。填写完保存文件的名字后，程序会将**颜色数值、透明度**保存到 `PCL2 Theme Switcher\saves\<保存文件的名字>.ini` 。
- 按下键盘上的 `2` 为**加载**（覆盖 `PCL\setup.ini`） `PCL2 Theme Switcher\saves\` 里的 `.ini` 存档文件。注意：执行前请务必做好对 `PCL\setup.ini` 备份，尽管本程序**会**自动备份（保存为 `PCL2 Theme Switcher\setup.ini`。

> [!NOTE]
> 不会将其他数值覆盖（如窗口标题），只会覆盖需要的颜色值。

# 数值信息
> [!NOTE]
> 前面的数值为存储在 `PCL\setup.ini` 里的数据（如 `UiLauncherTheme:14`） ，后面的数值为在 PCL2 里查看的，比如：  
![1725765206387.png](https://www.freeimg.cn/i/2024/09/08/66dd1659a2830.png)
- `UiLauncherTransparent` : **透明度**，0 为 **40%** 不透明，600 为 **100%** 不透明
- `UiLauncherDelta` : **色调渐变**，0 为 **-90** 色调渐变，180 为 **+180** 色调渐变
- `UiLauncherSat` : **饱和度**，0 为 **0%** 饱和度，100 为 **100%** 饱和度
- `UiLauncherHue` : **色调**，0 为 **0°** 色调，360为 **360°** 色调
- `UiLauncherLight` : **亮度**，0为 **-20** 亮度， 40 为 **+20** 亮度

