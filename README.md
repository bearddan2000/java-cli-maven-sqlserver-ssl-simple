# java-cli-maven-sqlserver-ssl-simple

## Description
A java maven build, that connects to sqlserver database.

Sql server uses self-signed ssl.

## Tech stack
- java
- maven
  - 6.8.2

## Docker stack
- alpine:edge
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
