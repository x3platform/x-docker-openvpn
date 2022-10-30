# 将官方 Alpine 运行时用作父镜像
FROM x3platform/alpine
# 维护该镜像的用户信息
LABEL maintainer="ruanyu <ruanyu@x3platform.com>"

RUN apk add openssl easy-rsa openvpn iptables bash

# Configure tun
RUN mkdir -p /dev/net && mknod /dev/net/tun c 10 200 