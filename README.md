# web-scaffold-vuejs

Vue.js で Web アプリケーションを docker 環境で開発する際の土台

## Commands

環境起動
```
$ docker-compose -p $USER up -d
```
環境破棄
```
$ docker-compose -p $USER down
```
パッケージ追加
```
$ docker-compose -p $USER exec app npm install <package-name>
```
Build
```
$ docker-compose -p $USER exec app npm build
```
Lint
```
$ docker-compose -p $USER exec app npm lint
```
