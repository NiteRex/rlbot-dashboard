# RLBot 1v1 training dashboard

Live progress of a Rocket League 1v1 bot learning by self-play (PPO on RocketSim via rlgym-sim + rlgym-ppo).

The page (`index.html`) reads `data.json`, which the training PC regenerates and pushes every ~5 minutes while
it is on. This repo is a single force-pushed snapshot; there is no history to browse.

Tabs: **Overview** (headline numbers, goals, randomness, contacts, speed) · **How it plays** (ball/car
speed, air time, heights, boost) · **Learning health** (entropy, reward, value loss, KL, clip fraction) ·
**Rewards & history** (current reward weights, curriculum, every reward change and why) · **System**
(setup, PPO settings, checkpoints, watchdog log).
