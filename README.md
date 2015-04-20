# Easy usage of vmware-view-client 

vmware-view-client is a 32-bit application with 32-bit lib dependencies. The package is available from Canonical's partner repository. With this container you can use it on any Linux distros without disturbing your 64-bit environment. 

Suggested command:

```bash
export DISPLAY=:0; sudo docker run --rm -e DISPLAY -e USER -v ~/althome/.vmware-view-client.license-accepted:/root/.vmware-view-client.license-accepted -v ~/althome/.vmware:/root/.vmware -v ~/.Xauthority:/root/.Xauthority --net=host realbazso/horizon
```

Persistent config, X integration.
