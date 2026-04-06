# `Interest-aware Message-Passing GCN for Recommendation`

> `<One-sentence summary of the paper or project>`

## Authors

**Fan Liu**<sup>1</sup>, **Zhiyong Cheng**<sup>2</sup>\*, **Lei Zhu**<sup>3</sup>, **Zan Gao**<sup>2</sup>, **Liqiang Nie**<sup>1</sup>\*

<sup>1</sup> `Shandong University, China`  
<sup>2</sup> `Shandong Artificial Intelligence Institute, China`  
<sup>3</sup> `Shandong Normal University, China`  
\* Corresponding author

## Links

- **Paper**: [`Paper Link`](https://dl.acm.org/doi/abs/10.1145/3442381.3449986)
- **Code Repository**: [`GitHub`](https://github.com/iLearn-Lab/WWW21-IMPGCN)

---

## Updates

- [02/2021] Initial release
- [02/2021] Release paper / arXiv version
- [02/2021] Release code

---

## Introduction

本项目是论文 **`Interest-aware Message-Passing GCN for Recommendation`** 的官方实现。

请在这里简要说明：

- 论文要解决什么问题
- 方法的核心思想是什么
- 与现有方法相比有什么特点
- 本仓库提供了：
  - 训练代码
  - 训练集
  - 测试集

### Example Description

We present **`<Method Name>`**, a framework for **`<task name>`**.  
Our method addresses **`<problem>`** by introducing **`<core idea>`**.  
This repository provides the official implementation, pretrained checkpoints, and evaluation scripts.

---

## Highlights

- 支持 `<CF-based recommendation Task>`
- 提供 `<training / inference / evaluation>` 脚本
- 提供 `<dataset>`
- 适合用于 `<论文复现 / 后续研究>`

---

## Method / Framework

你可以在这里放方法框架图、模型结构图或整体 pipeline 图。

### Framework Figure

```markdown
![Framework](./assets/framework.png)
```

实际使用时，把上面这行替换成：

```markdown
![Framework](./assets/framework.png)
```

然后在下面补一句说明：

**Figure 1.** Overall framework of `<Method Name>`.

---


## Usage

## Environment Settings
- Tensorflow-gpu version:  1.3.0

## Example to run the codes.

### Training

# gowalla
Run IMP_GCN.py
```
python IMP_GCN.py --dataset gowalla  --regs [1e-4] --embed_size 64 --layer_size [64,64,64,64,64,64] --lr 0.001 --batch_size 2048 --epoch 2000 --groups 3 --Ks [20,10] --gpu_id 0
```

### Example Results

你可以插入结果图：

```markdown
![Result](./assets/result.png)
```

或者放一个简单结果表：

| Setting | Result |
|---|---:|
| Baseline | xx.x |
| Ours | xx.x |

---

## Citation

如果你的项目对应论文，请提供 BibTeX：

```bibtex
@inproceedings{10.1145/3442381.3449986,
author = {Liu, Fan and Cheng, Zhiyong and Zhu, Lei and Gao, Zan and Nie, Liqiang},
title = {Interest-aware Message-Passing GCN for Recommendation},
year = {2021},
publisher = {ACM},
booktitle = {Proceedings of the Web Conference 2021},
pages = {1296–1305}
```

---

## Acknowledgement

- Thanks to our supervisor and collaborators for valuable support.
- Thanks to the open-source community for providing useful baselines and tools.

---

## License

This project is released under the Apache License 2.0.
