# Update

- Run the following commands to update ltcd, all dependencies, and install it:

```bash
cd $GOPATH/src/github.com/ltcsuite/ltcd
git pull && GO111MODULE=on go install -v . ./cmd/...
```
