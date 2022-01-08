# Laravel Test Runner

## Build and push images

```bash
#!/usr/bin/env bash

docker build ./version8/php8.1/ -t seriquynh/laravel-test-runner:v8-php8.1

docker push seriquynh/laravel-test-runner --all
```
