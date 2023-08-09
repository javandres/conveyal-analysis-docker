# Conveyal Analisys Dockerized

This is the dockerized deploy of [Conveyal Analysis](http://conveyal.com/analysis), which allows users to create public transport scenarios and evaluate them in terms of cumulative opportunities accessibility indicators.

## Required software

- Docker

- Docker compose

## Quick Start

Clone this repository

```
git clone https://github.com/javandres/conveyal-analysis-docker.git
cd conveyal-analysis-docker
```
Clone the [R5](https://github.com/conveyal/r5): a routing engine which acts as the backend

```
git clone https://github.com/conveyal/r5.git
```

Checkout to R5 v6.4 (the compatible R5 version for the UI)

```
git checkout v6.4
```


Clone the [Analysis UI](https://github.com/conveyal/analysis-ui): the user interface

```
git clone https://github.com/conveyal/analysis-ui.git
```

Build docker images

```
docker-compose build
```

Run the stack

```
docker-compose up
```

Open the app in the browser and enjoy it [http://localhost:3000](http://localhost:3000)

