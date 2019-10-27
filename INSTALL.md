# Installation

## Requirements
- Python >= 3.6
- Numpy
- PyTorch 1.3
- [fvcore](https://github.com/facebookresearch/fvcore/): `pip install 'git+https://github.com/facebookresearch/fvcore'`
- [torchvision](https://github.com/pytorch/vision/) that matches the PyTorch installation.
  You can install them together at [pytorch.org](https://pytorch.org) to make sure of this.
- simplejson: `pip install simplejson`
- GCC >= 4.9
- PyAV: `conda install av -c conda-forge`
- ffmpeg (4.0 is prefereed, will be installed along with PyAV)
- PyYaml: (will be installed along with fvcore)

## Pytorch
Please follow PyTorch official instructions to install from source:
git clone --recursive https://github.com/pytorch/pytorch

## PySlowFast

Clone the PySlowFast Video Understanding repository.
```
git clone https://github.com/facebookresearch/slowfast
```

Add this repository to $PYTHONPATH.
```
export PYTHONPATH=/path/to/PySlowFast/lib:$PYTHONPATH
```

### Build PySlowFast

After having the above dependencies, run:
```
git clone git@github.com:facebookresearch/slowfast.git
cd slowfast
python setup.py build develop
```
