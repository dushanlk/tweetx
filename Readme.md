# Tweet-X

### Pre-requisites

* Java 8
* Node v8.10.0
* Maven 3.5.4
* NPM 6.10.0

### How to run

#### Tweet-X web application

1. Go to `builds` directory.
1. Run `npm install -g serve` command if you run for the first time.
1. Run `serve -s tweetx-web` command to start the web application.

#### Tweet-X server

1. Go to `builds` directory.
1. Run `./tweetx-server-0.0.1/bin/karaf` command to start with Karaf shell.
1. Or run `./tweetx-server-0.0.1/bin/start` command to start in background.

### How to build from source and run

#### Tweet-X web application

1. Go to `tweetx-web` directory.
1. Run `npm install`
1. Run `npm start`

#### Tweet-X server

1. Go to `tweetx-search` directory.
1. Run `mvn clean install`
1. Go to `tweetx-search/tweetx-server/target` directory.
1. Unzip the `tweetx-server-<version>.zip` file.
1. Run `./tweetx-server-<version>/bin/karaf` command start with Karaf shell.
1. Or run `./tweetx-server-<version>/bin/start` command start in background.

#### Check server log

1. Enter `log:tail` command in the Karaf shell and it will display the log.
2. And also you can directly check `tweetx-server-0.0.1/data/log/karaf.log` file.