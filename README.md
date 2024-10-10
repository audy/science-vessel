# science vessel

Explorer reporting...

![Science Vessel from Starcraft](./science-vessel.png)

I use this repository to track the dependencies that I commonly use in my
Jupyter notebook environment.

## Usage

I use [uv]()

### Setup

```sh
uv venv --seed # create virtual environment
uv pip install -r pyproject.toml # install dependencies
```

### From somewhere else

```sh
source /path/to/science-vessel/venv/bin/activate
# congrats, you're now using the science-vessel
```

```
function science() {
    echo "Stand back! I'm doing science!"
    source /Users/audy/Code/science-vessel/venv/bin/activate
}
```
