```python
import numpy as np
import pandas as pd
import time

N_STATE = 6
ACTION = ["left", "right"]
EPSILON = 0.9 
ALPHA = 0.1 
LAMBDA = 0.9
MAX_EPISODES = 20
FRESH_TIME = 0.3 

def build_q_table(n_states, actions):
  table = pd.DataFrame(

```

