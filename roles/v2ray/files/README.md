# 加密
```
openssl enc -e -in file -out file.enc  -p -aes256 -k 123
```
# 解密
```
openssl enc -d  -in file.enc -out file -aes256 -k 123
```