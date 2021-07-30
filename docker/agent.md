# Agent

## Image

```text
agent {
    docker {
        image 'maven:3.8.1-adoptopenjdk-11'
        args '-v /root/.m2:/root/.m2'
    }
}
```

## File

```text
agent {
    dockerfile {
        filename 'test.Dockerfile'
        args '-v /root/.m2:/root/.m2'
    }
}
```

