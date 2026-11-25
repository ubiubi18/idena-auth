# Idena auth service

### Reliability and consensus

Please treat the software in this repository as potentially unreliable. To the best of my knowledge, concerns relevant to Idena’s consensus security remain unresolved upstream.

As long as the chain continues to operate under its current rules, I will not change those rules on my own. I welcome working with upstream maintainers, node operators, and the wider Idena community to review any proposed consensus change and coordinate its adoption.

## Research disclaimer

This is experimental research software. I cannot guarantee its security, correctness, or fitness for any purpose. Use it at your own risk, take responsibility for your decisions, independently verify changes, and stay vigilant.

### Running `idena-auth`

In order to run the service you need the following:

1. Run **PostgreSQL** instance
2. Build `idena-auth` binary file (run `go build`)
3. Prepare `config.json` configuration file and put it to the working directory where `idena-auth` will be running (there is an example of `config.json` file in the root of the project)
4. Copy `resources` directory from the root of the project to the working directory
5. Run `idena-auth` binary file