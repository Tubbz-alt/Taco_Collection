# README

使用LJSpeech 50k的checkpoint作为原始模型，性别为女；

使用VCTK中的p227中的50句语料作为训练集，性别为男；

这次实验的目的主要是想看一下10句用于finetuning是否可行，实验结果表明：10句完全可以进行微调训练，实验效果还不错，但是音质会稍微差一点，微调2000步就有结果了。

保存的checkepoint有54k/55k/56k/60k。55k和60k的效果几乎是一样的。