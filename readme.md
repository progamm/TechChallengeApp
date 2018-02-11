# Vibrato Tech Test App

This app is a work in progress and not ready yet

## Compile from source

`go get github.com/Virato/TechTestApp`

run `build.sh`

the `dist` folder contains the compiled web package

## Start server

update `config.toml` with database settings

`./TechTestApp updatedb` to create a database and seed it with test data

`./TechTestApp serve` will start serving requests