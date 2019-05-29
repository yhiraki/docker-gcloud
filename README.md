Docker gcloud
=============

Use as same as [gcloud](https://cloud.google.com/sdk/gcloud/reference/) command like:

```shell
gcloud compute instances list
```

`bq` , `gsutil` command are also available.

Installation
------------

### Use git clone

```shell
git clone https://github.com/yhiraki/docker-gcloud
export PATH=$(pwd)/docker-gcloud/bin:$PATH
```

### Use [zplug](https://github.com/zplug/zplug)

```shell
zplug "yhiraki/docker-gcloud", as:command, use:'bin/*'
```
