# 训练指令
未修改train.py文件时 python legged_gym/scripts/train.py --task=g1 --num_envs=1920 --max_iterations=10000 --headless
修改train.py文件时 python legged_gym/scripts/train.py

# 测试
未修改play.py文件时 python legged_gym/scripts/play.py --task=g1
修改play.py文件时 python legged_gym/scripts/play.py


# 查看log
tensorboard --logdir logs/

# sim2sim
python deploy/deploy_mujoco/deploy_mujoco.py g1.yaml
python deploy/deploy_mujoco/deploy_mujoco.py