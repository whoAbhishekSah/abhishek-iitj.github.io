---
title: 'RabbitMQ - the simplest queue'
date: '2023-03-18T22:12:03.284Z'
description: 'BLOG'
---

### RabbitMQ and AMQP

RabbitMQ is a distributed message broker that works on AMQP protocol that runs on TCP. [AMQP Protocol](https://www.amqp.org/) defines the rules of message delivery. The most popular version is 0-9-1. The latest version is AMQP 1.0 but it is widely different from the former. Though RabbitMQ implements both protocols, we will scope our discussions to 0-9-1.

#### AMQP 0-9-1

The AMQP protocol message delivery is analogous to a Post Office. When we want to send a letter via PostOffice, we first put the sender and recipient information on the letter. Then the letter is put in Post box. The post office then sends the letter to appropriate places.

In AMQP model, the Exchanges play the role of Post Offices. Publishers publish the messages in Exchanges. Depending the nature of the Exchange, the messages could be sent to One or more queues. Consumers listen on these queues.

Thanks for reading. Feel free to connect with me on [Twitter](https://twitter.com/whoAbhishekSah) for any conversations on this.
