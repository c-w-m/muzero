Name: myMuzeroCartpole
Parameters `train -c examples/myMuzeroCartpole.json --game cartpole --gpu -1`

```shell
/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero37/bin/python /home/cwm/.local/share/JetBrains/Toolbox/apps/PyCharm-C/ch-0/212.5457.59/plugins/python-ce/helpers/pydev/pydevd.py --multiproc --qt-support=auto --client 127.0.0.1 --port 36239 --file /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/Main.py train -c examples/myMuzeroCartpole.json --game cartpole --gpu -1
Connected to pydev debugger (build 212.5457.59)
2021-11-23 16:11:33.205775: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'libcudart.so.11.0'; dlerror: libcudart.so.11.0: cannot open shared object file: No such file or directory
2021-11-23 16:11:33.205987: I tensorflow/stream_executor/cuda/cudart_stub.cc:29] Ignore above cudart dlerror if you do not have a GPU set up on your machine.
2021-11-23 16:11:38.760025: I tensorflow/core/platform/cpu_feature_guard.cc:142] This TensorFlow binary is optimized with oneAPI Deep Neural Network Library (oneDNN) to use the following CPU instructions in performance-critical operations:  AVX2 FMA
To enable them in other operations, rebuild TensorFlow with the appropriate compiler flags.
2021-11-23 16:11:38.761001: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'libcuda.so.1'; dlerror: libcuda.so.1: cannot open shared object file: No such file or directory
2021-11-23 16:11:38.761038: W tensorflow/stream_executor/cuda/cuda_driver.cc:326] failed call to cuInit: UNKNOWN ERROR (303)
2021-11-23 16:11:38.761081: I tensorflow/stream_executor/cuda/cuda_diagnostics.cc:156] kernel driver does not appear to be running on this host (flxsa02): /proc/driver/nvidia/version does not exist
/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero37/lib/python3.7/site-packages/ale_py/roms/utils.py:90: DeprecationWarning: SelectableGroups dict interface is deprecated. Use select.
  for external in metadata.entry_points().get(self.group, []):
Using TensorFlow backend.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Testing: CartPole, Base, Gym, cartpole, 20211123-161139
/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero37/lib/python3.7/site-packages/tensorflow/python/keras/optimizer_v2/optimizer_v2.py:375: UserWarning: The `lr` argument is deprecated, use `learning_rate` instead.
  "The `lr` argument is deprecated, use `learning_rate` instead.")
------ITER 1------
Self Play:   0%|          | 0/20 [00:00<?, ?it/s]2021-11-23 16:11:41.729638: I tensorflow/compiler/mlir/mlir_graph_optimization_pass.cc:176] None of the MLIR Optimization Passes are enabled (registered 2)
2021-11-23 16:11:41.746875: I tensorflow/core/platform/profile_utils/cpu_utils.cc:114] CPU Frequency: 2793685000 Hz
Self Play: 100%|██████████| 20/20 [06:06<00:00, 18.33s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 1 self play iterations
In total 20 episodes have been played amounting to 279 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:20<00:00,  1.93it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:07<00:00, 12.78s/it]
Pitting p2: 100%|██████████| 10/10 [02:06<00:00, 12.60s/it]
AVERAGE PLAYER 1 SCORE: 9.6 ; AVERAGE PLAYER 2 SCORE: 9.5
CHAMPION/CONTENDER WINS : 3 / 2 ; DRAWS : 5 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 2------
Self Play: 100%|██████████| 20/20 [04:15<00:00, 12.78s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 2 self play iterations
In total 40 episodes have been played amounting to 477 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.34it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:03<00:00, 12.35s/it]
Pitting p2: 100%|██████████| 10/10 [02:03<00:00, 12.33s/it]
AVERAGE PLAYER 1 SCORE: 9.5 ; AVERAGE PLAYER 2 SCORE: 9.5
CHAMPION/CONTENDER WINS : 3 / 2 ; DRAWS : 5 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 3------
Self Play: 100%|██████████| 20/20 [04:11<00:00, 12.59s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 3 self play iterations
In total 60 episodes have been played amounting to 671 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.30it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:03<00:00, 12.37s/it]
Pitting p2: 100%|██████████| 10/10 [02:02<00:00, 12.26s/it]
AVERAGE PLAYER 1 SCORE: 9.5 ; AVERAGE PLAYER 2 SCORE: 9.4
CHAMPION/CONTENDER WINS : 4 / 2 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 4------
Self Play: 100%|██████████| 20/20 [04:06<00:00, 12.34s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 4 self play iterations
In total 80 episodes have been played amounting to 863 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.29it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:00<00:00, 12.06s/it]
Pitting p2: 100%|██████████| 10/10 [02:01<00:00, 12.10s/it]
AVERAGE PLAYER 1 SCORE: 9.4 ; AVERAGE PLAYER 2 SCORE: 9.4
CHAMPION/CONTENDER WINS : 4 / 4 ; DRAWS : 2 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 5------
Self Play: 100%|██████████| 20/20 [03:52<00:00, 11.62s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1043 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.29it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [01:57<00:00, 11.70s/it]
Pitting p2: 100%|██████████| 10/10 [01:59<00:00, 11.98s/it]
AVERAGE PLAYER 1 SCORE: 9.1 ; AVERAGE PLAYER 2 SCORE: 9.3
CHAMPION/CONTENDER WINS : 2 / 3 ; DRAWS : 5 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 6------
Self Play: 100%|██████████| 20/20 [04:10<00:00, 12.52s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 951 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.94it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:04<00:00, 12.45s/it]
Pitting p2: 100%|██████████| 10/10 [02:03<00:00, 12.37s/it]
AVERAGE PLAYER 1 SCORE: 9.4 ; AVERAGE PLAYER 2 SCORE: 9.6
CHAMPION/CONTENDER WINS : 1 / 2 ; DRAWS : 7 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 7------
Self Play: 100%|██████████| 20/20 [04:11<00:00, 12.58s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 941 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.98it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:04<00:00, 12.43s/it]
Pitting p2: 100%|██████████| 10/10 [01:58<00:00, 11.85s/it]
AVERAGE PLAYER 1 SCORE: 9.5 ; AVERAGE PLAYER 2 SCORE: 9.2
CHAMPION/CONTENDER WINS : 4 / 3 ; DRAWS : 3 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 8------
Self Play: 100%|██████████| 20/20 [03:58<00:00, 11.90s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 928 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.17it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [03:01<00:00, 18.10s/it]
Pitting p2: 100%|██████████| 10/10 [02:19<00:00, 14.00s/it]
AVERAGE PLAYER 1 SCORE: 9.8 ; AVERAGE PLAYER 2 SCORE: 9.4
CHAMPION/CONTENDER WINS : 6 / 3 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 9------
Self Play: 100%|██████████| 20/20 [04:14<00:00, 12.73s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 923 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.95it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [01:59<00:00, 11.94s/it]
Pitting p2: 100%|██████████| 10/10 [02:06<00:00, 12.64s/it]
AVERAGE PLAYER 1 SCORE: 9.2 ; AVERAGE PLAYER 2 SCORE: 9.8
CHAMPION/CONTENDER WINS : 1 / 5 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 10------
Self Play: 100%|██████████| 20/20 [04:07<00:00, 12.36s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 927 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.92it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:07<00:00, 12.78s/it]
Pitting p2: 100%|██████████| 10/10 [01:57<00:00, 11.77s/it]
AVERAGE PLAYER 1 SCORE: 9.6 ; AVERAGE PLAYER 2 SCORE: 9.1
CHAMPION/CONTENDER WINS : 5 / 1 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 11------
Self Play: 100%|██████████| 20/20 [03:57<00:00, 11.86s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 923 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.20it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:05<00:00, 12.56s/it]
Pitting p2: 100%|██████████| 10/10 [02:02<00:00, 12.29s/it]
AVERAGE PLAYER 1 SCORE: 9.7 ; AVERAGE PLAYER 2 SCORE: 9.3
CHAMPION/CONTENDER WINS : 4 / 1 ; DRAWS : 5 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 12------
Self Play: 100%|██████████| 20/20 [04:01<00:00, 12.10s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 919 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.13it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:01<00:00, 12.16s/it]
Pitting p2: 100%|██████████| 10/10 [02:01<00:00, 12.14s/it]
AVERAGE PLAYER 1 SCORE: 9.4 ; AVERAGE PLAYER 2 SCORE: 9.4
CHAMPION/CONTENDER WINS : 4 / 4 ; DRAWS : 2 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 13------
Self Play: 100%|██████████| 20/20 [04:09<00:00, 12.48s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 930 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.01it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [01:55<00:00, 11.52s/it]
Pitting p2: 100%|██████████| 10/10 [02:07<00:00, 12.78s/it]
AVERAGE PLAYER 1 SCORE: 8.9 ; AVERAGE PLAYER 2 SCORE: 9.8
CHAMPION/CONTENDER WINS : 0 / 7 ; DRAWS : 3 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 14------
Self Play: 100%|██████████| 20/20 [04:02<00:00, 12.12s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 930 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.20it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:02<00:00, 12.30s/it]
Pitting p2: 100%|██████████| 10/10 [01:59<00:00, 11.90s/it]
AVERAGE PLAYER 1 SCORE: 9.5 ; AVERAGE PLAYER 2 SCORE: 9.2
CHAMPION/CONTENDER WINS : 5 / 2 ; DRAWS : 3 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 15------
Self Play: 100%|██████████| 20/20 [03:59<00:00, 11.98s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 931 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.15it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:03<00:00, 12.38s/it]
Pitting p2: 100%|██████████| 10/10 [02:00<00:00, 12.04s/it]
AVERAGE PLAYER 1 SCORE: 9.3 ; AVERAGE PLAYER 2 SCORE: 9.1
CHAMPION/CONTENDER WINS : 5 / 3 ; DRAWS : 2 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 16------
Self Play: 100%|██████████| 20/20 [04:19<00:00, 12.96s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 945 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.16it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [01:57<00:00, 11.79s/it]
Pitting p2: 100%|██████████| 10/10 [02:05<00:00, 12.54s/it]
AVERAGE PLAYER 1 SCORE: 9.1 ; AVERAGE PLAYER 2 SCORE: 9.7
CHAMPION/CONTENDER WINS : 1 / 6 ; DRAWS : 3 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 17------
Self Play: 100%|██████████| 20/20 [04:15<00:00, 12.80s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 946 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:06<00:00,  6.10it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:10<00:00, 13.04s/it]
Pitting p2: 100%|██████████| 10/10 [02:08<00:00, 12.89s/it]
AVERAGE PLAYER 1 SCORE: 9.5 ; AVERAGE PLAYER 2 SCORE: 9.1
CHAMPION/CONTENDER WINS : 5 / 4 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 18------
Self Play: 100%|██████████| 20/20 [04:20<00:00, 13.00s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 941 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.97it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:03<00:00, 12.34s/it]
Pitting p2: 100%|██████████| 10/10 [02:05<00:00, 12.59s/it]
AVERAGE PLAYER 1 SCORE: 9.2 ; AVERAGE PLAYER 2 SCORE: 9.3
CHAMPION/CONTENDER WINS : 2 / 2 ; DRAWS : 6 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 19------
Self Play: 100%|██████████| 20/20 [04:15<00:00, 12.75s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 938 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.04it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:12<00:00, 13.22s/it]
Pitting p2: 100%|██████████| 10/10 [02:07<00:00, 12.78s/it]
AVERAGE PLAYER 1 SCORE: 9.5 ; AVERAGE PLAYER 2 SCORE: 9.5
CHAMPION/CONTENDER WINS : 2 / 2 ; DRAWS : 6 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 20------
Self Play: 100%|██████████| 20/20 [04:23<00:00, 13.18s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 945 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:06<00:00,  6.61it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:12<00:00, 13.29s/it]
Pitting p2: 100%|██████████| 10/10 [02:05<00:00, 12.53s/it]
AVERAGE PLAYER 1 SCORE: 9.5 ; AVERAGE PLAYER 2 SCORE: 9.2
CHAMPION/CONTENDER WINS : 4 / 2 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 21------
Self Play: 100%|██████████| 20/20 [04:31<00:00, 13.57s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 944 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.69it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:11<00:00, 13.19s/it]
Pitting p2: 100%|██████████| 10/10 [02:12<00:00, 13.27s/it]
AVERAGE PLAYER 1 SCORE: 9.3 ; AVERAGE PLAYER 2 SCORE: 9.6
CHAMPION/CONTENDER WINS : 1 / 3 ; DRAWS : 6 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 22------
Self Play: 100%|██████████| 20/20 [04:29<00:00, 13.48s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 968 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.18it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:04<00:00, 12.45s/it]
Pitting p2: 100%|██████████| 10/10 [02:05<00:00, 12.52s/it]
AVERAGE PLAYER 1 SCORE: 9.6 ; AVERAGE PLAYER 2 SCORE: 9.3
CHAMPION/CONTENDER WINS : 5 / 2 ; DRAWS : 3 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 23------
Self Play: 100%|██████████| 20/20 [04:18<00:00, 12.93s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 979 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.20it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [01:53<00:00, 11.40s/it]
Pitting p2: 100%|██████████| 10/10 [02:06<00:00, 12.69s/it]
AVERAGE PLAYER 1 SCORE: 8.8 ; AVERAGE PLAYER 2 SCORE: 9.8
CHAMPION/CONTENDER WINS : 0 / 6 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 24------
Self Play: 100%|██████████| 20/20 [04:20<00:00, 13.04s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 996 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.18it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:02<00:00, 12.25s/it]
Pitting p2: 100%|██████████| 10/10 [02:08<00:00, 12.88s/it]
AVERAGE PLAYER 1 SCORE: 9.0 ; AVERAGE PLAYER 2 SCORE: 9.0
CHAMPION/CONTENDER WINS : 2 / 2 ; DRAWS : 6 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 25------
Self Play: 100%|██████████| 20/20 [04:25<00:00, 13.25s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 996 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.22it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:04<00:00, 12.47s/it]
Pitting p2: 100%|██████████| 10/10 [02:04<00:00, 12.43s/it]
AVERAGE PLAYER 1 SCORE: 9.6 ; AVERAGE PLAYER 2 SCORE: 9.6
CHAMPION/CONTENDER WINS : 1 / 1 ; DRAWS : 8 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 26------
Self Play: 100%|██████████| 20/20 [04:21<00:00, 13.06s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1002 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.19it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:01<00:00, 12.14s/it]
Pitting p2: 100%|██████████| 10/10 [02:04<00:00, 12.47s/it]
AVERAGE PLAYER 1 SCORE: 9.4 ; AVERAGE PLAYER 2 SCORE: 9.7
CHAMPION/CONTENDER WINS : 2 / 4 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 27------
Self Play: 100%|██████████| 20/20 [04:36<00:00, 13.82s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1004 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.21it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:01<00:00, 12.19s/it]
Pitting p2: 100%|██████████| 10/10 [02:00<00:00, 12.05s/it]
AVERAGE PLAYER 1 SCORE: 9.4 ; AVERAGE PLAYER 2 SCORE: 9.3
CHAMPION/CONTENDER WINS : 3 / 3 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 28------
Self Play: 100%|██████████| 20/20 [04:02<00:00, 12.12s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 993 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.14it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:00<00:00, 12.06s/it]
Pitting p2: 100%|██████████| 10/10 [02:00<00:00, 12.08s/it]
AVERAGE PLAYER 1 SCORE: 9.3 ; AVERAGE PLAYER 2 SCORE: 9.3
CHAMPION/CONTENDER WINS : 4 / 3 ; DRAWS : 3 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 29------
Self Play: 100%|██████████| 20/20 [04:55<00:00, 14.76s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1020 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.22it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:04<00:00, 12.45s/it]
Pitting p2: 100%|██████████| 10/10 [02:03<00:00, 12.33s/it]
AVERAGE PLAYER 1 SCORE: 9.6 ; AVERAGE PLAYER 2 SCORE: 9.5
CHAMPION/CONTENDER WINS : 5 / 4 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 30------
Self Play: 100%|██████████| 20/20 [04:39<00:00, 13.98s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1044 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.14it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [01:59<00:00, 11.95s/it]
Pitting p2: 100%|██████████| 10/10 [02:13<00:00, 13.36s/it]
AVERAGE PLAYER 1 SCORE: 9.2 ; AVERAGE PLAYER 2 SCORE: 10.3
CHAMPION/CONTENDER WINS : 0 / 6 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 31------
Self Play: 100%|██████████| 20/20 [04:35<00:00, 13.80s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1055 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.25it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:03<00:00, 12.36s/it]
Pitting p2: 100%|██████████| 10/10 [01:54<00:00, 11.43s/it]
AVERAGE PLAYER 1 SCORE: 9.5 ; AVERAGE PLAYER 2 SCORE: 8.8
CHAMPION/CONTENDER WINS : 6 / 0 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 32------
Self Play: 100%|██████████| 20/20 [04:57<00:00, 14.86s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1069 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.19it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [01:58<00:00, 11.89s/it]
Pitting p2: 100%|██████████| 10/10 [02:00<00:00, 12.00s/it]
AVERAGE PLAYER 1 SCORE: 9.2 ; AVERAGE PLAYER 2 SCORE: 9.3
CHAMPION/CONTENDER WINS : 3 / 3 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 33------
Self Play: 100%|██████████| 20/20 [04:51<00:00, 14.57s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1107 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.22it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:03<00:00, 12.37s/it]
Pitting p2: 100%|██████████| 10/10 [01:59<00:00, 11.92s/it]
AVERAGE PLAYER 1 SCORE: 9.4 ; AVERAGE PLAYER 2 SCORE: 9.2
CHAMPION/CONTENDER WINS : 3 / 2 ; DRAWS : 5 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 34------
Self Play: 100%|██████████| 20/20 [04:52<00:00, 14.62s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1104 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.23it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [01:59<00:00, 12.00s/it]
Pitting p2: 100%|██████████| 10/10 [02:02<00:00, 12.22s/it]
AVERAGE PLAYER 1 SCORE: 9.2 ; AVERAGE PLAYER 2 SCORE: 9.4
CHAMPION/CONTENDER WINS : 3 / 3 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 35------
Self Play: 100%|██████████| 20/20 [04:38<00:00, 13.92s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1099 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.18it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [01:58<00:00, 11.83s/it]
Pitting p2: 100%|██████████| 10/10 [02:03<00:00, 12.33s/it]
AVERAGE PLAYER 1 SCORE: 9.1 ; AVERAGE PLAYER 2 SCORE: 9.5
CHAMPION/CONTENDER WINS : 3 / 4 ; DRAWS : 3 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 36------
Self Play: 100%|██████████| 20/20 [04:57<00:00, 14.87s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1113 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.25it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:09<00:00, 12.95s/it]
Pitting p2: 100%|██████████| 10/10 [02:07<00:00, 12.77s/it]
AVERAGE PLAYER 1 SCORE: 10.0 ; AVERAGE PLAYER 2 SCORE: 9.2
CHAMPION/CONTENDER WINS : 2 / 3 ; DRAWS : 5 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 37------
Self Play: 100%|██████████| 20/20 [04:59<00:00, 14.99s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1118 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.22it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:11<00:00, 13.19s/it]
Pitting p2: 100%|██████████| 10/10 [02:15<00:00, 13.53s/it]
AVERAGE PLAYER 1 SCORE: 10.1 ; AVERAGE PLAYER 2 SCORE: 10.4
CHAMPION/CONTENDER WINS : 1 / 5 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 38------
Self Play: 100%|██████████| 20/20 [04:32<00:00, 13.63s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1101 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.25it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:53<00:00, 17.38s/it]
Pitting p2: 100%|██████████| 10/10 [02:09<00:00, 12.97s/it]
AVERAGE PLAYER 1 SCORE: 13.1 ; AVERAGE PLAYER 2 SCORE: 9.6
CHAMPION/CONTENDER WINS : 7 / 1 ; DRAWS : 2 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 39------
Self Play: 100%|██████████| 20/20 [05:46<00:00, 17.31s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1131 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.17it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:07<00:00, 12.71s/it]
Pitting p2: 100%|██████████| 10/10 [02:22<00:00, 14.25s/it]
AVERAGE PLAYER 1 SCORE: 9.8 ; AVERAGE PLAYER 2 SCORE: 11.0
CHAMPION/CONTENDER WINS : 4 / 5 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 40------
Self Play: 100%|██████████| 20/20 [04:36<00:00, 13.84s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1134 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.09it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:07<00:00, 12.73s/it]
Pitting p2: 100%|██████████| 10/10 [02:03<00:00, 12.30s/it]
AVERAGE PLAYER 1 SCORE: 9.5 ; AVERAGE PLAYER 2 SCORE: 9.4
CHAMPION/CONTENDER WINS : 5 / 1 ; DRAWS : 4 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 41------
Self Play: 100%|██████████| 20/20 [04:30<00:00, 13.53s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1107 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.87it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:10<00:00, 13.03s/it]
Pitting p2: 100%|██████████| 10/10 [02:02<00:00, 12.27s/it]
AVERAGE PLAYER 1 SCORE: 9.6 ; AVERAGE PLAYER 2 SCORE: 9.4
CHAMPION/CONTENDER WINS : 4 / 5 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 42------
Self Play: 100%|██████████| 20/20 [05:06<00:00, 15.31s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1112 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.33it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [03:14<00:00, 19.49s/it]
Pitting p2: 100%|██████████| 10/10 [02:04<00:00, 12.43s/it]
AVERAGE PLAYER 1 SCORE: 15.1 ; AVERAGE PLAYER 2 SCORE: 9.6
CHAMPION/CONTENDER WINS : 6 / 3 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 43------
Self Play: 100%|██████████| 20/20 [05:36<00:00, 16.84s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1140 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.19it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [03:39<00:00, 21.96s/it]
Pitting p2: 100%|██████████| 10/10 [03:07<00:00, 18.79s/it]
AVERAGE PLAYER 1 SCORE: 16.2 ; AVERAGE PLAYER 2 SCORE: 14.3
CHAMPION/CONTENDER WINS : 5 / 5 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 44------
Self Play: 100%|██████████| 20/20 [05:03<00:00, 15.17s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1119 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.21it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [03:56<00:00, 23.61s/it]
Pitting p2: 100%|██████████| 10/10 [02:26<00:00, 14.65s/it]
AVERAGE PLAYER 1 SCORE: 18.2 ; AVERAGE PLAYER 2 SCORE: 11.3
CHAMPION/CONTENDER WINS : 6 / 4 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 45------
Self Play: 100%|██████████| 20/20 [06:29<00:00, 19.45s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1205 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.20it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:32<00:00, 15.23s/it]
Pitting p2: 100%|██████████| 10/10 [04:17<00:00, 25.79s/it]
AVERAGE PLAYER 1 SCORE: 11.3 ; AVERAGE PLAYER 2 SCORE: 18.9
CHAMPION/CONTENDER WINS : 4 / 5 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 46------
Self Play: 100%|██████████| 20/20 [05:34<00:00, 16.73s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1241 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.29it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [04:55<00:00, 29.58s/it]
Pitting p2: 100%|██████████| 10/10 [02:33<00:00, 15.34s/it]
AVERAGE PLAYER 1 SCORE: 22.0 ; AVERAGE PLAYER 2 SCORE: 11.1
CHAMPION/CONTENDER WINS : 8 / 1 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 47------
Self Play: 100%|██████████| 20/20 [08:29<00:00, 25.48s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1387 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.30it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:37<00:00, 15.79s/it]
Pitting p2: 100%|██████████| 10/10 [03:28<00:00, 20.80s/it]
AVERAGE PLAYER 1 SCORE: 11.9 ; AVERAGE PLAYER 2 SCORE: 15.4
CHAMPION/CONTENDER WINS : 2 / 7 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 48------
Self Play: 100%|██████████| 20/20 [05:28<00:00, 16.43s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1374 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:06<00:00,  6.63it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [05:06<00:00, 30.66s/it]
Pitting p2: 100%|██████████| 10/10 [03:23<00:00, 20.31s/it]
AVERAGE PLAYER 1 SCORE: 19.3 ; AVERAGE PLAYER 2 SCORE: 13.6
CHAMPION/CONTENDER WINS : 7 / 2 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 49------
Self Play: 100%|██████████| 20/20 [09:05<00:00, 27.28s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1510 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.34it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [03:54<00:00, 23.45s/it]
Pitting p2: 100%|██████████| 10/10 [03:51<00:00, 23.14s/it]
AVERAGE PLAYER 1 SCORE: 18.2 ; AVERAGE PLAYER 2 SCORE: 18.0
CHAMPION/CONTENDER WINS : 4 / 6 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 50------
Self Play: 100%|██████████| 20/20 [07:37<00:00, 22.88s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1565 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.36it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [02:38<00:00, 15.82s/it]
Pitting p2: 100%|██████████| 10/10 [03:39<00:00, 21.95s/it]
AVERAGE PLAYER 1 SCORE: 12.3 ; AVERAGE PLAYER 2 SCORE: 16.7
CHAMPION/CONTENDER WINS : 4 / 6 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 51------
Self Play: 100%|██████████| 20/20 [06:40<00:00, 20.01s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1630 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.22it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [03:29<00:00, 20.95s/it]
Pitting p2: 100%|██████████| 10/10 [02:51<00:00, 17.15s/it]
AVERAGE PLAYER 1 SCORE: 14.9 ; AVERAGE PLAYER 2 SCORE: 12.7
CHAMPION/CONTENDER WINS : 6 / 4 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 52------
Self Play: 100%|██████████| 20/20 [08:35<00:00, 25.79s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1624 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:06<00:00,  6.50it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [06:58<00:00, 41.85s/it]
Pitting p2: 100%|██████████| 10/10 [04:10<00:00, 25.02s/it]
AVERAGE PLAYER 1 SCORE: 30.2 ; AVERAGE PLAYER 2 SCORE: 18.3
CHAMPION/CONTENDER WINS : 5 / 4 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 53------
Self Play: 100%|██████████| 20/20 [12:44<00:00, 38.21s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1990 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.41it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [04:21<00:00, 26.19s/it]
Pitting p2: 100%|██████████| 10/10 [07:17<00:00, 43.71s/it]
AVERAGE PLAYER 1 SCORE: 20.3 ; AVERAGE PLAYER 2 SCORE: 33.8
CHAMPION/CONTENDER WINS : 2 / 8 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 54------
Self Play: 100%|██████████| 20/20 [07:50<00:00, 23.53s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 1985 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.37it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [11:09<00:00, 66.93s/it]
Pitting p2: 100%|██████████| 10/10 [04:43<00:00, 28.39s/it]
AVERAGE PLAYER 1 SCORE: 52.0 ; AVERAGE PLAYER 2 SCORE: 22.0
CHAMPION/CONTENDER WINS : 10 / 0 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 55------
Self Play: 100%|██████████| 20/20 [21:13<00:00, 63.68s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 2618 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.40it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [09:17<00:00, 55.76s/it]
Pitting p2: 100%|██████████| 10/10 [11:38<00:00, 69.86s/it]
AVERAGE PLAYER 1 SCORE: 43.2 ; AVERAGE PLAYER 2 SCORE: 54.1
CHAMPION/CONTENDER WINS : 1 / 9 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 56------
Self Play: 100%|██████████| 20/20 [18:14<00:00, 54.73s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 3165 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.39it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [06:48<00:00, 40.88s/it]
Pitting p2: 100%|██████████| 10/10 [09:15<00:00, 55.59s/it]
AVERAGE PLAYER 1 SCORE: 31.6 ; AVERAGE PLAYER 2 SCORE: 43.1
CHAMPION/CONTENDER WINS : 1 / 8 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 57------
Self Play: 100%|██████████| 20/20 [16:55<00:00, 50.77s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 3576 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.44it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [07:22<00:00, 44.28s/it]
Pitting p2: 100%|██████████| 10/10 [07:35<00:00, 45.54s/it]
AVERAGE PLAYER 1 SCORE: 34.3 ; AVERAGE PLAYER 2 SCORE: 35.3
CHAMPION/CONTENDER WINS : 2 / 8 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 58------
Self Play: 100%|██████████| 20/20 [10:54<00:00, 32.75s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 3494 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.45it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [06:30<00:00, 39.01s/it]
Pitting p2: 100%|██████████| 10/10 [07:06<00:00, 42.68s/it]
AVERAGE PLAYER 1 SCORE: 30.2 ; AVERAGE PLAYER 2 SCORE: 33.1
CHAMPION/CONTENDER WINS : 2 / 7 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 59------
Self Play: 100%|██████████| 20/20 [13:27<00:00, 40.39s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 3754 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.43it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [13:47<00:00, 82.70s/it]
Pitting p2: 100%|██████████| 10/10 [06:17<00:00, 37.72s/it]
AVERAGE PLAYER 1 SCORE: 63.9 ; AVERAGE PLAYER 2 SCORE: 29.2
CHAMPION/CONTENDER WINS : 10 / 0 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 60------
Self Play: 100%|██████████| 20/20 [21:36<00:00, 64.81s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 3768 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.27it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [13:38<00:00, 81.88s/it]
Pitting p2: 100%|██████████| 10/10 [13:27<00:00, 80.77s/it]
AVERAGE PLAYER 1 SCORE: 63.2 ; AVERAGE PLAYER 2 SCORE: 62.4
CHAMPION/CONTENDER WINS : 3 / 5 ; DRAWS : 2 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 61------
Self Play: 100%|██████████| 20/20 [24:30<00:00, 73.54s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 4053 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.42it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [11:08<00:00, 66.87s/it]
Pitting p2: 100%|██████████| 10/10 [14:46<00:00, 88.68s/it]
AVERAGE PLAYER 1 SCORE: 51.1 ; AVERAGE PLAYER 2 SCORE: 64.1
CHAMPION/CONTENDER WINS : 3 / 7 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 62------
Self Play: 100%|██████████| 20/20 [27:33<00:00, 82.68s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 4477 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.88it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [10:53<00:00, 65.37s/it]
Pitting p2: 100%|██████████| 10/10 [14:40<00:00, 88.04s/it]
AVERAGE PLAYER 1 SCORE: 42.6 ; AVERAGE PLAYER 2 SCORE: 65.4
CHAMPION/CONTENDER WINS : 0 / 9 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 63------
Self Play: 100%|██████████| 20/20 [16:39<00:00, 49.95s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 4735 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.44it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [09:09<00:00, 54.97s/it]
Pitting p2: 100%|██████████| 10/10 [09:39<00:00, 57.98s/it]
AVERAGE PLAYER 1 SCORE: 42.1 ; AVERAGE PLAYER 2 SCORE: 42.2
CHAMPION/CONTENDER WINS : 4 / 5 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 64------
Self Play: 100%|██████████| 20/20 [15:22<00:00, 46.10s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 4738 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.74it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [12:35<00:00, 75.56s/it]
Pitting p2: 100%|██████████| 10/10 [10:18<00:00, 61.88s/it]
AVERAGE PLAYER 1 SCORE: 50.4 ; AVERAGE PLAYER 2 SCORE: 42.0
CHAMPION/CONTENDER WINS : 7 / 1 ; DRAWS : 2 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 65------
Self Play: 100%|██████████| 20/20 [19:21<00:00, 58.09s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 4521 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.74it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [16:38<00:00, 99.88s/it]
Pitting p2: 100%|██████████| 10/10 [11:50<00:00, 71.00s/it]
AVERAGE PLAYER 1 SCORE: 67.6 ; AVERAGE PLAYER 2 SCORE: 49.1
CHAMPION/CONTENDER WINS : 8 / 1 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 66------
Self Play: 100%|██████████| 20/20 [29:35<00:00, 88.78s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 4616 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:06<00:00,  6.19it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [14:16<00:00, 85.66s/it]
Pitting p2: 100%|██████████| 10/10 [16:51<00:00, 101.15s/it]
AVERAGE PLAYER 1 SCORE: 58.9 ; AVERAGE PLAYER 2 SCORE: 70.1
CHAMPION/CONTENDER WINS : 1 / 8 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 67------
Self Play: 100%|██████████| 20/20 [25:20<00:00, 76.01s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 4459 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.69it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [12:10<00:00, 73.05s/it]
Pitting p2: 100%|██████████| 10/10 [14:21<00:00, 86.17s/it]
AVERAGE PLAYER 1 SCORE: 50.6 ; AVERAGE PLAYER 2 SCORE: 60.7
CHAMPION/CONTENDER WINS : 3 / 7 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 68------
Self Play: 100%|██████████| 20/20 [25:40<00:00, 77.02s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 4754 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.78it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [07:24<00:00, 44.45s/it]
Pitting p2: 100%|██████████| 10/10 [11:17<00:00, 67.76s/it]
AVERAGE PLAYER 1 SCORE: 30.9 ; AVERAGE PLAYER 2 SCORE: 46.8
CHAMPION/CONTENDER WINS : 2 / 8 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 69------
Self Play: 100%|██████████| 20/20 [18:23<00:00, 55.15s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 4891 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  6.72it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [17:38<00:00, 105.87s/it]
Pitting p2: 100%|██████████| 10/10 [09:21<00:00, 56.11s/it]
AVERAGE PLAYER 1 SCORE: 72.8 ; AVERAGE PLAYER 2 SCORE: 38.9
CHAMPION/CONTENDER WINS : 7 / 2 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 70------
Self Play: 100%|██████████| 20/20 [37:40<00:00, 113.03s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 5679 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.07it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [16:55<00:00, 101.51s/it]
Pitting p2: 100%|██████████| 10/10 [16:39<00:00, 99.94s/it] 
AVERAGE PLAYER 1 SCORE: 73.2 ; AVERAGE PLAYER 2 SCORE: 72.1
CHAMPION/CONTENDER WINS : 6 / 4 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 71------
Self Play: 100%|██████████| 20/20 [30:42<00:00, 92.11s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 5776 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.07it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [16:08<00:00, 96.84s/it] 
Pitting p2: 100%|██████████| 10/10 [14:17<00:00, 85.72s/it] 
AVERAGE PLAYER 1 SCORE: 70.2 ; AVERAGE PLAYER 2 SCORE: 62.1
CHAMPION/CONTENDER WINS : 5 / 5 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 72------
Self Play: 100%|██████████| 20/20 [28:58<00:00, 86.92s/it] 
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 5980 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.12it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [12:49<00:00, 76.91s/it]
Pitting p2: 100%|██████████| 10/10 [14:26<00:00, 86.67s/it]
AVERAGE PLAYER 1 SCORE: 55.7 ; AVERAGE PLAYER 2 SCORE: 62.7
CHAMPION/CONTENDER WINS : 3 / 7 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 73------
Self Play: 100%|██████████| 20/20 [17:19<00:00, 52.00s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 5648 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:06<00:00,  6.52it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [22:22<00:00, 134.24s/it]
Pitting p2: 100%|██████████| 10/10 [16:29<00:00, 98.93s/it] 
AVERAGE PLAYER 1 SCORE: 90.9 ; AVERAGE PLAYER 2 SCORE: 67.6
CHAMPION/CONTENDER WINS : 9 / 1 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 74------
Self Play: 100%|██████████| 20/20 [35:22<00:00, 106.14s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 6386 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:06<00:00,  6.66it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [18:09<00:00, 108.90s/it]
Pitting p2: 100%|██████████| 10/10 [14:03<00:00, 84.32s/it]
AVERAGE PLAYER 1 SCORE: 80.6 ; AVERAGE PLAYER 2 SCORE: 64.5
CHAMPION/CONTENDER WINS : 5 / 4 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 75------
Self Play: 100%|██████████| 20/20 [35:15<00:00, 105.78s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 6428 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.47it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [15:51<00:00, 95.15s/it]
Pitting p2: 100%|██████████| 10/10 [21:27<00:00, 128.76s/it]
AVERAGE PLAYER 1 SCORE: 72.7 ; AVERAGE PLAYER 2 SCORE: 98.3
CHAMPION/CONTENDER WINS : 4 / 6 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 76------
Self Play: 100%|██████████| 20/20 [31:11<00:00, 93.55s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 6530 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.48it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [15:54<00:00, 95.48s/it] 
Pitting p2: 100%|██████████| 10/10 [16:04<00:00, 96.44s/it] 
AVERAGE PLAYER 1 SCORE: 72.7 ; AVERAGE PLAYER 2 SCORE: 73.5
CHAMPION/CONTENDER WINS : 4 / 5 ; DRAWS : 1 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 77------
Self Play: 100%|██████████| 20/20 [22:50<00:00, 68.54s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 6318 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.42it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [20:30<00:00, 123.05s/it]
Pitting p2: 100%|██████████| 10/10 [13:42<00:00, 82.27s/it]
AVERAGE PLAYER 1 SCORE: 93.9 ; AVERAGE PLAYER 2 SCORE: 62.7
CHAMPION/CONTENDER WINS : 9 / 1 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 78------
Self Play: 100%|██████████| 20/20 [36:33<00:00, 109.68s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 7264 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.48it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [18:58<00:00, 113.90s/it]
Pitting p2: 100%|██████████| 10/10 [22:17<00:00, 133.74s/it]
AVERAGE PLAYER 1 SCORE: 86.8 ; AVERAGE PLAYER 2 SCORE: 102.1
CHAMPION/CONTENDER WINS : 6 / 4 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 79------
Self Play: 100%|██████████| 20/20 [41:05<00:00, 123.27s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 7638 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.38it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [21:07<00:00, 126.78s/it]
Pitting p2: 100%|██████████| 10/10 [21:09<00:00, 126.93s/it]
AVERAGE PLAYER 1 SCORE: 96.4 ; AVERAGE PLAYER 2 SCORE: 96.6
CHAMPION/CONTENDER WINS : 2 / 8 ; DRAWS : 0 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 
------ITER 80------
Self Play: 100%|██████████| 20/20 [31:22<00:00, 94.13s/it]
=== Replay Buffer Statistics ===
Replay buffer filled with data from 5 self play iterations
In total 100 episodes have been played amounting to 7455 data samples
Checkpoint Directory exists! 
Backpropagation: 100%|██████████| 40/40 [00:05<00:00,  7.49it/s]
Pitting players...
Pitting p1: 100%|██████████| 10/10 [19:50<00:00, 119.06s/it]
Pitting p2: 100%|██████████| 10/10 [15:14<00:00, 91.41s/it]
AVERAGE PLAYER 1 SCORE: 90.5 ; AVERAGE PLAYER 2 SCORE: 69.5
CHAMPION/CONTENDER WINS : 7 / 1 ; DRAWS : 2 ; NEW CHAMPION ACCEPTANCE RATIO : 0.0
ACCEPTING NEW MODEL
Checkpoint Directory exists! 
Checkpoint Directory exists! 

Process finished with exit code 0


```