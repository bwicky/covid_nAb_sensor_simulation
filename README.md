# Covid nAb sensor simulation

Code for simulating the response of COVID-19 nAb sensors.

See [Thermodynamically coupled biosensors for detecting neutralizing antibodies against SARS-CoV-2 variants](https://www.nature.com/articles/s41587-022-01280-8) for details

### Usage

1) Install conda environment for library compatibility:
conda env create -f sensor_env.yml

2) Add environment to your jupyter notebook
source activate sensor
python -m ipykernel install --user --name sensor --display-name "sensor"

3) Use this kernel (sensor) when launching the notebook
