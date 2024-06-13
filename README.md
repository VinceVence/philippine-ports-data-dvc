# Philippine Ports Data

This repository contains data related to Philippine ports, managed using DVC (Data Version Control).

## Getting Started

![Diagram]([DIAGRAMS] flowchart\Ports Processing Flowchart.drawio.png)

### Prerequisites

Ensure you have DVC installed. If not, install it using pip:

```bash
pip install dvc
```

## Cloning the Repository
Clone the repository to your local machine:

```bash
git clone https://github.com/VinceVence/philippine-ports-data-dvc.git
cd philippine-ports-data-dvc
```

## Pulling the Data
To pull the data files managed by DVC, use the following command:

```bash
dvc pull
```

## Directory Structure

- `.dvc` - DVC configuration files
- `[DIAGRAMS]` - Flowcharts and diagrams
- `[IPYNB]` - Jupyter Notebooks
- `[DATA]` - Port data files

## Raw Data Source

The raw data was taken from [Philippine Ports Authority Statistics](https://www.ppa.com.ph/content/statistics-1).

## Usage

Open the Jupyter Notebooks in the `[IPYNB]` directory to explore and analyze the data.Running the port processing file will create the processed files if not yet pulled using dvc.

## Contributing

Contributions are welcome. Please fork the repository and create a pull request.


## License

This project is licensed under the MIT License.
