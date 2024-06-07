Create environment and install dependencies
```bash
git clone git@github.com:bpiyush/VideoLLaMA2.git
cd VideoLLaMA2

conda create -n videollama2 python=3.9 -y
conda activate videollama2

pip install -r requirements.txt
pip install flash-attn --no-build-isolation
```

Download weights.
```sh
# Currently not available
```