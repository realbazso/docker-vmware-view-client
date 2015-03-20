# Easy usage of vmware-view-client 

vmware-view-client is a 32-bit application with 32-bit lib dependencies. The package is available from Canonical's partner repository. With this container you can use it on any Linux distros without disturbing your 64-bit environment. 

Suggested command:

```bash
export DISPLAY=:0; docker run --rm -e DISPLAY -v ~/althome/.vmware-view-client.license-accepted:/.vmware-view-client.license-accepted -v ~/althome/.vmware:/.vmware -v ~/.Xauthority:/.Xauthority --net=host realbazso/horizon
```

Persistent config, X integration.
