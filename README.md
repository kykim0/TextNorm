# TextNorm

This repo contains the benchmark data and relevant artifacts for our paper [Confidence-aware Reward Optimization for Fine-tuning Text-to-Image Models](https://openreview.net/pdf?id=Let8OMe20n) published at ICLR 2024.

## TIA2 Benchmark
The Text-Image Alignment Assessment (TIA2) benchmark comprises a diverse collection of text prompts, images generated using Stable Diffusion v2.1 for those prompts, and human annotations for each text and image pair.
The full set of images can be downloaded from [Google Drive](https://drive.google.com/drive/folders/1sgWSzlFm740PFCngcRmsgN2J5oPYncCW).

The `human_annotations` folder contains the three human labels for each text and image pair.
The `prompts` folder contains the sets of prompts used to implement TextNorm.
Lastly, the `alignment_scores` folder contains the average metrics computed with the baseline reward models and TextNorm for each prompt.

## Citation

```bibtex
@inproceedings{kim2023confidence,
  title={Confidence-aware Reward Optimization for Fine-tuning Text-to-Image Models},
  author={Kim, Kyuyoung and Jeong, Jongheon and An, Minyong and Ghavamzadeh, Mohammad and Dvijotham, Krishnamurthy Dj and Shin, Jinwoo and Lee, Kimin},
  booktitle={The Twelfth International Conference on Learning Representations},
  year={2024}
}
```