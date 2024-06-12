<h1 align="center">
	🚀 Opération Liberté
</h1>

## 💡 About the project

    🚀 TLDR: We successfully decoupled BI from the operational database.


## Objective
- Utilizing Kafka as a generic utility for Event-Driven Architecture (EDA), and the HAPI FHIR server for mapping and data storage in PostgreSQL.

## My Contributions to the Project:

- Orchestrated the setup and configuration of the environment, utilizing Docker to deploy essential services such as Kafka, Zookeeper, and PostgreSQL.
- Configured Kafka with a single topic.
- Configured the gem [WaterDrop](https://github.com/karafka/waterdrop) for sending messages to Kafka.
- Developed the necessary code within one of the models to ensure that relevant information was sent to the Kafka topic after each change occurred.

## 🛠️ Team

- @LeonMoreno
- @davpatrik

## Results of the Hackathon

- 2nd place in the Hackathon