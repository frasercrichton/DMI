# DMI

Install and Setup

Install:

`mamba env create -f environment.yml`

Activate the environment:

`mamba activate DMI`

Updates to Python Package

`mamba env update --file environment.yml --prune`

Prerequisite

Create a .env file and add:

REPLICATE_API_TOKEN=xyz

Run 

`source .env`


gcloud init