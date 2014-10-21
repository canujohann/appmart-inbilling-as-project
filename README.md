# Appmartアプリ内課金: Android project Library

![last-version](http://img.shields.io/badge/last%20version-1.1-green.svg "last version:1.1") 

![license apache 2.0](http://img.shields.io/badge/license-apache%202.0-brightgreen.svg "licence apache 2.0")


---

## 目次

```
1- 導入手順

	- パーミッション設定
	- サンプルをclone
	- Workspaceに追加 (Eclipse)
	- プロジェクトに導入（Eclipse）

---


## 導入手順


#### パーミッション設定

```xml
<!-- 課金API用 -->
<uses-permission android:name="jp.app_mart.permissions.APPMART_BILLING" />
```

#### サンプルをclone

```shell
cd /home/user/your_directory
git clone https://github.com/info-appmart/appmart-inbilling-as-project
```

> 注意点：　Eclipseにうまく読み込まれないために、workspace以外のフォルダーにcloneしてください。


#### Workspaceに追加 (eclipse)

+ ⇒ File
+ ⇒ Import
+ ⇒ Existing Android Code Into Workspace
+ ⇒ 先ほどcloneしたプロジェクトを選択

![Eclipse:appmart library](http://s14.postimg.org/5hbwc1t7l/phonegap_capture_2.png "Eclipse:appmart library")

#### プロジェクトに導入（eclipse）

+ ⇒ プロジェクトに右クリック　
+ ⇒ Properties 
+ ⇒ Android
+ ⇒ Libraries  :  Add ([appmart-inbilling-as-project]を選択)

![Eclipse:appmart](http://s27.postimg.org/wza6sbrcj/phonegap_plugin.png "Eclipse:appmart")
