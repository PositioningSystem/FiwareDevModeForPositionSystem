# Dev Mode: Fiware Deployment for Positioning System

This is project is an ad-hoc implementation for sending positioning data using the [SDG](https://github.com/sfl0r3nz05/CSV-Data-Sender.git) and [Publisher Agent](https://github.com/sfl0r3nz05/Publisher-Agent.git) projects. In addition constitues the *Development Mode* of the [Fiware Production for Positioning System](https://github.com/sfl0r3nz05/FiwareProdModeForPositionSystem.git) project.

## Architecture

![Architecture](./documentation/images/Architecture.png)

## How to use

1. [Prerequsites](./documentation/Prerequsites.md) [Required].
2. [Add security features](./documentation/AddSecurityLayer.md).
3. [How to deploy the positioning system environment](./documentation/HowToUse.md) [Required].

   ### Demonstration

   - [Demonstration of sending data to the next information flow: SDG -> Publisher Agent MQTT -> Fiware](https://youtu.be/gJ2BJ4i7nQw)

## To Do

1. Create an unsecure branch
2. Create a secure branch
3. Create more endpoints for the API
4. Create a production repository based on Kubernetes