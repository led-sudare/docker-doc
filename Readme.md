Dockerに関する情報をまとめます。
===

<!-- toc -->
* [🔨DockerとComposeとk8s](#-DockerとComposeとk8s)
* [📘公式ドキュメント](#-公式ドキュメント)
* [👣Get Started](#-get-started)
<!-- tocstop -->

# DockerとComposeとk8s
Dockerを扱うツールとして次のものがあります。
* Docker  
    1つのコンテナをローカル環境で構築・管理(DevOPS)するツールです。  

* Docker Compose  
    複数のコンテナをローカル環境でDevOPSするツールです。  

* Kubernetes  
    複数のコンテナをリモートでDevOPSするツールです。  
    名前が長いのでk8s(k-eightsと発音する)と呼ばれることも多いです。  


それぞれに共通しているのは次の通り。  
1. ベースとなるイメージを作成する  
2. イメージからコンテナを作成して、コンテナを起動する。  
3. 設定ファイルでもって、イメージやコンテナの構築、環境設定を行う。  


# 公式ドキュメント

## Docker
* [Dockerfile](https://docs.docker.com/engine/reference/builder/)
* [Dockerコマンド](https://docs.docker.com/engine/reference/commandline/build/)

## Docker Compose
* [Docker Compose file](https://docs.docker.com/compose/compose-file/)
* [Docker Composeコマンド](https://docs.docker.com/compose/reference/overview/)


# Get Started

## ツールインストール

**Win**
Docker & Docker Compose  
> WindowsはDockerと一緒にDocker Composeもインストールされます。

Win10 Home x64  
1. Docker Toolboxを[ここから](https://docs.docker.com/toolbox/toolbox_install_windows/)ダウンロードする。  
2. 上記ページを見ながらインストールする。  
3. デスクトップに作られたDocker QuickStartを実行してDockerコントローラを起動する。  
4. Dockerのバージョン情報が表示されればOK。  
    ```sh
    $ docker version
    Client:
    Version:       18.03.0-ce
    API version:   1.37
    Go version:    go1.9.4
    Git commit:    0520e24302
    Built: Fri Mar 23 08:31:36 2018
    OS/Arch:       windows/amd64
    Experimental:  false
    Orchestrator:  swarm

    Server: Docker Engine - Community
    Engine:
    Version:      18.09.6
    API version:  1.39 (minimum version 1.12)
    Go version:   go1.10.8
    Git commit:   481bc77
    Built:        Sat May  4 02:41:08 2019
    OS/Arch:      linux/amd64
    Experimental: false
    ```
  

Win10 Pro以上 x64  
1. Docker Desktop for Windowsを[ここから](https://docs.docker.com/docker-for-windows/install/)ダウンロードする。  
2. 上記ページを見ながらインストールする。  
3. Dockerのバージョン情報が表示されればOK.
    ```sh
    $ docker version
    ```

**Mac**
```sh
Docker & Docker Compose

```

**Linux**
```sh
Docker & Docker Compose

```
> ディストリビューション毎のパッケージ管理システムに合せて読み替えてください。

