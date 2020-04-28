This website introduces the _COCOP Toolkit_ to integrate industrial systems in
a decoupled yet well-scalable fashion. Decoupling refers to eliminating direct
physical dependencies between systems, whereas a scalable network remains fit
and extensible even when data volumes grow and new network nodes appear. The
approach is based on the AMQP communication protocol (RabbitMQ, in particular)
and standard-based message structures. Each software application (excluding
any third-party items) was implemented in
the research project COCOP (Coordinating Optimisation of Complex Industrial
Processes).


Communication stack
-------------------

* [Introduction](stack.html)
* [Cocop.MessageSerialiser](messageserialiser.html) (by Petri Kannisto)
* [Cocop.AmqpRequestResponseHelper](amqprequestresponsehelper.html) (by Petri Kannisto)
* RabbitMQ.Client (third-party API; see [https://www.rabbitmq.com/](https://www.rabbitmq.com/) )


Additional software tools
-------------------------

* [Process data simulator service for AMQP](processdatasimulator.html) (by Antti Kätkytniemi)
* [Requested history data publisher service for AMQP](requestedhistorydatapublisher.html) (by Antti Kätkytniemi)
* [COCOP Message Logger](messagelogger.html) (by Petri Kannisto and Tapio Vaaranmaa)
* [AMQP Math Tool Connector](amqpmathtoolconnector.html) (by Petri Kannisto)


Acknowledgement
---------------

<img src="logos.png" alt="COCOP and EU" style="display:block;margin-right:auto" />

COCOP - Coordinating Optimisation of Complex Industrial Processes  
[https://cocop-spire.eu/](https://cocop-spire.eu/)

This project has received funding from the European Union's Horizon 2020
research and innovation programme under grant agreement No 723661. This piece
of software reflects only the authors' views, and the Commission is not
responsible for any use that may be made of the information contained therein.
 
