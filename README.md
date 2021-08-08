# react_base

reactのベース 要調整

## React公式doc

[https://ja.reactjs.org/](url)

## コピーして使う場合

- 'react-sample'を消す

- `docker-compose.yml`の`react-sample`を任意のアプリ名に変更

```docker
command: sh -c "cd react-sample && yarn start"
```

- 以下のコマンド`react-sample`を`docker-compose.yml`のアプリ名に変更

```bash
docker-compose run --rm node sh -c "npm install -g create-react-app && create-react-app react-sample"
```

参考資料

[https://qiita.com/2754github/items/413bdaaa90834e219dc8](url)
