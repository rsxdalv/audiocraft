# Audiocraft (Fork, works with Apple Silicon)

This repo is a fork that works with Apple Silicon devices (e.g. M1 Macbook Pro). The original that can be found here: https://github.com/facebookresearch/audiocraft

## Installation

To install, you need to slightly modify the pip install command. Clone this repository and `cd` into the root directory of the repo. Then run the following commands:
```bash
# creating a virtual environment is optional (but recommended).
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip

# this step is required.
pip install --pre --extra-index-url https://download.pytorch.org/whl/nightly/cpu -e .
```