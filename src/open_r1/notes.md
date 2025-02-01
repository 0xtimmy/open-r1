# Runnign sft.py
```
python ./src/open_r1/sft.py --model_name_or_path Qwen/Qwen2.5-Math-1.5B-Instruct     --dataset_name HuggingFaceH4/Bespoke-Stratos-17k     --learning_rate 2.0e-5     --num_train_epochs 1     --packing     --max_seq_length 2048     --per_device_train_batch_size 1     --per_device_eval_batch_size 1     --gradient_accumulation_steps 4     --gradient_checkpointing     --bf16     --logging_steps 5     --eval_strategy steps     --eval_steps 100     --output_dir data/Qwen2.5-1.5B-Open-R1-Distill
```