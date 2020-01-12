# Celcius-tech (Thermistor) application

Greenhouse live temperature mesurement analytics

### Live version of client-side application you may find [here](https://celcius-tech.herokuapp.com/)

## Description

IoT React.js client application that subscribes to a topic on MQTT Broker and reads LIVE data from topic channel. In a particlar case application reads LIVE temperature mesurements in a greenhouse and displays analytics in a dynamic chart.

This client application is only a part of the whole system of temperature mesurement analytics. The server side of the application your can find [here](https://github.com/romanplkh/java-iot-thermistor)

Inspired by previous hack-a-thons, application was created with intent of learning more about IoT, network programming.

## Installation

```bash
    npm install

    npm start
```

## Usage

- Fork and clone application
- Install dependencies
- Since it is only client side of a system, you need to clone and fork server side from my another repo [java-iot-thermistor](https://github.com/romanplkh/java-iot-thermistor) with additional instructions

- To be able to read data from MQTT server you will need an instance of MQTT Broker running on your localhost. You may download a version of an open source MQTT Broker from [here](http://emqtt.io/downloads/)

## Credits:

Thank you [Chris Cusak](https://github.com/chrisecusack) for helping out with installation and configuration instructions for [EMQTT Broker](http://emqtt.io)

## License:

Copyright © by Roman Pelikh. You are 100% allowed to use this application for both personal or commercial use, but NOT to claim it as your own project.
A credit to the original author, Roman Pelikh, is of course highly appreciated!

### Languages and Technologies used:

React.js, Eclipse PAHO MQTT, Erlang MQTT, CSS
