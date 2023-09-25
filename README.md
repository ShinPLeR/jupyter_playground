# jupyter_playground

## About
`JupyterLab`の遊び場環境です  
めんどうなPython, Jupyter環境構築不要ですぐにデータ分析その他に使用できます

## How to use
```shell
docker-compose build
docker-compose up -d
```

`http://localhost:8888`にアクセス  
JupyterLabが起動します

ファイルデータを取り込む際は`/workspace/data`フォルダの中に入れてください

**GPUには対応していません．対応させたい場合はDockerfileを編集してください**