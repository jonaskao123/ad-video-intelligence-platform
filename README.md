# ad-video-intelligence-platform demo
![Demo](https://github.com/user-attachments/assets/6f1eeeb7-25e7-4898-a834-9c8fca1aae6f)

# Features
- **Predict ad video ctr performance**

  ![Screen Recording 2025-05-20 172730](https://github.com/user-attachments/assets/9c880345-33ca-4aec-ad82-6039b8d67e24)

- **Find visually similar ad videos**

  ![未命名的影片_ 使用 Clipchamp 製作 (5) (1)](https://github.com/user-attachments/assets/7db6831d-8172-4ec5-88b6-ebd6593b5346)

- **Shot boundary detection**

  ![20250523-0740-28 7290449 (1)](https://github.com/user-attachments/assets/4f347bc6-8012-4244-8c88-aff62125db51)

# Architecture
![ctr model v2 1 (1)](https://github.com/user-attachments/assets/e03b34dc-b3fc-45ca-8047-64a1e9e68746)

# Version
- v1: for visual guidance series  
  input: image series  

- v2: for advertising clip series  **(best-performing version in prediction)**    
  input: clip series  

- v3: for advertising clip (lightweight version of v2)  
  input: clip  

# Reference
  [1] [Montalvo-Lezama, Ricardo, Berenice Montalvo-Lezama, and Gibran Fuentes-Pineda. "Improving transfer learning for movie trailer genre classification using a dual image and video transformer." Information Processing & Management 60.3 (2023): 103343.](https://arxiv.org/pdf/2210.07983)  
  [2] [Zhu, Wentao, et al. "Autoshot: A short video dataset and state-of-the-art shot boundary detection." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023.](https://arxiv.org/pdf/2304.06116)  
  [3] [Ni, Bolin, et al. "Expanding language-image pretrained models for general video recognition." European conference on computer vision. Cham: Springer Nature Switzerland, 2022.](https://arxiv.org/pdf/2208.02816)  
  [4] [Caron, Mathilde, et al. "Emerging properties in self-supervised vision transformers." Proceedings of the IEEE/CVF international conference on computer vision. 2021.](https://openaccess.thecvf.com/content/ICCV2021/papers/Caron_Emerging_Properties_in_Self-Supervised_Vision_Transformers_ICCV_2021_paper.pdf)  
  [5] [Akiba, Takuya, et al. "Optuna: A next-generation hyperparameter optimization framework." Proceedings of the 25th ACM SIGKDD international conference on knowledge discovery & data mining. 2019.](https://arxiv.org/pdf/1907.10902)  
  [6] [Vaswani, Ashish, et al. "Attention is all you need." Advances in neural information processing systems 30 (2017).](https://arxiv.org/pdf/1706.03762)  
  [7] [Loshchilov, Ilya, and Frank Hutter. "Decoupled weight decay regularization." arXiv preprint arXiv:1711.05101 (2017).](https://arxiv.org/pdf/1711.05101)
