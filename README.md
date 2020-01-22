# [vscode-helloworld](https://github.com/Markhng/vscode-helloworld)

"Hello world!" demonstrations for LaTeX, C++, Python in <del>IDE</del> Editor VS Code (Visual Studio Code)

## Introduction
Visual Studio Code is a modern editor that allows you customizing to coding better.
You can customize VS Code by installing extensions and creating some short config files.

This project is a Minimum Working Example (*in my opinion*😉) to show how to print `Hello world!` **in different programming languages** by using VS Code.
This project is tested only on my **Windows 10** computer. If you are using a Mac or Linux machine, some details may differ.

## Getting Started
Before printing `Hello world!`, we need to [install VS Code](https://code.visualstudio.com/Download) first.

The [official documentation](https://code.visualstudio.com/docs) is always very important and very accurate， we should read it first.

However, in some cases, the official documentation assumes that we should know something but we don't actually know it.
I know this is not their intention, because they are already proficient in using these softwares, and the basic operations are not worth introducing.
Learning a lot of new concepts at once can be difficult for some newbies. So in this project, I will only introduce the [*Tips*](#tips) that have to be understood.
Instead, I will post the operations and the related config files. You just need to:

1. Make some preparations for your external development environment (e.g. TeX Live for LaTeX);
2. Download the subfolder (e.g. [latex](./latex/)) you need into your computer;
3. Right-click the folder (e.g. [latex](./latex/)) and click **"Open Folder as VS Code Project"**;
4. Install some specific extensions mentioned in specified [*Instructions*](#instructions);
5. Compile or run the project through the [*Instructions*](#instructions), and witness "Hello world!";
6. Make some changes to the source file(s) (not config file(s)), re-compile or re-run, until meeting your requirements.

I believe that in your later use, you will gradually understand the reasons for these configurations.

## Instructions
- [ ] [LaTeX](latex/README.md)
- C / C++
	- [ ] [gcc / MinGW C++](cpp-gcc/README.md)
	- [ ] [MSVC C++](cpp-msvc/README.md)
- Python
	- [ ] [Vanilla Python](python/README.md)
	- [ ] [Python with Anaconda](python-conda/README.md)
- [ ] [Java](java/README.md)

## Tips
Like [VIM](https://www.vim.org/) and other editors, the settings of VS Code are human-editable files.
All settings for each project are located in `./.vscode/`, and they are all in [JSON](https://code.visualstudio.com/Docs/languages/json) format.
In general, for most projects, three settings files are important. They are:
- `settings.json`: [configurations for extensions and Editor itself](https://code.visualstudio.com/docs/getstarted/settings);
- `tasks.json`: [configurations for compiling or running](https://code.visualstudio.com/Docs/editor/tasks);
- `launch.json`: [configurations for debugging](https://code.visualstudio.com/Docs/editor/debugging);

(Global settings for Windows 10 device are located in `%APPDATA%/Code/User/`, e.g. `C:/Users/Markhng/AppData/Roaming/Code/User/`,
you can copy some global settings to here)

## Reference
These configurations are not the focus of this project. Most of them are simple. Here are just some links for reference:
- [Color theme](https://code.visualstudio.com/docs/getstarted/themes)
- [Key bindings](https://code.visualstudio.com/docs/getstarted/keybindings)
- [Remote development](https://code.visualstudio.com/docs/remote/remote-overview)

## License
The content of the project <span xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/Markhng/vscode-helloworld/"  property="dct:title">vscode-helloworld</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/Markhng/" property="cc:attributionName" rel="cc:attributionURL">Huang Yuxi</a> itself is licensed under the <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

And the underlying source code is licensed under the <a rel="license" href="https://opensource.org/licenses/MIT">MIT License</a>.