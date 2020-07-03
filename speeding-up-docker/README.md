# Speeding up Docker

[Bind-mounting](https://docs.docker.com/storage/bind-mounts/) the local filesystem into a container while developping is convenient, but it does have some performance overhead on Windows and macOS. 
There are some techniques that you can apply to improve disk performance, or you can open a repository in a container using a isolated container volume instead.

## On Windows

The most direct solution is to use the [Windows Subsystem for Linux v2 (WSL2)](https://docs.microsoft.com/en-us/windows/wsl/wsl2-about) and to enable [Docker Desktop's WSL2 back-end](https://aka.ms/vscode-remote/containers/docker-wsl2).

## On macOS

### NFS
### Delegate
### Using volume instead of bind mount
