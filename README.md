# heroku-line-go-example

```
gvm use go1.8.3

gvm pkgset create vs-code
gvm pkgset use vs-code

go get -u -v github.com/nsf/gocode
go get -u -v github.com/rogpeppe/godef
go get -u -v github.com/zmb3/gogetdoc
go get -u -v github.com/golang/lint/golint
go get -u -v github.com/ramya-rao-a/go-outline
go get -u -v sourcegraph.com/sqs/goreturns
go get -u -v golang.org/x/tools/cmd/gorename
go get -u -v github.com/tpng/gopkgs
go get -u -v github.com/newhook/go-symbols
go get -u -v golang.org/x/tools/cmd/guru
go get -u -v github.com/cweill/gotests/...
go get -u -v golang.org/x/tools/cmd/godoc
go get -u -v github.com/fatih/gomodifytags
go get -u -v github.com/josharian/impl
go get -u -v github.com/derekparker/delve
go get -u -v github.com/kardianos/govendor
go get github.com/derekparker/delve/cmd/dlv

export GOPATH=`pwd`

go get -u github.com/line/line-bot-sdk-go/linebot

mkdir src/ubinix.com
mkdir src/ubinix.com/warun
mkdir src/ubinix.com/warun/chewy-xyz
cd src/ubinix.com/warun/chewy-xyz

vi server.go

govendor init
govendor add github.com/line/line-bot-sdk-go/linebot

govendor install +local

```
