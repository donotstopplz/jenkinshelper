# JenkinsHelper

<!--- ![Build](https://github.com/Lv-lifeng/JenkinsHelper/workflows/Build/badge.svg) --->
[![Version](https://img.shields.io/jetbrains/plugin/v/19155.svg)](https://plugins.jetbrains.com/plugin/19155)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/19155.svg)](https://plugins.jetbrains.com/plugin/19155)
![](https://komarev.com/ghpvc/?username=itisokey-jenkinshelper&color=orange&style=flat&label=pv)

<!-- Plugin description -->
### JenkinsHelper is a plugin for JetBrains IDEs, such as IntelliJ IDEA, that enables Jenkins operations on multiple jobs simultaneously.
The JenkinsHelper window is at the bottom of the IDE, it supports selecting multiple jobs to operate at the same time.
* build   
  * build with params
  * circular build if last build was failed 
  * choose last build failed jobs to build
* update
  * git branch name
  * update value of string params
  * add new string param
* error log
  * filter error log

![O6iPjU.gif](https://s1.ax1x.com/2022/05/14/O6iPjU.gif)
<!-- Plugin description end -->

### TODO LIST
1. Job list add build status and health status 
2. Support more parameter types
3. ...
## Installation

- Using IDE built-in plugin system:

  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "JenkinsHelper"</kbd> >
  <kbd>Install Plugin</kbd>

- Manually:

  Download the [latest release](https://github.com/Lv-lifeng/JenkinsHelper/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>
