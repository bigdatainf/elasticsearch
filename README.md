# Elasticsearch Deployment on Docker

This repository contains all necessary files for deploying [Elasticsearch](https://www.elastic.co) using Docker, with a focus on presenting Elasticsearch technology for academic purposes. Elasticsearch is a distributed search and data analytics engine, capable of handling a wide array of use cases. By utilizing Docker, we not only simplify the configuration and deployment of Elasticsearch but also ensure an easy-to-integrate and reproducible setup across different environments. 

Included in the repository is a docker-compose.yml file that sets up and runs Elasticsearch in a Docker container. Additionally, for a more interactive and educational experience, a [Jupyter](https://jupyter.org) notebook is integrated into the deployment. This notebook provides an accessible way to interact with the Elasticsearch storage system, making it an ideal setup for learning and experimentation.

## Prerequisites

Before starting, ensure you have Docker and Docker Compose installed on your system. You can download and install them from the [Docker Official Site](https://www.docker.com/get-started).

## Getting Started

To start the Elasticsearch container, follow these steps:

1. **Clone the Repository:**
````   
   git clone https://github.com/bigdatainf/elasticsearch.git
   cd elasticsearch
````

3. **Run Docker Compose:**
````
   docker compose up
````
This command downloads the Elasticsearch image (if not already downloaded) and starts the container.

4. **Verify Execution:**
- Elasticsearch: Verify by visiting [http://localhost:9200](http://localhost:9200) in your browser or using a command-line client like `curl`.
- Jupyter Notebook: Access the notebook by visiting [http://localhost:8888](http://localhost:8888) to interact with Elasticsearch.

## Elasticsearch Documentation

For more information on how to use Elasticsearch, refer to the [official Elasticsearch documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html).

## Support

For any issues or queries related to this repository, please open an issue in the 'Issues' section of the repository.


