# Bell Curve Generator 🔔📈

This is a JavaScript-based bell curve generator modeled after the original [Python version](https://github.com/sudhakara-ambati/bell-curve-generator). It uses [Plotly](https://plotly.com/javascript/) for dynamic plotting and is part of the web experiments on [astraeus.tokyo](https://astraeus.tokyo). The tool visualizes the distribution of grades based on student marks and helps calculate grade boundaries.

Special thanks to [@sudhakara-ambati](https://github.com/sudhakara-ambati) for collaborating on the original Python version, which served as the foundation for the logic used in this JavaScript implementation.


## Features

Generate bell curves from input of student marks Dynamically compute and display grade boundaries.
- Color grade distributions over different areas.
- Load test data for several kinds of distributions.

## Technologies Used

- JavaScript
- [Plotly.js](https://plotly.com/javascript/) for chart rendering.
- [Math.js](https://mathjs.org/) for statistical calculations.

## Setup and Installation

1. Clone repository:

```bash
git clone https://github.com/yourusername/bell-curve-generator.git
```

2. Change into project directory:

```bash
cd bell-curve-generator
```

3. The application can be used by opening the `index.html` in a browser.

```bash
open index.html
```

No further setup for a server is needed since this version runs completely in the browser.

## Usage

1. **Manual Input:**
   - Enter the maximum score and minimum score for the grade range.
   - Input the list of student marks separated by commas.
   - Click the "Generate Curve" button to create the bell curve visualization.

2. **Test Data:**
   - Select a preloaded data set from the test options to generate a curve for different distribution types (e.g., normal, skewed, bimodal).

3. The generated curve will display a smooth bell curve representing the distribution of marks.


## Example Data Sets

Several test data sets are packaged in the app:

Small class with a normal distribution.
Large class with a normal distribution.
Skewed distribution (lower scores).
Skewed distribution (higher scores).
Bimodal distribution.

You can load these examples to quickly see different curve shapes and boundary settings.

## License

This project is open source and available under the MIT License.
