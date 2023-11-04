# nodejs-web-reactjs-express-api-basic-auth-ssl-axios-dolt

## Description
A reactjs that uses expressjs api that uses basic authentication
and self signed ssl. The api then connects to a dolt database.

| username | password |
| -------- | -------- |
| *maria* | *pass* |

Features: 
- component with parameters
- css grid
- axios
- promise
- cors
- basic authentication
- self signed ssl

## Tech stack
- reactjs
- axios
- expressjs
- webpack
- dolt

## Docker stack
- alpine:edge
- dolthub/dolt-sql-server
- node:latest
- bayesimpact/react-base:latest

## To run
`sudo ./install.sh -u`
- [Availble here](http://localhost/)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Express ssl code](https://dev.to/omergulen/step-by-step-node-express-ssl-certificate-run-https-server-from-scratch-in-5-steps-5b87)