# DeepReinforcementLearning

A deep reinforcement learning tutorial based on [ElegantRL](https://github.com/AI4Finance-Foundation/ElegantRL)



## Requirements


```conda
conda create -n rl python=3.10
conda activate rl
pip install torch==1.13.0+cu116 torchvision==0.14.0+cu116 torchaudio==0.13.0 --extra-index-url https://download.pytorch.org/whl/cu116
pip install gymnasium[all]==0.29.1
```

若网络故障，可以添加其他的安装原进行安装
```conda
pip install gymnasium[all]==0.29.1 -i https://pypi.tuna.tsinghua.edu.cn/simple 
```

## Train
```conda
cd dqn
python dqn.py
```