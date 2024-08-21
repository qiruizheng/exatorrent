# *exatorrent docker汉化版*
## 🧲 self-hostable torrent client

![GitHub Repo stars](https://img.shields.io/github/stars/varbhat/exatorrent)
![Latest Release](https://img.shields.io/github/release/varbhat/exatorrent)
![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/varbhat/exatorrent)
![GitHub License](https://img.shields.io/github/license/varbhat/exatorrent?logoColor=violet)

![Linux](https://img.shields.io/badge/Linux-%23.svg?logo=linux&color=FCC624&logoColor=black)
![macOS](https://img.shields.io/badge/macOS-%23.svg?logo=apple&color=000000&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-%23.svg?logo=windows&color=0078D6&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%23.svg?logo=docker&color=1D63ED&logoColor=white)
![Podman](https://img.shields.io/badge/podman-%23.svg?logo=podman&color=734392&logoColor=white)

<p><a href="docs/screenshots.md">Screenshots</a> &bull; <a href="https://github.com/varbhat/exatorrent/releases/latest">Releases</a> &bull; <a href="#features">Features</a> &bull; <a href="#usage"> Installation </a> &bull; <a href="docs/usage.md"> Usage</a> &bull; <a href="docs/docker.md">Docker</a> &bull; <a href="docs/build.md"> Build </a> &bull; <a href="LICENSE">License</a></p>
<hr>

* exatorrent 是用 [Go]（https://go.dev/） 编写的优雅 [BitTorrent]（https://www.bittorrent.org/） 客户端。
*它简单，易于使用，但功能丰富。
* 它可以在本地运行，也可以托管在具有良好资源的远程服务器中。
* 它是单一的、完全静态链接的二进制文件，具有零外部依赖性。
* 它重量轻，资源少。
* 它带有用 Svelte 和 Typescript 编写的美观响应式 Web 客户端。
* 感谢 exatorrent 的文档 [WebSocket]（https://datatracker.ietf.org/doc/html/rfc6455） [API]（docs/API.md），可以创建自定义客户端。
* 它支持单用户模式和多用户模式。
* 种子下载文件存储在本地磁盘中，可以通过 HTTP/浏览器/媒体播放器下载和流式传输。
 默认用户的用户名和密码分别为adminuser和adminpassword

## Usage

 * **Docker:** Docker images of exatorrent are also provided which lets exatorrent to be run in a Docker container. See [Docker Docs](docs/docker.md).
   ```bash
   docker build -t qiruizheng/exatorrent .
   或者 
   docker pull qiruizheng/exatorrent:latest
   docker run -p 5000:5000 -p 42069:42069 -v /path/to/directory:/exa/exadir qiruizheng/exatorrent:latest
   ```


## License
[GPL-v3](LICENSE)
