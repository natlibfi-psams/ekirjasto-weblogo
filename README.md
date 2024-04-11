# ekirjasto-weblogo

This container summons httpserver to show static e-kirjasto logo.  

Clone and build and run

```bash
git clone git@github.com:natlibfi-psams/ekirjasto-weblogo.git
cd ekirjasto-weblogo
buildah build -t ekirjasto-weblogo .
```

Run:
```
podman run -d -p 8080:80 ekirjasto-weblogo
```