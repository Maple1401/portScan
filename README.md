## Usage:

```bash
  -h string
        指定主机IP (default "127.0.0.1")
  -p string
        指定扫描的端口 (default "1-10000")
```

## e.g.

```bash
# 扫描 1-65535
./scanPort -h 192.168.0.1 -p 1-

# 扫描 80-1000
./scanPort -h 192.168.0.1 -p 80-1000

# 扫描 22,80,8080,1024
./scanPort -h 192.168.0.1 -p 22,80,8080,1024
```