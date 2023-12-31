# change static pod path.md

```
ps -aux | grep -i kubelete
find --config=/var/lib/kuebelete/config.yaml

nano /var/lib/kuebelete/config.yaml
staticpodpath=...
```
