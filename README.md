# infrastructure-server
A basic infrastructure server exposing [Zipkin](https://github.com/openzipkin/zipkin) and an [auth endpoint](https://github.com/solher/auth-nginx-proxy-companion).

# Installation
To work correctly, [Sup](https://github.com/pressly/sup), [Docker](https://github.com/docker/docker), [Compose](https://github.com/docker/compose) and [Machine](https://github.com/docker/machine) must be installed and properly configured.

How to install `Sup`:

- For Go users:

		$ go get -u github.com/pressly/sup/cmd/sup
		
- Using Homebrew:

		$ brew install https://raw.githubusercontent.com/pressly/sup/master/dist/brew/sup.rb
		
# Basic usage

To create and deploy a new local development Docker machine, run:

	$ sup dev deploy
	
To deploy to the active Docker machine, run:

	$ sup prod deploy
	