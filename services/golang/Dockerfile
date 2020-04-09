ARG GOLANG_VERSION
FROM ${GOLANG_VERSION}

RUN apt update && apt install bash-completion # install bash
RUN apt-get install lsof

# 启用 GO111MODULE
RUN go env -w GO111MODULE=on
RUN go env -w GOPROXY=https://goproxy.cn,direct

WORKDIR $GOPATH