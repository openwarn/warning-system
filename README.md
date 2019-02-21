# WarningSystem

This project is part of OpenWarn. It contains configuration to orchestrate and run the prototypic warning system.

## About OpenWarn

OpenWarn is a prototypic open-source warning system which leverages modern microservice architecture concepts
to build an modular and customizable integrated warning system.

It was created as part of the master thesis called
`Konzeption einer Softwarearchitektur für ein Nachrichtensystem zur Warnung der Bevölkerung in Gefahrensituationen` (conception of a software architecture for public warning message systems) at Technical University Ilmenau in 2019.

## Installation

Prerequisites: Docker >= v18.0, Docker-Compose >= v1.23.2

Make sure that all docker images used in _docker-compose.yml_ are available.
Some of them are possibly not available in a repository and must be built manually.

## Run

```bash
docker-compose up -d
```

Now open your webbrowser at http://localhost

## Contributing

Feel free to contribute to OpenWarn by creating a pull request or adding an issue.

If you are interessted in supporting this project or building a warning system based on this software, contact me via GitHub.

## License

  [MIT](LICENSE)