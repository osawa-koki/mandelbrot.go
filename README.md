# mandelbrot.go

ðµðµðµ Goè¨èªã§ãã³ãã«ãã­éåãæåããã  
æ®éã«æåã¨ãgoroutineãä½¿ç¨ãã2ã¤ãç¨æã  

Goã¯åå¤§ã ððð  

![ææç©](./.development/img/fruit.png)  

## å®è¡æ¹æ³

DevContaineråã«å¥ããä»¥ä¸ã®ã³ãã³ããå®è¡ã  

```shell
# éå¸¸ç
go run ./normal/main.go

# goroutineãä½¿ã£ãæéç
go run ./faster/main.go
```

ãã£ããã¨ãã«ããå®è¡ããã«ã¯ããã  

```shell
# éå¸¸ç
go build -o ./bin/normal ./normal/main.go
./bin/normal

# goroutineãä½¿ã£ãæéç
go build -o ./bin/faster ./normal/main.go
./bin/faster
```
