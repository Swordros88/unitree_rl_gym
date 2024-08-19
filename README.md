详细使用说明，请参考 https://support.unitree.com/home/zh/developer/rl_example
# add robot loong
  refer to https://github.com/youyou826/humanoid-gym-loong

# Training
python3  scripts/train.py --task=go2
# Test
python scripts/play.py --task=go2
# Model saved path
unitree_rl_gym/logs/{$task_name}/exported
/policies/
# Sim2sim
use Swordros88/humanoid-gym to simulate in mojocu
