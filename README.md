# Wedjat: the eye of Horus - Kubernetes 资源监控项目

Wedjat is a Kubernetes-level resource monitoring project written in the Go language. The project is inspired by the Eye of Horus in Egyptian mythology, which symbolizes surveillance and protection.

## 特性

- **轻量级监控：** Wedjat 提供了简单而强大的 Kubernetes 资源监控功能，帮助用户更好地了解集群的状态。

- **实时数据更新：** 通过实时更新，用户可以随时查看集群的最新状态，确保高效的资源管理。

- **可视化界面：** Wedjat 提供直观的可视化界面，使用户能够快速了解集群中各个资源的使用情况。

## 快速开始

### 依赖

确保你的环境中已经安装了以下工具：

- [Go](https://golang.org/)
- [Kubernetes 集群](https://kubernetes.io/)

### 安装 Wedjat

1. 克隆项目：

    ```bash
    git clone https://github.com/yourusername/wedjat.git
    cd wedjat
    ```

2. 构建 Wedjat：

    ```bash
    go build -o wedjat main.go
    ```

3. 运行 Wedjat：

    ```bash
    ./wedjat
    ```

访问 http://localhost:8080 查看 Wedjat 的监控界面。

## 贡献

如果你想为 Wedjat 做出贡献，请查看我们的[贡献指南](CONTRIBUTING.md)。

## 许可证

Wedjat 使用 [MIT 许可证](LICENSE)。

---

感谢使用 Wedjat！如果您有任何问题或建议，请随时提出。