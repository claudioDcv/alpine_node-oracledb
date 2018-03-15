# alpine_node-oracledb

Apline Linux with node.js with node-oracledb client ready to use.


OS: Apline Linux  
node.js: 8.10.0  
Oracle Client: 11.0 ( node-oracledb )  
Build Essentials: Packages included in windows-build-tools( C++, G++, Python 2.7, git, etc..) for Alpine-linux  
target: node-oracledb, SQLite   


to build

```terminal
docker build . -t node_oracledb
```

or get from docker hub 

```terminal
docker pull chronowalker/alpine_node-oracledb
```
