## Memory-Efficient Gradient Unrolling for Large-Scale Bi-level Optimization 
This is the official code repo for Memory-Efficient Gradient Unrolling for Large-Scale Bi-level Optimization (NeurIPS24).  
arXiv: https://arxiv.org/abs/2406.14095  
Please feel free to shoot an email to shenqianli@u.nus.edu for any questions.

This repository provides implementations for three experiments conducted in the paper:
1.	Data Condensation: Efficiently compress large datasets while maintaining task performance.  
   •	Framework: JAX  
	 •	Location: https://github.com/BIGKnight/FG2U_JAX/tree/master/data_condensation
2.	Meta-Learning Online Adaptation of Language Models: Meta-Learn token-wise weights for online adaption of LLMs.  
   •	Framework: PyTorch  
	 •	Location: https://github.com/ShenQianli/FG2U_CaMeLS
3.	PDE Discovery: Learn PDEs from data using BO techniques.  
   •	Framework: JAX  
	 •	Location: https://github.com/BIGKnight/FG2U_JAX/tree/master/PDE_coefs_discovery

### Citation

If you use this code or find our work helpful, please consider citing:

```
@article{shen2024memory,
  title={Memory-Efficient Gradient Unrolling for Large-Scale Bi-level Optimization},
  author={Shen, Qianli and Wang, Yezhen and Yang, Zhouhao and Li, Xiang and Wang, Haonan and Zhang, Yang and Scarlett, Jonathan and Zhu, Zhanxing and Kawaguchi, Kenji},
  journal={arXiv preprint arXiv:2406.14095},
  year={2024}
}
```
