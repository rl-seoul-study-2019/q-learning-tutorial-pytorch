# Q-Table learning codes for FrozenLake game

This is Q-Table learning codes for FrozenLake game.

<br>

This is from 2nd week lecture  studying on RL Seoul Study.

<br>

-----------------------------------

<strong>Environment</strong>

- Anaconda3
- python3.6
- openai gym

<br>

----------------------------------------------------

<strong>Deterministic FrozenLake-v3</strong>

```python
env = gym.make('FrozenLake-v3')
```

<em>Play Game</em>

- 01_frozenlake_deterministic.py

<em>Q-Table and Success rate</em>

- 02_q-table_learning_det_v0.py
- 03_q-table_learning_det_v1.py
- 04_q-table_learning_det_v2.py

<br>

-----------------------------------------

<strong>Stochastic FrozenLake-v0</strong>

```python
env = gym.make('FrozenLake-v0')
```

<em>Play Game</em>

- 05_play_frozenlake.py
- 08_q-table_frozenlake.py

<em>Q-Table and Success rate</em>

- 06_q-table-nondeterministic_v0.py
- 07_q-table_nondeterministic_v1.py
