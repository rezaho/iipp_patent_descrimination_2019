# iipp_patent_descrimination_2019


# Installation

## Cloning the USPTO_2019 repository
```
cd destination/path
git clone https://github.com/rezaho/uspto_2019.git
````

## Installing dependencies
In case you need to run the BigQuery commands, you need to first set-up the Google Cloud console. Please follow the instruction in [Google Big Query Quick Start](https://cloud.google.com/bigquery/docs/quickstarts/quickstart-client-libraries#client-libraries-install-python).

We recommend you to create a new virtual environment using `Conda` or `pip` package managers.
The following code creates a new environment for Conda users using the `requirements.txt` file provided in this repository:
```
# using Conda
conda create --name <env_name> --file requirements.txt

conda activate <env_name>
````
If you prefer using `pip` , you may use the following code:
```
# using pip
pip install -r requirements.txt

```
