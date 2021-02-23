# fix-me

A java maven project with 3 components that communicate over a network with the understanding and implementation of TCP protocol, sockets and ports. This project aims to focus on a complex scenario where threads
and sockets will be involved.

## Objectives

implement a server component and two client components that
exchange messages between each other, over the TCP protocol, ensuring that the messages
are well-formed and are delivered correctly. Persistence of data is a bonus for the project.

## Run

- ./build.sh (mvn clean package)

a folder called 'jars' will contain the runnable jars for each component (router, market, broker) run each component in a separate terminal

- first start the Router - ./run.sh router

- then the Market - ./run.sh market

- lastly the Broker - ./run.sh broker

The market and broker will connect to the router, will be assigned unique ID's
and will be able to communicate with each other.
