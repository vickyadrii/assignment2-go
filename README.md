# Assignment 2 - Go | Kominfo x Hacktiv8

## Layered Architecture

```
├───docs        # Design file and documentation API.
├───dto         # Transport data between layers and tiers.
├───entity      # Contains all Entities and Value Objects.
├───handler     # Interaction between external clients and the application.
├───infra       # Usually connect with devops, configuration and yaml files.
├───pkg         # Utility file that reused on the same folder.
├───repository  # Responsible for interacting with storage.
├───service     # responsible for all business logic.
```

## Endpoint  
| Method        | URL               |
| ------------- | -------------     |
| GET           | /orders           |
| POST          | /orders           |
| PUT           | /orders/:orderId  |
| DELETE        | /orders/:orderId  |
