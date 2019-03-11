# HelloWorld - NativeScript
* [Creating Application](https://docs.nativescript.org/angular/start/cli-basics#full-setup-using-run)

## 1. Installation
```bash
$ npm i npm@latest -g

$ npm install -g nativescript
$ tns

$ ruby -e "$(curl -fsSL https://www.nativescript.org/setup/mac)"
$ cat ~/.bash_profile
$ export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_202.jdk/Contents/Home
$ export ANDROID_HOME=/Users/rwibawa/Library/Android/sdk/
```

## 2. Create and Run an application.
```bash
$ mkdir workspace_tns
$ cd workspace_tns/
$ tns create HelloWorld --template tns-template-blank-ng
$ cd HelloWorld/

# Run on ios simulator
$ tns run ios

# Run on android simulator
$ tns run android

# Run on Cloud operation (NativeScript Playground & Preview)
$ tns preview
```
