<p aligin="center">
  <img src="![image](https://github.com/mjkim001130/RL/assets/79756320/1db659da-a9bd-490e-8ac5-0ba0e8ee342f)">
</p>

## Documents

---

```
python = 3.11.5
gymnasium = 0.29.1
pytorch = 2.1.0
```

## Run code

---

### Algorithm:

```
python main.py --Deul False --Double False # DQN on CartPole-v1
```
```
python main.py --Deul False  # Double DQN on CartPole-v1
```
```
python main.py  --Double False # Duel DQN on CartPole-v1
```

### Change Env:

```
"--EnvIdex 0" for "CartPole-v1"
"--EnvIdex 1" for "LunarLander-v2"
```
if you want to eun code in EnvIdex 1:

```
python main.py --Double False --EnvIdex 1 # Duel DQN on LunarLander-v2
```

### Lendering with trained model:

```
python main.py --EnvIdex 0 --render True --Loadmodel True --ModelIdex 300 
```

### Training Curve:

```
python main.py --write True # record
```
```
tensorboard --logdir runs # visualization
```
