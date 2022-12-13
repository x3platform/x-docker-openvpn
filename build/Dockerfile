# 将官方 Alpine 运行时用作父镜像
FROM x3platform/alpine
# 维护该镜像的用户信息
LABEL maintainer="ruanyu <ruanyu@x3platform.com>"

RUN apk add bash easy-rsa iptables libintl inotify-tools openssl openvpn=2.5.6-r1 openvpn-auth-ldap=2.0.4-r4

# Configure tun
RUN mkdir -p /dev/net && mknod /dev/net/tun c 10 200 