# grpc.demo.go
gRPC demo Kodi (http://kodi.tv) plugin - uses github.com/iMro0t/go-pvr for Kodi

## Build Instructions

### Linux

1. Install golan
2. Install g++
3. git clone https://github.com/DavidHillman/grpc.demo.go
4. git clone https://github.com/iMro0t/go-pvr
4. go mod init go-pvr/v18/pvr
5. go mod tidy
6. mv go-pvr grpc.demo.go/
7. cd grpc.demo.go/
8. go build -buildmode=c-shared -o grpc.demo.go/grpc.demo.go.so.0.0.1
9. zip -rq grpc.demo.go-0.0.1.zip grpc.demo.go
10. Copy to Kodi and install as music add-on

##### Useful links

- [Kodi's PVR user support](http://forum.kodi.tv/forumdisplay.php?fid=167)
- [Kodi's PVR development support](http://forum.kodi.tv/forumdisplay.php?fid=136)

