### One Monitoring Agent
https://github.com/Yuu5758/One-Monitoring

#### Building the agent
```bash
env CGO_ENABLED=0 GOOS=<GOOS> GOARCH=<GOARCH> go build -ldflags "-s -w"
```
