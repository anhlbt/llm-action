


# 场景

文生图，还能实现图生文、图文联合生成、无条件图文生成、图文改写


文生图(Generation) （文本->图像）
视觉问答(Visual Question Answering) (图像+文本 ->文本)
多模态分类 (Multimodal classification) (图像+文本 -> 标签)
优化理解/生成(Better understanding/generation) (图像+文本 ->标签/文本)

零样本图像描述生成


通用视觉问答

文本导向的视觉问答

细粒度视觉定位



CLIP

BLIP


BLIP2 

LLaVA 

miniGPT4

InstructBLIP




## 任务

例如给定一张图片，可以完成以下任务：

一、VQA（Visual Question Answering）视觉问答输入：一张图片、一个自然语言描述的问题输出：答案（单词或短语）

二、Image Caption 图像字幕输入：一张图片输出：图片的自然语言描述（一个句子）

三、Referring Expression Comprehension 指代表达输入：一张图片、一个自然语言描述的句子输出：判断句子描述的内容（正确或错误）

四、Visual Dialogue 视觉对话输入：一张图片输出：两个角色进行多次交互、对话

五、VCR (Visual Commonsense Reasoning) 视觉常识推理输入：1个问题，4个备选答案，4个理由输出：正确答案，和理由


六、NLVR(Natural Language for Visual Reasoning)自然语言视觉推理

输入：2张图片，一个分布

输出：true或false



七、Visual Entailment 视觉蕴含

输入：图像、文本

输出：3种label的概率。（entailment、neutral、contradiction）蕴含、中性、矛盾




八、Image-Text Retrieval 图文检索

有3种方式。

1）以图搜文。输入图片，输出文本

2）以文搜图。输入文本，输出图片

3）以图搜图，输入图片，输出图片
