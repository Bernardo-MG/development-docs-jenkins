# Running images

## Script

```text
script {
   docker.image('mongo:latest').withRun('-p 27017:27017') {}
}
```

