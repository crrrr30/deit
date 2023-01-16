# Readme

```
conda install pytorch==1.7.0 torchvision==0.8.1 -c pytorch
pip install timm
pip install submitit
pip install einops
```

```
git clone https://github.com/facebookresearch/deit
python main.py --model deit_tiny_patch4_32 --batch 8192 --lr 4e-3 --epochs 10000 --weight-decay 0.05 --sched cosine --input-size 32 --eval-crop-ratio 1.0 --reprob 0.0 --smoothing 0.0 --warmup-epochs 25 --drop 0.0 --nb-classes 100 --seed 0 --opt lamb --warmup-lr 1e-6 --mixup .8 --drop-path 0.05 --cutmix 1.0 --unscale-lr --repeated-aug --bce-loss --color-jitter 0.3 --ThreeAugment --output_dir .
```
