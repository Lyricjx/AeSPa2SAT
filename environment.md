# AeSPa Environment

## Environment Summary

- Python: 3.10.20
- PyTorch: 2.5.0+cu118
- CUDA Toolkit: 11.8
- GCC/G++: 11.4
- NumPy: 1.26.4
- mamba-ssm: 2.2.2
- transformers: 4.44.2
- pandas: 2.3.3
- matplotlib: 3.10.9
- tensorboard: 2.21.0
- hydra-core: 1.3.2

## Notes

- PyTorch is built with CUDA 11.8.
- CUDA Toolkit 11.8 is used to compile the CUDA extensions required by `mamba-ssm`.
- GCC/G++ 11 is used for compatibility with CUDA 11.8.
- `mamba-ssm==2.2.2` is compiled from the official source repository.
- `transformers==4.44.2` is used for compatibility with `mamba-ssm==2.2.2`.
