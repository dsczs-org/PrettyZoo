## What

A GUI for Zookeeper created by JavaFX and Curator Framework.

## Requires

- Java 1.8 +

## Download

[Download from Here](https://github.com/vran-dev/PrettyZoo/releases)

- usage
```shell
java -jar PrettyZoo.jar
```

## Features

- connect multi zookeeper server at same time

- remember your server at local

- sync node tree between server and local automatic

- you can recognize different node (persist, ephemeral) by style

- you can add / delete / update node

- recursive mode: add / delete node recursively

- ACL syntax highlight

## TODO

- [ ] support node search

- [x] support recursive delete / add (now you can only delete leaf node and add one children)

- [ ] support ACL

- [ ] more strictly check of input, and more friendly reminder

- [ ] installer of OS (exe, img, deb......)

## Example

### Main view


![](release/example/main-2.jpg)

![](release/example/main.jpg)

### add server

![](release/example/addServer.jpg)

### Double click to connect and sync

![](release/example/syncNode.jpg)

### right click item to add / delete node

![](release/example/addNode-01.jpg)

![](release/example/addNode-02.jpg)