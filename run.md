### step1 创建目录
```shell
mkdir -p ./volumes/html
```

### step2 复制文件

```shell
cp -r index.php demo/demo.html src ./volumes/html
```

### step3 创建compose并启动

```shell
docker compose up -d
```

### 其他命令
#### 停止

```shell
## 停止
docker compose stop
```

#### 启动

```shell
## 启动
docker compose start
```

#### 停止容器并删除compose

```shell
docker compose down
```