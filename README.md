
# DR4R Season 6 - Lerobot 


## Train command 

```
# ACT
python lerobot/lerobot/scripts/train.py --output_dir=outputs/train/act_pusht --policy.type=act --dataset.repo_id=lerobot/pusht --seed=100000 --env.type=pusht --batch_size=64 --steps=200000 --eval_freq=25000 --save_freq=25000 --wandb.enable=true

# Diffusion policy
python lerobot/lerobot/scripts/train.py --output_dir=outputs/train/diffusion_pusht --policy.type=diffusion --dataset.repo_id=lerobot/pusht --seed=100000 --env.type=pusht --batch_size=64 --steps=200000 --eval_freq=25000 --save_freq=25000 --wandb.enable=true

# Consistency policy
python lerobot/lerobot/scripts/train.py --output_dir=outputs/train/consistency_diffusion_pusht --policy.type=consistency_diffusion --dataset.repo_id=lerobot/pusht --seed=100000 --env.type=pusht --batch_size=64 --steps=200000 --eval_freq=25000 --save_freq=25000 --wandb.enable=true

```
