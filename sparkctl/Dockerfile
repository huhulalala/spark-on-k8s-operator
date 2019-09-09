FROM yangqizhou/dep:latest
ENV GO111MODULE="on"
RUN mkdir -p ${GOPATH}/src/github.com/GoogleCloudPlatform/spark-on-k8s-operator/sparkctl
WORKDIR ${GOPATH}/src/github.com/GoogleCloudPlatform/spark-on-k8s-operator/sparkctl
COPY . ./
#RUN go mod init github.com/GoogleCloudPlatform/spark-on-k8s-operator/sparkctl
RUN go build -o sparkctl
