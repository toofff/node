# README

Node.js JavaScript runtime

## Installation

Linux users can use the [installer](https://github.com/timonier/node/blob/master/bin/installer):

```sh
curl --location "https://github.com/timonier/node/raw/master/bin/installer" | sudo sh -s -- install
```

## Usage

### create-react-app

Run the command `create-react-app`:

```sh
# See all create-react-app options

create-react-app --help

# Run create-react-app

create-react-app admin
```

### generate-api-platform-client

Run the command `generate-api-platform-client`:

```sh
# See all generate-api-platform-client options

generate-api-platform-client --help

# Run generate-api-platform-client

generate-api-platform-client "http://127.0.0.1:8000" my-spa
```

### angular-cli

Run the command `angular-cli`:

```sh
# See all angular-cli options

ng --help

# Run angular-cli

ng new my-spa
```

### node

Run the command `node`:

```sh
# See all node options

node --help

# Run node-app

node -e 'console.log("Hello World");'
```

### npm

Run the command `npm`:

```sh
# See all npm options

npm help

# Run npm

npm install react
```

### serve

```sh
# See all serve options

serve --help

# Run serve

serve /home/morgan/Documents
```

### yarn

Run the command `yarn`:

```sh
# See all yarn options

yarn --help

# Run yarn

yarn add api-platform-admin
```

## Contributing

1. Fork it.
2. Create your branch: `git checkout -b my-new-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin my-new-feature`.
5. Submit a pull request.

__Note__: Use the script `bin/build` to test your modifications locally.

## Links

* [api-platform/client-generator](https://github.com/api-platform/client-generator)
* [facebookincubator/create-react-app](https://github.com/facebookincubator/create-react-app)
* [image "timonier/node"](https://hub.docker.com/r/timonier/node/)
* [nodejs](https://nodejs.org)
* [timonier/dumb-entrypoint](https://github.com/timonier/dumb-entrypoint)
* [yarn](https://yarnpkg.com)
* [zeit/serve](https://github.com/zeit/serve)
