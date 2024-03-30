
Reducing High-Frequency Artifacts for Generative Model Watermarking via Wavelet Transform

High-Frequency Artifacts-Resistant Image Watermarking Applicable to Image Processing Models

Generative Model Watermarking Suppressing High-Frequency Artifacts

Generative Model Watermarking Based on Human Visual System

本项目提供了四篇论文框架最精简的代码，不包含各类测试代码。仅提供了框架代码以供参考。

进入app文件夹，将自己想要运行的代码文件夹test(xxxx)修改为test,运行main即可。
通过修改test中config可以修改实验配置。

例如，在实验中配置损失函数超参数。可以在训练初期设置一个大的水印参数来实现水印嵌入，在降低该参数以实现更佳的视觉效果。

训练的过程中有很多的小技巧需要自己探索，对参数的调整，损失函数的调整可能会直接影响最终的效果。需要根据实际训练的情况不断修改。此外，由于生成任务本身具有一定的难度，在训练的过程中要衡量好水印任务和生成任务。经验之谈，水印任务相对来说比较简单，可以在初期设置较大的水印任务超参数，来快速完成水印任务，再调小改参数。保证水印任务的同时完成生成任务。使用预训练模型训练也是非常重要的手段。有些时候没有预训练模型难以实现任务

注意：想要了解更多该项目框架可以阅读reademeFramework。
