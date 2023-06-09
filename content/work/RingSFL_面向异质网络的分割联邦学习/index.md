---
title: RingSFL：面向异质网络的分割联邦学习
date: 2023-05-20
content_id: 1
tag:
  - work
---

<div style="padding-top:1vh;">Federated Learning (FL)是一种能够在保护客户数据隐私的同时进行协同训练的技术，它已经引起了越来越多的关注。然而，传统FL无法适应客户异质性，会存在拖延者而导致培训效率下降，而且仍然容易泄露隐私。为了解决这些问题，本文提出了一个名为RingSFL的新型分布式学习方案，该方案将FL与模型分割机制相结合，以适应客户异质性并保持数据隐私性。</div>

<!--more-->

在RingSFL中，所有客户端形成一个环形拓扑结构。对于每个客户端，模型不是在本地训练，而是通过预定义的方向在整个环中进行分割和训练。通过适当设置异质客户的传播长度，可以减轻拖延者效应，显着提高系统的训练效率。此外，由于本地模型是混合的，窃听者很难能够获取完整的模型来恢复原始数据，从而提高了数据隐私性。在独立同分布（IID）和非IID数据集上的实验结果表明，RingSFL可以比基准方法实现更好的收敛性能，同时有效地防止窃听者恢复训练数据。