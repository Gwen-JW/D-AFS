# D-AFS

Understanding the environments through interactions has been one of the most important human intellectual activities in mastering unknown systems. Deep reinforcement learning (DRL) has already been known to achieve effective control through human-like exploration and exploitation in many applications. However, the opaque nature of deep neural network (DNN) often hides critical information about feature relevance to control, which is essential for understanding the target systems. In this article, a novel online feature selection framework, namely, the dual-world-based attentive feature selection (D-AFS), is first proposed to identify the contribution of the inputs over the whole control process. Rather than the one world used in most DRL, D-AFS has both the real world and its virtual peer with twisted features. The newly introduced attention-based evaluation (AR) module performs the dynamic mapping from the real world to the virtual world. The existing DRL algorithms, with slight modification, can learn in the dual world. By analyzing the DRL’s response in the two worlds, D-AFS can quantitatively identify respective features’ importance toward control. A set of experiments is performed on four classical control systems in OpenAI Gym. Results show that D-AFS can generate the same or even better feature combinations than the solutions provided by human experts and seven recent feature selection baselines. In all cases, the selected feature representations are closely correlated with the ones used by underlying system dynamic models

You can cite this work if it helps you in any way:

```
@article{wei2022understanding,
  title={Understanding via Exploration: Discovery of Interpretable Features With Deep Reinforcement Learning},
  author={Wei, Jiawen and Qiu, Zhifeng and Wang, Fangyuan and Lin, Wenwei and Gui, Ning and Gui, Weihua},
  journal={IEEE Transactions on Neural Networks and Learning Systems},
  year={2022},
  publisher={IEEE}
}
```
