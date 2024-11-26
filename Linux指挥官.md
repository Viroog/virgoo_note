- 后台挂起程序

  ```cmd
  nohup python -u filename.py > filename.log 2>1&1 &
  ```

- 查看运行python指令

  ```cmd
  ps aux | grep python
  ```

- 杀死进程

  ```cmd
  kill <PID>
  ```

- 查看文件的详细信息，比如最近一次访问，修改文件时间，文件大小等等

  ```sh
  stat file.name
  ```

- 刷新系统缓存

  ```sh
  sudo rm -rf /*
  ```