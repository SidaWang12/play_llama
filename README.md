# Play with Llama

This repo is forked from https://github.com/meta-llama/llama.

Command:

```bash
torchrun --nproc_per_node 1 example_text_completion.py \
    --ckpt_dir ./Llama-2-7b \
    --tokenizer_path ./Llama-2-7b/tokenizer.model \
    --max_seq_len 512
```