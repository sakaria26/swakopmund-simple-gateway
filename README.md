# Sample Gateway

Clone the repository and then build the containers with the following command:

```bash
docker compose up -d --build
```
Once it is up, navigate to `0.0.0.0:8080/welcome` to see the first redirected service and `0.0.0.0:8080/goodbye` for the other redirected service

You can manually nagivate to `0.0.0.0:5080` or `0.0.0.0:6080` for each service.

This approach ensures that for each one of our services, we never have to expose our ports to client applications
