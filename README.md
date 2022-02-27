[![Automation](https://img.shields.io/github/workflow/status/biaw/dstat-logger/Bot%20Stats%20Logger?label=automation)](https://github.com/biaw/dstat-logger/actions/workflows/logger.yml)
[![GitHub Issues](https://img.shields.io/github/issues-raw/biaw/dstat-logger.svg)](https://github.com/biaw/dstat-logger/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-raw/biaw/dstat-logger.svg)](https://github.com/biaw/dstat-logger/pulls)

# dstat-logger

An automatic Discord bot statistic logger. Uses [Benricheson101/dstat](https://github.com/Benricheson101/dstat) and stores output on GitHub automatically.

## Setup

1. Fork this repository
2. Add your bot token(s) to [the repository secrets](https://github.com/biaw/dstat-logger/settings/secrets/actions)
3. Edit the [.github/workflows/logger.yml](https://github.com/biaw/dstat-logger/blob/master/.github/workflows/logger.yml) file
    - Note that the workflow file has two bots configured. You can configure as many bots as you'd like, you just need their bot token. If you only need one bot logged then remove the second bot job.
4. Wait until the magic happens, or manually start the workflow under the Actions tab

## Example

Examples can be found in the [bot1.json](/bot1.json) and [bot2.json](/bot2.json) files.

## Credits

  - [Benricheson101/dstat](https://github.com/Benricheson101/dstat)