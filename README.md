# shosubgo
Small tool to Grab subdomains using Shodan api.

#### Quoted in the vídeo https://www.youtube.com/watch?v=qLTe6Z10vj8 h@cktivitycon 2020: The Bug Hunter's Methodology v4: Recon Edition by 0x0G

## Get your shodan api FREE with limit usage:
<https://developer.shodan.io/api/requirements>

## Install

```bash
$ go install github.com/incogbyte/shosubgo@latest
# verify inside your $GOPATH the folder "bin"
```

## Usage
```bash
go run main.go -d target.com -s YourAPIKEY / go run main.go -f file -s YourAPIKEY
```
## Usage download from releases:

https://github.com/incogbyte/shosubgo/releases/tag/1.1

```bash
# From Download Releases

./shosubgo_linux -d target.com -s YourAPIKEY
./shosubgo_linux -f file -s YourAPIKEY
```

![shosubgo](https://raw.githubusercontent.com/incogbyte/shosubgo/master/shosubgo.png)


![gopher](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTFcFPxQzLnq18PnHBkUxF6KfavmHX9q6Ukz-JWSNOg7iJu7Dsy)
