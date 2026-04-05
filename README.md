### Course from
[Golang Tutorial for Beginners | Full Go Course](https://www.youtube.com/watch?v=yyUHQIec83I&t=167s)


### Commands
#### Create a new Go module
```bash
go mod init <module-name>
```


## Necessary setup for SSH Agent
### Start SSH Agent (In Host)
```bash
eval "$(ssh-agent -s)"
```

### Add your Github key to the SSH Agent (In Host)
```bash

ssh-add ~/.ssh/id_rsa
```

### Verify the agent socket exists (In Host)
```bash
ls -al $SSH_AUTH_SOCK
```
