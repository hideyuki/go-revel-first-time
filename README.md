# My First Revel: Web framework for Go

Revel: [http://robfig.github.io/revel/](http://robfig.github.io/revel/)

# Use gvm

About gvm: [https://github.com/moovweb/gvm](https://github.com/moovweb/gvm)

```
$ bash < <(curl -s -S -L https://raw.githubusercontent.com/moovweb/gvm/master/binscripts/gvm-installer)
$ source ~/.gvm/scripts/gvm
$ gvm listall
$ gvm install go1.3
$ gvm use go1.3 --default
$ gvm pkgset create --local
$ gvm pkgset use --local
$ gvm pkgset list

gvm go package sets (go1.3)

=>L /Users/username/github/go-revel-first-time
    global
    local
```

# Instalation Revel

```
$ go get github.com/robfig/revel/revel
```

# Demo

```
$ revel run github.com/robfig/revel/samples/chat
$ open http://localhost:9000
```

# Add new project

```

```