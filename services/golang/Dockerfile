ARG GOLANG_VERSION
FROM ${GOLANG_VERSION}

# RUN apt-get update && apt-get install -y vim

# 启用 GO111MODULE
RUN go env -w GO111MODULE=on
RUN go env -w GOPROXY=https://goproxy.cn,direct

WORKDIR $GOPATH