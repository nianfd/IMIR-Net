# IMIR-Net
This is the official implementation (based on PyTorch) of our paper "Ingredient-guided Multi-modal Interaction and Refinement Network for RGB-D Food Nutrition Assessment".
Including code, models, and log file.

<div align="center">
  <img src="https://github.com/nianfd/IMIR-Net/blob/main/framework.png" width=800 />
</div>

## Data and model
- [data with dish grounding](https://pan.baidu.com/s/1VzYF3wWGLrYJHH4liUEhDw?pwd=14x6)
- [pre-trained model on Nutrition5k dataset](https://pan.baidu.com/s/1x-TSXCddzoZjALfB0rIamQ?pwd=hz1e)
- [Ingredient feature extracted from CLIP text encoder](https://pan.baidu.com/s/159EDLOwMtHj549Cjube0YA?pwd=7f4d)

## Train
python train_rgbd.py

## Inference
python test_rgbd.py

## Qualitative Result
<div align="center">
  <img src="https://github.com/nianfd/IMIR-Net/blob/main/results.png" width=800 />
</div>

## Quantitative Result
- [All testset results (Our IMIR-Net with backbone Swin-B)](https://docs.qq.com/sheet/DYm5ZSXNhaml4ZU1I?u=523ecdde394d40a4b1246faf3f4107d3&tab=000001)
  <div align="center">
  <img src="https://github.com/nianfd/IMIR-Net/blob/main/alltest.png" width=900 />
</div>
