# ekirjasto-weblogo

This container summons httpserver to show static e-kirjasto logo.  

Clone and build and run

```bash
git clone git@github.com:natlibfi-psams/ekirjasto-weblogo.git
cd ekirjasto-weblogo
buildah build -t ekirjasto-weblogo .
```

Run or pull image:
```
# or use docker
#podman pull ghcr.io/natlibfi-psams/ekirjasto-weblogo:main
podman run -d --rm --name weblogo -p 8000:80 ghcr.io/natlibfi-psams/ekirjasto-weblogo:main
```
