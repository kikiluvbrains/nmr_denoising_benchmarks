# nmr_denoising_benchmarks
Benchmarking DESPERATE against existing denoising methods for ¹H NMR sequences.


# Installation

For Windows, open a cmd in the location you want to install, and copy-paste the following, while having Python 3.11 installed:

```
git clone https://github.com/kikiluvbrains/nmr_denoising_benchmarks
cd nmr_denoising_benchmarks
py -3.11 -m venv .venv
.venv/Scripts/Activate
python.exe -m pip install --upgrade pip
pip install -r requirements.txt --no-cache-dir
```

Please make sure to install the requirements.txt to avoid conflicts between packages.

For PyTorch with CUDA,
```
pip install torch==2.5.1 torchvision==0.20.1 torchaudio==2.5.1 --index-url https://download.pytorch.org/whl/cu124
```

For PyTorch with CPU,
```
pip install torch==2.5.1 torchvision==0.20.1 torchaudio==2.5.1 --index-url https://download.pytorch.org/whl/cpu
```

For Mac: 
```
conda install pytorch==2.5.1 torchvision==0.20.1 torchaudio==2.5.1 cpuonly -c pytorch
git clone https://github.com/kikiluvbrains/nmr_denoising_benchmarks
```
