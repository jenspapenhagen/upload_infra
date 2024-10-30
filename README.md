# upload_infra

Overview of the Infra

```mermaid
graph TB;
    id1(frontend service)-->id2(backend service)
    id2-->id7(storage)
    id7-->id3(filechecker service)
    id3-->id4(Apache Tika)
    id4-->id3
    id3-->id5(Ollama)
    id5-->id3
    id3-->id6(Vector DB)
    id6-->id3
```
<br>
build a local docker-compose instance, for later testing
<br>

## Testrun with traefik
![a screenshot of treafik dashboard](Screenshot.png "Screenshot from treafik")