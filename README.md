# pipeline_test
`accelerate config`
(Select deepspeed ZeRO or fsdp with cpu offload )

`accelerate test`

`accelerate launch run_translation_no_trainer.py \
    --model_name_or_path Helsinki-NLP/opus-mt-en-ro \
    --source_lang en \
    --target_lang ro \
    --dataset_name wmt16 \
    --dataset_config_name ro-en \
    --output_dir ~/tmp/tst-translation`
