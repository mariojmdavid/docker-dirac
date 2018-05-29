# docker-dirac
Dirac interware client for DIRAC4EGI: https://dirac.egi.eu/DIRAC/

## Documentation

Documentation on DIRAC and DIRAC4EGI:
* http://dirac.readthedocs.io/en/latest/UserGuide/index.html
* https://wiki.egi.eu/wiki/HOWTO22

DIRAC is installed in the `/usr/local/dirac`, there is an environment variable:

```bash
DIRAC=/usr/local/dirac
```

## Using the image

```bash
docker run --name dirac -v ~/.globus:/root/.globus -it mariojmdavid/dirac:v6r20 dirac-proxy-init -x
```

## Acknowledgments
http://dirac.readthedocs.io/en/latest/index.html

