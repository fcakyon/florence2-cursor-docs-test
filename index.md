contains info on how to load model, perform inference, model sizes, benchmarks: [florence2-base readme](https://huggingface.co/microsoft/Florence-2-base/raw/main/README.md)

contains default config params as projection_dim, vocab_size, model_type, torch_dtype, patch_size, decoder_attention_heads, decoder_layers, encoder_layers: [florence2-base config.json](https://huggingface.co/microsoft/Florence-2-base/raw/main/config.json)

contains preprocessor config params as image_seq_length, size, height, image_mean"[preprocessor_config.json](https://huggingface.co/microsoft/Florence-2-base/raw/main/preprocessor_config.json)

This is the configuration class to store the configuration of a [`Florence2VisionModel`]. It is used to instantiate a Florence2VisionModel according to the specified arguments, defining the model architecture: [configuration_florence2.py](https://huggingface.co/microsoft/Florence-2-base/raw/main/configuration_florence2.py)

contains code for Florence2PostProcesser, Florence2Processor, decode_with_spans, post_process_generation, tasks_answer_post_processing_type, task_prompts_without_inputs, task_prompts_with_input, additional_special_tokens parse_description_with_bboxes_from_text_and_spans, parse_phrase_grounding_from_text_and_spans, :[processing_florence2.py](https://huggingface.co/microsoft/Florence-2-base/raw/main/processing_florence2.py)

contains code for Florence2ForConditionalGeneration, Florence2VisionModelWithProjection, Florence2VisionModel, Florence2PreTrainedModel, Florence2LanguageForConditionalGeneration, Florence2Decoder, Florence2Encoder, Florence2DecoderLayer, Florence2EncoderLayer Florence2SdpaAttention, Florence2Attention, DaViT: [modeling_florence2.py](https://huggingface.co/microsoft/Florence-2-base/raw/main/modeling_florence2.py)
