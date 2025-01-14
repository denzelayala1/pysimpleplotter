# PySimplePlotter

PySimplePlotter is a GUI to create simple plots.

## Installation

PySimplePlotter is still in development. The only installation method is to
clone the repo and manually install its dependencies:

1. Clone the repo

    ```
    git clone git@github.com:wodend/pysimpleplotter.git
    ```

2. Install the dependencies

    ```
    pip install pandas matplotlib pysimplegui
    ```

## Usage

Start PySimplePlotter:

```
cd pysimpleplotter/
python3 gui.py
```

## Roadmap

- Automatically detect file type
- Maybe automatically detect header for Perkin Elmer file type
- Support deleting cols from list
- Automatically detect col count for TSV file type
- Automatically fill in default plotting x and y axises from cols
- Generate default plot title from x and y axis inputs
- Create package and set up GUI as the entrypoint
- Add to PyPi for install
- Add more detail to the README Usage section
- Add in-line documentation

## License

[MIT](https://choosealicense.com/licenses/mit/)
