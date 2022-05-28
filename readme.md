# setup
1. After clone this repo, open it with `Microsoft Visual Studio Community 2022 (64-bit) - Current`
2. Change Solution Platform from x86 to x64
3. Right-click the project name in the solution explorer, go to `Configuration Properties/VC++ Directories`,
append something like this to your `Include Directories`: `D:\ReposMine\common-learn\learn-opengl\learn-opengl\opengl\includes`
append something like this to your `Library Directories`: `D:\ReposMine\common-learn\learn-opengl\learn-opengl\opengl\lib;`
4. Link libraries to our project, go to `Configuration Properties\Linker\Input`, append: `glfw3.lib;opengl32.lib;`
