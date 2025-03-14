## Bike Sharing 
Analisis data penyewaan sepeda berdasarkan kategori pengguna, hari libur, dan musim.

## Setup Environment-Anaconda
conda create --name main-ds python=3.13
conda activate main-ds
pip install -r requirements.txt

## Setup Environment-Shell/Terminal
mkdir dashboard2
cd dashboard2
pipenv install
pipenv shell
pip install -r requirements.txt

## Run Streamlit app
Streamlit run dashboard.py