# nmr_denoising_benchmarks
Benchmarking DESPERATE against existing denoising methods for ¹H NMR sequences.


# Installation (DO NOT RUN YET)

For Windows, open a cmd in the location you want to install, and copy-paste the following, while having Python 3.11 installed:

```
git clone https://github.com/kikiluvbrains/nmr_denoising_benchmarks
cd nmr_denoising_benchmarks
py -3.11 -m venv .venv
.venv/Scripts/Activate
python -m pip install --upgrade
pip install -r requirements.txt
```
Please make sure to install the requirements.txt to avoid conflicts between packages.

For PyTorch with CUDA,
```
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu126
```

For PyTorch with CPU,
```
pip install torch torchvision
```