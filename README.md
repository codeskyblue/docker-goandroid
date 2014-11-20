## golang android
Code from: <https://code.google.com/p/go.mobile>

The Dockerfile contains necessary tools, include

* golang1.4
* android-ndk,android-sdk
* java,ant,gradle
* vim,git,svn,tmux,htop,syncthing
* gobind (ref: <http://godoc.org/golang.org/x/mobile/cmd/gobind>)

## Usage

	docker pull codeskyblue/docker-goandroid
	docker run --rm -ti -p 8080:8080 -p 22000:22000 codeskyblue/docker-goandroid bash

	cd example; echo "view example projects

[See more doc](README)
