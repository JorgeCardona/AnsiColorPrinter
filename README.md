---

# ANSI Color Printer

The ANSI Color Printer is a Python package that provides functionality to print text with ANSI color formatting in the terminal. It allows you to apply various colors and text styles to your text output, enhancing readability and visual appeal.

## Features

- Apply ANSI color formatting to text output in the terminal.
- Choose from a wide range of colors and text styles.
- Easily integrate into your Python projects for colorful text printing.

## Installation

You can install the ANSI Color Printer package via pip:

```bash
pip install AnsiColorPrinter
```

## Usage

```python
import AnsiColorPrinter as acp

# Print red text
print(acp.red("Hello, World!"))

# Print bold blue text
print(acp.blue("Welcome!", formats=["bold"]))

# Print bold red multiple formats
print(acp.cyan("Multi Formats", formats=['underlined', 'bold', 'reverse']))                                            
```

## Available Colors

The package supports the following colors:

- List of colors...

* almond
* aqua
* aquamarine
* banana
* beige
* bisque
* black
* blue
* bone
* brass
* bronze
* brown
* bubblegum
* buff
* burgundy
* burnt_sienna
* burnt_umber
* cadet_blue
* camel
* candy
* caramel
* celadon
* cerulean
* champagne
* charcoal
* chartreuse
* cherry
* chestnut
* chocolate
* cinnamon
* claret
* copper
* coral
* cornflower
* cranberry
* cream
* cyan
* dark_gray
* denim
* ecru
* eggplant
* emerald
* emerald_green
* forest_green
* frost
* gold
* goldenrod
* gray
* grape
* grass_green
* green
* hot_pink
* hunter_green
* ice_blue
* indigo
* iris
* jade
* jungle_green
* khaki
* lavender
* lemon
* lemonade
* lilac
* lime
* lime_green
* linen
* magenta
* mahogany
* malachite
* maroon
* melon
* midnight_blue
* mint_green
* mocha
* moonstone
* moss_green
* mulberry
* mustard
* navy
* nude
* ocean_blue
* olive
* onyx
* opal
* orange
* orchid
* pale_blue
* pale_pink
* paprika
* peach
* pearl
* periwinkle
* petal_pink
* pine_green
* plum
* powder_blue
* pumpkin
* raspberry
* red
* rose
* rust
* sage
* sapphire
* sea_blue
* seafoam
* seashell
* sepia
* sienna
* sky_blue
* slate_blue
* slate_gray
* snow
* spearmint
* steel_blue
* stone
* strawberry
* sunflower
* tan
* taupe
* teal
* terracotta
* thistle
* tomato
* topaz
* tulip
* turquoise
* vanilla
* violet
* white
* yellow
                                            
## Available Text Styles

The package supports the following text styles:

- List of text styles...
* bright 
* bold 
* dim 
* italic 
* underlined 
* blink 
* reverse
                                            
## Examples

You can find more examples and usage scenarios in the [examples](examples) directory.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize and expand upon this template as needed for your project!
