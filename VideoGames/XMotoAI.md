
# Xmoto AI

Reinforcement learning has been successful in the fields of games such as Go, DOTA, Starcraft that doesn't involve physics.  
I believe Xmoto could be an interesting environment with physics kinda similar to reality in 2D.

[Few experiments have been done already](https://github.com/louis030195/xmoto-gym) but to do a serious "AI wrapper" it implies making getting observations and sending actions accessible synchronously through a Python API ideally.

Work to be done on Xmoto game:

1. Make most useful C++ code callable by Python such as:
	- Start the game at a specific level
	- [Sending actions](https://github.com/xmoto/xmoto/blob/master/src/states/StatePlaying.cpp)
	- Getting observations (moto data, level data)
	- [Optionally] Ghosts for imitation learning

2. Update the xmoto-gym wrapper
3. Make a template to train AI on xmoto
4. Examples
