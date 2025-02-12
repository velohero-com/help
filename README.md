# Velo Hero Help Center

Velo Hero Help Website: <https://www.velohero.com/help/>

## Python

Follow the [official guide](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/) so that you have a working virtual environment and `pip3` installed.

Once you have created and activated a virtual environment, install the dependencies we use for testing and tools.

```bash
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements.txt
```

## Serve

Create a current version for yourself:

```bash
mkdocs serve
```

Open notes:

```bash
open "http://127.0.0.1:8000/"
```