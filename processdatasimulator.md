
[<< Back to index](index.html)

# Process data simulator service for AMQP

The purpose of this application is to read data from CSV files with one
software process and push this data to AMQP message bus with another process.
The motivation stems from "simulating" the data flow in an industrial process
plant, where current measurement values a published to the message bus
regularly.

The application can be operated remotely over network. It has a Rest
(Representative State Transfer) interface implemented with JSON over HTTP.
The data is served in a standard-based message format.


## Download

* NodeJs app: https://github.com/Ana-91/Cocop.ProcessDataSimulator


## Author

* Antti Kätkytniemi, Tampere University, Finland


## Acknowledgement

<img src="logos.png" alt="COCOP and EU" style="display:block;margin-right:auto" />

COCOP - Coordinating Optimisation of Complex Industrial Processes  
[https://cocop-spire.eu/](https://cocop-spire.eu/)

This project has received funding from the European Union's Horizon 2020
research and innovation programme under grant agreement No 723661. This piece
of software reflects only the authors' views, and the Commission is not
responsible for any use that may be made of the information contained therein.
