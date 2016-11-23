# qGo
`g`: Interactively Manage Your Golang Versions. Inspired by [GitHub-tj/n](https://github.com/tj/n)

## Demo
![](demo.gif)

## Usage
- clone repo
```
git clone https://github.com/adolphlwq/qGo.git
```
- help info
```
cd qGo
geek@localhost:qGo$ bin/g -h
    Usage: g [options] [COMMAND] [args]

    Commands:

      g                   Output help information
      g ls                Output all Golang versions
      g use               Use specific version
      g rm                Remove the given version
      g info              Display installed golang package information

    Options:

      -h, --help          Display help information
```
- use go version
```
bin/g use
```
- see current state
```
geek@localhost:qGo$ bin/g info
qGo version:
  0.0.1
Golang version in used:
  go1.7.2
Base directory:
  /usr/local/golang
Download direstory:
  /usr/local/golang/versions
Downloaded packages:
  -go1.7.3
  -go1.7.2
```

## Reference
- [Terminal Input Translation](https://www.gnu.org/software/screen/manual/html_node/Input-Translation.html)
- [shell `command`](https://www.ibm.com/support/knowledgecenter/zh/ssw_aix_72/com.ibm.aix.cmds1/command.htm)
- [用shell写俄罗斯方块(一)](http://blog.chinaunix.net/uid-26833883-id-3153839.html)
- [How can I create a select menu in a shell script?](http://askubuntu.com/questions/1705/how-can-i-create-a-select-menu-in-a-shell-script/55901)
