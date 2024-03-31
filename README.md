React Native是一个流行的框架，用于开发跨平台的移动应用程序。它允许开发者使用JavaScript来创建同时适用于iOS和Android平台的原生应用程序。以下是一个React Native快速入门指南，帮助你开始构建你的第一个React Native应用程序。

### 必备条件

在开始之前，你需要确保你的开发环境中安装了Node.js。你可以通过运行`node -v`在命令行中检查Node.js是否已安装。此外，你还需要安装npm（Node.js的包管理器），它通常与Node.js一起安装。

### 创建React Native应用

1. **安装create-react-native-app**:
   使用npm安装create-react-native-app命令行工具，这是开始构建新React Native应用程序的最简单方式。运行以下命令：
   ```bash
   npm install -g create-react-native-app
   ```

2. **创建新项目**:
   创建一个名为"AwesomeProject"的新React Native项目，然后启动它：
   ```bash
   create-react-native-app AwesomeProject
   cd AwesomeProject
   npm start
   ```
   这将启动一个开发服务器，并在终端中打印一个QR码[1]。

3. **运行应用程序**:
   在iOS或Android手机上安装Expo客户端应用程序，并确保你的计算机和手机连接到同一无线网络。使用Expo应用程序扫描终端中的QR码以打开你的项目[1]。

4. **修改应用程序**:
   现在你已经成功运行了应用程序，让我们对其进行修改。在你选择的文本编辑器中打开`App.js`文件并编辑一些行。应用程序应该会在你保存更改后自动重新加载[1]。

### 运行应用程序在模拟器或虚拟设备上

如果你想在iOS模拟器或Android虚拟设备上运行你的应用程序，你可以按照与原生代码构建项目的说明来安装Xcode和设置你的Android环境。一旦设置好这些，你可以通过运行`npm run android`在Android虚拟设备上启动你的应用程序，或者在iOS模拟器上运行`npm run ios`（仅限macOS）[1]。

### 注意事项

使用Create React Native App创建项目时，你不会构建任何原生代码。如果你需要添加原生代码，你可能需要“eject”项目，并按照React Native CLI的指南进行操作[1]。

### 学习更多

如果你对React Native感到好奇并想要学习更多，可以继续阅读官方文档和教程。React Native的官方文档提供了详细的指南和教程，可以帮助你深入了解如何使用这个框架[1][2][4][5][7]。

这个快速入门指南提供了开始使用React Native所需的基本步骤。随着你对React Native的熟悉，你可以探索更高级的功能，如使用React Navigation来添加导航[6]，或者深入了解状态管理和组件生命周期[7]。如果你在设置或开发过程中遇到问题，React Native社区和文档是很好的资源，可以帮助你解决问题[8]。

Citations:
[1] https://s-pace.github.io/react-native/docs/getting-started.html
[2] https://getstream.io/blog/react-native-android-ios-setup/
[3] https://reactnative.dev/docs/environment-setup
[4] https://www.simplilearn.com/react-native-tutorial-article
[5] https://reactnative.dev/docs/getting-started
[6] https://reactnavigation.org/docs/getting-started/
[7] https://reactnative.dev/docs/tutorial
[8] https://www.reddit.com/r/reactnative/comments/tn9oal/getting_started_with_react_native_feeling_a_bit/
