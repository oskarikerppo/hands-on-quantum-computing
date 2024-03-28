# Quantum Computing Hands On -Seminar

main.pdf contains the slides

In qiskit-demo you can find some jupyter notebooks 

## Requirements to run the code
Tested on Python 3.10
ipykernel==6.29.4
qiskit==1.0.2
qiskit-aer==0.13.3
qiskit-ibm-runtime==0.22.0
qiskit-experiments==0.6.0
matplotlib==3.8.3
pylatexenc==2.10
setuptools==69.2.0

Alternatively, you can install from the requirements.txt file

## Config
If you want to run on IBM hardware, you need to register on https://quantum.ibm.com/ (it's free!)
Once you have an account, copy your API token from your profile settings. Then create a file `credentials.py` with a single line `token = your-token-value`. 
