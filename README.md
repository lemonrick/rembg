A simple flask app to remove the background of an image with [Rembg](https://github.com/danielgatis/rembg)

Watch the [tutorial](https://youtu.be/cw34KMPSt4k) on YouTube

## Run it

```
pip install -r requirements.txt
python app.py
```

## DOCKER

```bash
docker build -t removebg .
```

```bash
docker run --name removebg -p 5100:5100 removebg
```