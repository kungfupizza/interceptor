# Interceptor for POS machines on Sesame2
Interceptor is an interface between POS machine and Sesame2 switch interface.

## Pre-requisites
1. Create your device on [Balena](https://dashboard.balena-cloud.com/).
2. Flash your device with base BalenaOS from Balena Fleet.
3. Name your device on Balena fleet with name in naming format. `INTER-<stat>-XYZ` where `stat` can be `DEV` or `PROD` and XYZ is a 3 digit unique number. _NOTE: This can be automated later_

Development requisites are noted [here](./docs/prereqs.md)

## Deployment
Check how to deploy [documentdation](./docs/deploy.md).

## Architecture
