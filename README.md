# Hello World - ASP.NET Core Docker Sample

Ta Duy Phong - phongtd@vnpt.vn\
Nguyen Manh Hung - nmanhhung@vnpt.vn\
La Duc Hai - lahai@vnpt.vn

1. Clone code project từ git
```console
git clone https://github.com/taduyphong2171979/bai-1.git
```
2. Buil docker và run
```console
cd HelloNetCore
docker build -t hellonetcore . 
docker run --name hellonetcore -p 8000:80 hellonetcore:latest
```
3. Kiểm tra trên trình duyệt
```console
http://localhost:8000
```
