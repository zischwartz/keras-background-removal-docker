## Use

First, clone down this repo and make sure you have [docker](https://docs.docker.com/docker-for-mac/) installed.

Next put some images in `work/input`.

Then, from this directory, run:

```bash
yarn jupyter-run
```

And you should get your images back, with their backgrounds removed.

To run as a jupyter notebook, run

```bash
yarn jupyter
# and follow the directions to connect in your browser
```

---

Code originally from [here](https://github.com/rorodata/background-removal)/[here](https://medium.com/@burgalon/deploying-your-keras-model-35648f9dc5fb). This repo simply adapts it to run in docker, use jupyter, and run on a directory of images.
