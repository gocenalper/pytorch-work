# pytorch-work

My own works in PyTorch. These notebooks were written in Google Colab.

| Notebook | Topic |
| --- | --- |
| `torch_work_1.ipynb` | Tensor basics: shape, dtype, slicing, `max`, transpose, NumPy interop and shared memory |
| `torch_work_2.ipynb` | Device selection (CUDA / MPS / CPU) and moving tensors to a device |
| `torch_work_3(autograd).ipynb` | Autograd: `requires_grad`, `backward()`, gradient accumulation, `no_grad`, `detach`, in-place pitfalls |
| `torch_work_4(dataloaders).ipynb` | DataLoaders (work in progress) |
| `linear_regression.ipynb` | Linear regression on California Housing, first by hand with autograd, then with `nn.Linear` and `optim.SGD` |
| `mlp.ipynb` | An MLP regressor on California Housing with `TensorDataset`, `DataLoader`, Adam and an evaluation loop |

Each notebook opens directly in Colab or Jupyter.
