## git 2.9.5 설치

1. 의존성 라이브러리
```sh
# yum -y install curl-devel
# yum -y install expat-devel
# yum -y install gettext-devel
# yum -y install openssl-devel
# yum -y install zlib-devel
# yum -y install perl-devel
```

2. 다운로드
```sh
# wget https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.45.0.tar.gz

```

3. 압축 풀기
```sh
# tar xvfz git-2.9.5.tar.gz
```

4.소스 디렉토리 이동
```sh
  # cd git-2.45.0
```

5. configure compile & build Environment
```sh   
# ./configure --prefix=/usr/local/poscodx/git-2.45.0
```

6. 빌드
```sh
# make all
```
   
7. 설치
```sh   
# make install
```


링크 
# cd /usr/local/poscodx
# ln -s git-2.45.0 /usr/local/poscodx/git 
8. 설정(/etc/profile)


```sh
export PATH=$PATH:/usr/local/poscodx/git/bin
```

9. 확인
# souce /etc/profile 
```sh   
# git --version
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTY4MzYyMTM0NV19
-->
