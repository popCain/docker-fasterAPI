# docker-fasterAPI
NEXT+fastAPI

### [Install Linux on Windows with WSL](https://learn.microsoft.com/en-us/windows/wsl/install)

```shell
# when wsl help comment do next
wsl --install
# avialable linux os
wsl --list --online
# download one you like
wsl --install -d Ubuntu-20.04
```
- [x64 マシン用 WSL2 Linux カーネル更新プログラム パッケージ](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi)
  ```shell
  wsl --set-default-version 2
  wsl -l -v
  wsl --set-version Ubuntu-20.04 2
  ```
