# upload_infra

Overview of the Infra

```mermaid
graph TB;
    id1(frontend)-->id2(backend)
    id2-->id3(filechecker)
    id3-->id4(Apache Tika)
    id4-->id3
    id3-->id5(Ollama)
    id5-->id3
    id3-->id6(Vector DB)
    id6-->id3
```

