# verbose-pancake

Running locally:
``` pwsh

# run dependencies
docker compose up -d

# run the app
go run .

```

Managing dependencies:
``` pwsh

# tidy up the go.mod file (adding or removing dependencies as necessary)
go mod tidy

# list updatable dependencies
go list -m -u all

```