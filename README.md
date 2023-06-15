:pinched_fingers:

To get cool stuff on IBM Z, just go get it.  
Or, perhaps sponsor me so I can keep going.. :trollface:


PS: Contributors to [ZOSOpenTools](https://github.com/ZOSOpenTools) can now get [1Password for Teams](https://1password.com/teams/), to manage their keys and what-not.  
https://github.com/1Password/1password-teams-open-source/pull/754


| Project (builds on `zos/s390x`)                                              | Description                                                     | Port                                                                                    | Upstream (and its upstream)                                                                                                                                                                                                                                                                                 | Tests              |
|------------------------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|
| :white_check_mark: [direnv](https://github.com/direnv/direnv)                | Load & unload env and env. variables based on working directory | :white_check_mark: [direnvport](https://github.com/ZOSOpenTools/direnvport)             | :white_check_mark: https://github.com/direnv/direnv/pull/1094                                                                                                                                                                                                                                               | :white_check_mark: |
| :white_check_mark: [powerline-go](https://github.com/justjanne/powerline-go) | A prompt for your shell, showing useful info in segments        | :white_check_mark: [powerline-goport](https://github.com/zosopentools/powerline-goport) | :white_check_mark: https://github.com/justjanne/powerline-go/pull/381                                                                                                                                                                                                                                       | :white_check_mark: |
| :white_check_mark: [bump](https://github.com/wader/bump)                     | Version tracking & update tool                                  | :white_check_mark: [bumpport](https://github.com/zosopentools/bumpport)                 | N/A                                                                                                                                                                                                                                                                                                         | :white_check_mark: |
| :white_check_mark: [gotestsum](https://github.com/gotestyourself/gotestsum)  | 'go test' runner with output optimised for humans               |                                                                                         | :white_check_mark: https://github.com/gotestyourself/gotestsum/pull/334                                                                                                                                                                                                                                     | :construction:     |
| :white_check_mark: [Caddy](https://github.com/caddyserver/caddy)             | Fast and extensible HTTP web server with automatic HTTPS        |                                                                                         | :construction: https://github.com/google/certificate-transparency-go/pull/1088                                                                                                                                                                                                                              | :construction:     |
| :white_check_mark: [esbuild](https://github.com/evanw/esbuild)               | An extremely fast bundler for the web                           |                                                                                         | N/A                                                                                                                                                                                                                                                                                                         | :construction:     |
| :white_check_mark: [NATS](https://github.com/nats-io/nats-server)            | High-performance cloud & edge-native messaging system           |                                                                                         | :construction: https://github.com/nats-io/nats-server/pull/4209                                                                                                                                                                                                                                             | :construction:     |
| :white_check_mark: [Terraform](https://github.com/hashicorp/terraform)       | Infra-as-Code                                                   |                                                                                         | :construction: https://github.com/hashicorp/terraform/pull/33305 <br/> :construction: https://github.com/apparentlymart/go-userdirs/pull/2 <br/>                                                                                                                                                            | :construction:     |
| :construction: [DuckDB](https://github.com/duckdb/duckdb)                    | Ducking fast embeddable DB for analytics                        | :construction: [duckdbport](https://github.com/ZOSOpenTools/duckdbport)                 | :white_check_mark: PR1 https://github.com/duckdb/duckdb/pull/7805 <br/> :white_check_mark: https://github.com/cameron314/concurrentqueue/pull/346 <br/> :white_check_mark: https://github.com/fastfloat/fast_float/pull/207 <br/> :white_check_mark: https://github.com/yhirose/cpp-httplib/pull/1581 <br/> | :construction:     |


| Project (builds on `linux/s390x`)                                                        | Description                                                                      | Upstream (and its upstream)                                                     | Tests              |
|------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------|--------------------|
| :white_check_mark: [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) | Fast, cost-effective & simple time-series database                               | :white_check_mark: https://github.com/VictoriaMetrics/VictoriaMetrics/pull/3870 | :white_check_mark: |
| :white_check_mark: [Tyk](https://github.com/tyktechnologies/tyk)                         | API gateway supporting REST, GraphQL, TCP, and gRPC                              | :construction: https://github.com/TykTechnologies/tyk/pull/4777                 | :white_check_mark: |
| :construction: [DragonflyDB](https://github.com/dragonflydb/dragonfly)                   | Performant & scalable in-memory data store compatible with Redis & Memcached API | :construction: https://github.com/dragonflydb/dragonfly/pull/1214               |                    |
