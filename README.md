<h1 align="center">
  <a href="https://reactnative.dev/">
    React Native
  </a>
</h1>

<p align="center">
  <strong>Learn once, write anywhere:</strong><br>
  Build mobile apps with React.
</p>

<p align="center">
  <a href="https://github.com/facebook/react-native/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="React Native is released under the MIT license." />
  </a>
  <a href="https://circleci.com/gh/facebook/react-native">
    <img src="https://circleci.com/gh/facebook/react-native.svg?style=shield" alt="Current CircleCI build status." />
  </a>
  <a href="https://www.npmjs.org/package/react-native">
    <img src="https://badge.fury.io/js/react-native.svg" alt="Current npm package version." />
  </a>
  <a href="https://reactnative.dev/docs/contributing">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=reactnative">
    <img src="https://img.shields.io/twitter/follow/reactnative.svg?label=Follow%20@reactnative" alt="Follow @reactnative" />
  </a>
</p>

<h3 align="center">
  <a href="https://reactnative.dev/docs/getting-started">Getting Started</a>
  <span> · </span>
  <a href="https://reactnative.dev/docs/tutorial">Learn the Basics</a>
  <span> · </span>
  <a href="https://reactnative.dev/showcase.html">Showcase</a>
  <span> · </span>
  <a href="https://reactnative.dev/docs/contributing">Contribute</a>
  <span> · </span>
  <a href="https://reactnative.dev/en/help">Community</a>
  <span> · </span>
  <a href="https://github.com/facebook/react-native/blob/master/.github/SUPPORT.md">Support</a>
</h3>

React Native brings [**React**'s][r] declarative UI framework to iOS and Android. With React Native, you use native UI controls and have full access to the native platform.

- **Declarative.** React makes it painless to create interactive UIs. Declarative views make your code more predictable and easier to debug.
- **Component-Based.** Build encapsulated components that manage their state, then compose them to make complex UIs.
- **Developer Velocity.** See local changes in seconds. Changes to JavaScript code can be live reloaded without rebuilding the native app.
- **Portability.** Reuse code across iOS, Android, and [other platforms][p].

React Native is developed and supported by many companies and individual core contributors. Find out more in our [ecosystem overview][e].

[r]: https://reactjs.org/
[p]: https://reactnative.dev/docs/out-of-tree-platforms
[e]: https://github.com/facebook/react-native/blob/master/ECOSYSTEM.md

## Contents

- [Requirements](#-requirements)
- [Building your first React Native app](#-building-your-first-react-native-app)
- [Documentation](#-documentation)
- [Upgrading](#-upgrading)
- [How to Contribute](#-how-to-contribute)
- [Code of Conduct](#code-of-conduct)
- [License](#-license)


## 📋 Requirements

React Native apps may target iOS 10.0 and Android 4.1 (API 16) or newer. You may use Windows, macOS, or Linux as your development operating system, though building and running iOS apps is limited to macOS. Tools like [Expo](https://expo.io) can be used to work around this.

## 🎉 Building your first React Native app

Follow the [Getting Started guide](https://reactnative.dev/docs/getting-started.html). The recommended way to install React Native depends on your project. Here you can find short guides for the most common scenarios:

- [Trying out React Native][hello-world]
- [Creating a New Application][new-app]
- [Adding React Native to an Existing Application][existing]

[hello-world]: https://snack.expo.io/@hramos/hello,-world!
[new-app]: https://reactnative.dev/docs/getting-started.html
[existing]: https://reactnative.dev/docs/integration-with-existing-apps.html

## 📖 Documentation

The full documentation for React Native can be found on our [website][docs].

The React Native documentation discusses components, APIs, and topics that are specific to React Native. For further documentation on the React API that is shared between React Native and React DOM, refer to the [React documentation][r-docs].

The source for the React Native documentation and website is hosted on a separate repo, [**@facebook/react-native-website**][repo-website].

[docs]: https://reactnative.dev/docs/getting-started.html
[r-docs]: https://reactjs.org/docs/getting-started.html
[repo-website]: https://github.com/facebook/react-native-website

## 🚀 Upgrading

Upgrading to new versions of React Native may give you access to more APIs, views, developer tools, and other goodies. See the [Upgrading Guide][u] for instructions.

React Native releases are discussed in the React Native Community, [**@react-native-community/react-native-releases**][repo-releases].

[u]: https://reactnative.dev/docs/upgrading
[repo-releases]: https://github.com/react-native-community/react-native-releases

## 👏 How to Contribute

The main purpose of this repository is to continue evolving React Native core. We want to make contributing to this project as easy and transparent as possible, and we are grateful to the community for contributing bug fixes and improvements. Read below to learn how you can take part in improving React Native.

### [Code of Conduct][code]

Facebook has adopted a Code of Conduct that we expect project participants to adhere to.
Please read the [full text][code] so that you can understand what actions will and will not be tolerated.

[code]: https://code.fb.com/codeofconduct/

### [Contributing Guide][contribute]

Read our [**Contributing Guide**][contribute] to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to React Native.

[contribute]: https://reactnative.dev/docs/contributing

### [Open Source Roadmap][roadmap]

You can learn more about our vision for React Native in the [**Roadmap**][roadmap].

[roadmap]: https://github.com/facebook/react-native/wiki/Roadmap

### Good First Issues

We have a list of [good first issues][gfi] that contain bugs which have a relatively limited scope. This is a great place to get started, gain experience, and get familiar with our contribution process.

[gfi]: https://github.com/facebook/react-native/labels/good%20first%20issue

### Discussions

Larger discussions and proposals are discussed in [**@react-native-community/discussions-and-proposals**][repo-meta].

[repo-meta]: https://github.com/react-native-community/discussions-and-proposals

## 📄 License

React Native is MIT licensed, as found in the [LICENSE][l] file.

React Native documentation is Creative Commons licensed, as found in the [LICENSE-docs][ld] file.

[l]: https://github.com/facebook/react-native/blob/master/LICENSE
[ld]: https://github.com/facebook/react-native/blob/master/LICENSE-docs

# 本地编译ReactNative

1、进入到根目录下
yarn install 会自动下载package.json中的所有依赖

踩坑命令：
yarn add react-native@0.63.0
npm info react-native@0.63.0 peerDependencies   查看react-native 依赖的react版本
yarn add react@依赖的版本号
npm install --legacy-peer-deps
npm install --force

2、gradle同步代码

3、使用19.2.5345600 ndk版本，试了高版本的ndk好像会有各种各样的问题

3、./gradlew :ReactAndroid:assembleDebug
0.63.0版本 由于hermes头文件未引入，我在本地解决了，参照当前commit


# JS代码运行
Js代码运行中遇到一些js代码的执行错误，当前用的node js版本是v20 版本，看看是不是高版本的问题
当前下载了nvm工具，node js 版本管理工具
nvm -list查看当前已安装版本
C:\Users\A>nvm list
* 20.10.0 (Currently using 64-bit executable)


下面切换到v16.15.0版本试试
nvm install 16.15.0

安装后
nvm use 16.15.0

check是否切换成功
nvm ls


安装成功后，删除node_module模块
重新执行yarn install 去安装package.json文件中的依赖

为了保险起见，我还重新编译整个ReactAndroid模块，
因为编译的hermes部分代码时从node_module部分复制过来的

安装后再打开APP，选定本地debug ip 端口，app可正常运行。




