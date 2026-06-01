# CSE 151B Competition

Open **`cse151b_comp.ipynb`** to get started.

We used a L4 GPU to run our code, and it takes about 6 hours and 30 minutes to run the code.

To run the full pipeline:
run_inference(data_path="data/private.jsonl", output_csv="results/results.csv")
You might need to run the two cells 

"import sys
!{sys.executable} -m pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121"

and

"!{sys.executable} -m pip install sympy numpy "transformers>=4.51.0" vllm tqdm bitsandbytes accelerate "antlr4-python3-runtime==4.11.1""
