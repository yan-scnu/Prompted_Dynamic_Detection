<img src="Theme.jpg" alt="Theme" style="zoom: 25%;" />

# Prompt Engineering-assisted Malware Dynamic Analysis Using GPT-4

After our paper is accepted, we will make the code available on GitHub. In the meantime, researchers who need the code can contact us via email at 1355674762@qq.com.

## Abstract
Dynamic analysis methods effectively identify shelled, wrapped, or obfuscated malware, thereby preventing them from invading computers. As a significant representation of dynamic malware behavior, the API (Application Programming Interface) sequence, comprised of consecutive API calls, has progressively become the dominant feature of dynamic analysis methods. Though there have been numerous deep learning models for malware detection based on API sequences, the quality of API call representations produced by those models is limited. These models cannot generate representations for unknown API calls, which weakens both the detection performance and the generalization. Further, the concept drift phenomenon of API calls is prominent. To tackle these issues, we introduce a prompt engineering-assisted malware dynamic analysis using GPT-4. In this method, GPT-4 is employed to create explanatory text for each API call within the API sequence. Afterward, the pre-trained language model BERT is used to obtain the representation of the text, from which we derive the representation of the API sequence. Theoretically, this proposed method is capable of generating representations for all API calls, excluding the necessity for dataset training during the generation process. Utilizing the representation, a CNN-based detection model is designed to extract the feature. We adopt five benchmark datasets to validate the performance of the proposed model. The experimental results reveal that the proposed detection algorithm performs better than the state-of-the-art method (TextCNN). Specifically, in cross-database experiments and few-shot learning experiments, the proposed model achieves excellent detection performance and almost a 100% recall rate for malware, verifying its superior generalization performance.

## Code

Since our work hasn't been published, we only share the key processes and models, and we do not share the training weights or content generated by GPT. Researchers in need of the code for this article can contact me via email (1355674762@qq.com). In the body of the email, please state your purpose. Unless there are special circumstances, I will reply within 3 days.

## Citation

```
@article{yan2023prompt,
  title={Prompt Engineering-assisted Malware Dynamic Analysis Using GPT-4},
  author={Yan, Pei and Tan, Shunquan and Wang, Miaohui and Huang, Jiwu},
  journal={arXiv preprint arXiv:2312.08317},
  year={2023}
}
```
