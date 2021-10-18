docker-gc
=========
A simple Docker container and image garbage collection script.

Current chart version is `1.0.1`

Source code can be found [here](https://github.com/spotify/docker-gc)



## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| cron.log | string | `"/var/log/crond.log"` |  |
| cron.schedule | string | `"0 0 * * *"` |  |
| env.gracePeriodSeconds | string | `"0"` |  |
| image.org | string | `"spotify"` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.registry | string | `"docker.io"` |  |
| image.repository | string | `"docker-gc"` |  |
| image.tag | string | `"latest"` |  |
| nodeSelector | object | `{}` |  |
| resources | object | `{}` |  |
| tolerations | list | `[]` |  |
