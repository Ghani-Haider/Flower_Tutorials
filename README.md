### Flower Framework Practice Codes

1. Introduction to Flower (Part 1)
     - Loading the dataset and centralized training in Pytorch
     - Starting on FL
         - Implementing Flower Client Class (using flwr.client.NumPyClient)
         - Implementing client_fn for Virtual Client Enginer (Flower VCE)
     - Training using FedAvg Strategy
       - Choosing strategy
       - Configuring client resource
       - Implementing client generated metric (loss, accuracy etc) aggregation function
       - Starting the simulation

1. Use A Federated Learning Strategy (Part 2)
     - Load Torchvision CIFAR10 Dataset into partitions
     - Model Training & Eval Pytorch Code For Client
     - Customizing FLOWER Client
     - Strategy Customizations
       - Server-side parameter initialization: initialized model params at server
       - Changing strategy: FedAvg to FedAdagrad etc
       - Server-side evaluation: test/val at server
       - Sending/receiving arbitrary values to/from clients: configure/set client-side params from server side


