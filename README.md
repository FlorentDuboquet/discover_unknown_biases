# Discover the Unknown Biased Attribute of an Image Classifier

<img src="images/teaser.pdf" alt="teaser" style="zoom:200%;" />



### Abstract

Recent works find that AI algorithms learn biases from data. Therefore, it is urgent and vital to identify biases in AI algorithms. However, the previous bias identification pipeline overly relies on human experts to conjecture potential biases (e.g., gender), which may neglect other underlying biases not realized by humans. To help human experts better find the AI algorithms' biases, we study a new problem in this work -- for a classifier that predicts a target attribute of the input image, discover its unknown biased attribute.



To solve this challenging problem, we use a hyperplane in the generative model's latent space to represent an image attribute; thus, the original problem is transformed to optimizing the hyperplane's normal vector and offset. We propose a novel total-variation loss within this framework as the objective function and a new orthogonalization penalty as a constraint. The latter prevents trivial solutions in which the discovered biased attribute is identical with the target or one of the known-biased attributes. Extensive experiments on both disentanglement datasets and real-world datasets show that our method can discover biased attributes and achieve better disentanglement w.r.t. target attributes. Furthermore, the qualitative results show that our method can discover unnoticeable biased attributes for various object and scene classifiers, proving our method's generalizability for detecting biased attributes in diverse domains of images. 



**Contact**: Zhiheng Li (zhiheng.li@rochester.edu)



### Citation

```
@inproceedings{Li-Discover-Biases-2021,
  title = {Discover the {{Unknown Biased Attribute}} of an {{Image Classifier}}},
  booktitle = {arXiv preprint},
  author = {Li, Zhiheng and Xu, Chenliang},
  year = {2021}
}
```

