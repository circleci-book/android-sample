# TODO App

## ローカルビルド

### Android SDK 28をインストール

Preferences -> Appereances & Behavior -> Android SDK -> Check "Android 9.0 (Pie)"

### local.propertiesを作成

```
➜  todoapp git:(todo-mvp-kotlin) cat local.properties
sdk.dir = /Users/kimh/Library/Android/sdk
```

### JAVAのバージョンを確認

```
➜  todoapp git:(todo-mvp-kotlin) java -version
openjdk version "1.8.0_222"
OpenJDK Runtime Environment (AdoptOpenJDK)(build 1.8.0_222-b10)
OpenJDK 64-Bit Server VM (AdoptOpenJDK)(build 25.222-b10, mixed mode)
```

### ローカルビルド

./gradlew androidDependencies
./gradlew lint test

