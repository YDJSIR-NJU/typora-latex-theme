# 安装教程

这里给出精简的安装教程。  

## 安装前

安装本主题前，**请确保您已经安装 Typora**.
请注意，`Supplemental` 文件夹中的 `essay-template.md` 和 `essay-template.pdf` 展示了一篇小论文在该主题下的效果（其中文字来源于我本人的课程作业以及一些拼凑，请不要在意过多细节），其中论文封面（也单独放置在 `cover-template.md` 文件中）、摘要、关键词和其他一些特别的元素使用 HTML 代码来编写。您可以自行取用修改它们的文字内容部分和代码部分来完成您的课程论文。  

## 安装 LaTeX 主题

以下给出两种安装途径，请任选其一执行。  

### 1. 手动安装

请您打开安装包的 `target` 文件夹，按照[官方教程（英文）](https://theme.typora.io/doc/Install-Theme/)，将这个文件夹里的所有 CSS 文件复制到指定的 Typora 主题文件夹中。 

### 2. 自动安装

- 如果您正在使用 Windows 操作系统，请运行 `install.ps1` 文件。具体的运行方式是：右键点击 `install.ps1` 文件，然后点击“使用 PowerShell 运行”。  
    若您看到了以下提示，请输入`Y`，然后按下回车`enter`：  
    > 执行策略更改  
    > 执行策略可帮助你防止执行不信任的脚本。更改执行策略可能会产生安全风险，如 https:/go.microsoft.com/fwlink/?LinkID=135170 中的 about_Execution_Policies 帮助主题所述。是否要更改执行策略?  
    > [Y] 是(Y)  [A] 全是(A)  [N] 否(N)  [L] 全否(L)  [S] 暂停(S)  [?] 帮助 (默认值为“N”):  

- 如果您正在使用 macOS ，请运行 `install.sh` 文件。具体的运行方式是：打开*终端*，将 `install.sh` 文件拖入终端窗口中。如果您不知道如何打开终端，请参考以下步骤：打开[启动台](https://support.apple.com/zh-cn/HT202635)；在启动台顶部的搜索栏里，搜索“终端”，然后点击搜索结果中的终端图标。  
- 本主题目前没有对 Linux 的完善支持。如果您在使用 Linux ，且愿意体验本主题，您也可以通过先下载 `latex-theme-macos.zip`，再运行 `install.sh` 的方式进行安装。  

## 安装字体

**以上步骤执行完毕后， Typora 显示的结果可能并不符合您的预期，主要是一些字体与您的预期不符。这时，您需要安装本主题依赖的所有字体。**您可以在  [Keldos-Li/typora-latex-theme-fonts](https://github.com/Keldos-Li/typora-latex-theme-fonts) 仓库下载并安装您需要的字体。您需要下载的文件有这些：  

- Mac 用户可以前往 [`/macOS`](https://github.com/Keldos-Li/typora-latex-theme-fonts/tree/main/macOS) 和 [`/General platform`](https://github.com/Keldos-Li/typora-latex-theme-fonts/tree/main/General%20platform) 获取适用于 macOS 的额外字体。  
- Windows 用户可以前往 [`/Windows`](https://github.com/Keldos-Li/typora-latex-theme-fonts/tree/main/Windows) 和 [`/General platform`](https://github.com/Keldos-Li/typora-latex-theme-fonts/tree/main/General%20platform) 获取适用于 Windows 的额外字体。  
- 本项目对 Linux 的支持还不完备。若您正在使用 Linux 且愿意体验这个主题，请自行寻找合适的中文字体，并对主题文件进行修改。  

建议您根据您的操作系统，下载对应文件夹下的所有 `.zip` 文件，解压后进行安装，以达到最好的使用体验。  

## 最后一步

启动或重新启动 Typora，然后在菜单栏的**主题**下拉菜单中选择 `Latex` 或 `Latex Dark` 选项。
