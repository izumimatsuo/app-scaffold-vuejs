# app-scaffold-vuejs

Vue.js で Web アプリケーションを docker 環境で開発する際の土台

## Commands

環境起動
```
$ docker-compose up -d
```
環境破棄
```
$ docker-compose down
```
パッケージ追加
```
$ docker-compose exec app npm install <package-name>
```
Build
```
$ docker-compose exec app npm build
```
Lint
```
$ docker-compose exec app npm lint
```
