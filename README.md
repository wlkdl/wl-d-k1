# wl-d-k1
import os
# 消除Windows OpenMP库冲突，防止Jupyter内核重启
os.environ["KMP_DUPLICATE_LIB_OK"] = "TRUE"

import torch
import torch.nn as nn
from torch.utils.data import TensorDataset, DataLoader
import matplotlib.pyplot as plt
import numpy as np

# 验证PyTorch环境
print("PyTorch版本：", torch.__version__)
