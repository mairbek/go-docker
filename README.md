Let's be honest, `$GOPATH` is **annoying**.

This template project requires zero installations and configurations, assuming you have `docker` installed, and allows to build and run `go` apps in the container.

Modify `.env` file and run `docker-compose run app sh`.

Inside the container run `glide install --strip-vendor` to load deps.

Inside the container run `go run main.go`.
