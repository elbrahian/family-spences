# FamilySpences Platform

Arquitectura basada en microservicios y eventos usando RabbitMQ.

## Arquitectura
- Frontend: React
- API (Producer): Spring Boot
- Processor (Consumer): Spring Boot
- Mensajería: RabbitMQ

## Puertos
- Frontend: 5173
- API: 8080
- Processor: 8090
- RabbitMQ: 15672

## Flujo
Frontend → API → RabbitMQ → Processor

## Pruebas
- JMeter

## Repositorios
- API (Producer): https://github.com/JuanCarJ/familyspencesapi.git
- Processor (Consumer): https://github.com/jpg27/processor_family_familySpences.git
- Frontend: https://github.com/juanpanore/familyspencesapp.git
