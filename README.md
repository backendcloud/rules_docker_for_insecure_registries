﻿# rules_docker_for_insecure_registries

## 使用方法


在项目根目录的WORKSPACE中，原来的rules_docker配置如下：（仅举例，每个项目用的官方的rules_docker版本不尽相同）

```bash
http_archive(
    name = "io_bazel_rules_docker",
    sha256 = "95d39fd84ff4474babaf190450ee034d958202043e366b9fc38f438c9e6c3334",
    strip_prefix = "rules_docker-0.16.0",
    urls = [
        "https://github.com/bazelbuild/rules_docker/releases/download/v0.16.0/rules_docker-v0.16.0.tar.gz",
        "https://storage.googleapis.com/builddeps/95d39fd84ff4474babaf190450ee034d958202043e366b9fc38f438c9e6c3334",
    ],
)
```

在项目根目录的WORKSPACE中将上面的内容替换成下面的内容：（具体替换内容以发布页为准）

[rules_docker_for_insecure_registries](https://github.com/backendcloud/rules_docker_for_insecure_registries/releases/tag/rules_docker_for_insecure_registries)
