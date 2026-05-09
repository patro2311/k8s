1.  I needed to change -t in docker so localhost:32000/<Image-ID>
2.  Add /etc/docker.daemon.json
    {
        "insecure-registries" = ["localhost:32000"]
    }

