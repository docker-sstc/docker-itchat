# docker-itchat

see more at [itchat](https://github.com/littlecodersh/ItChat)

## Usage

```sh
cat > main.py <<- EOM
import itchat
itchat.auto_login()
itchat.send('Hello, filehelper', toUserName='filehelper')
EOM

docker run --rm \
-v `pwd`:/app \
sstc/itchat
```

## TODO

- add default example code to /app/main.py
- add command line bot modes.
