---
layout: default

paper-title: 'MonoAvatar++: Efficient 3D Implicit Head Avatar with Mesh-anchored Hash Table Blendshapes'
authors: Ziqian Bai, Feitong Tan, Sean Fanello, Rohit Pandey, Mingsong Dou, <u>Shichen Liu</u>, Ping Tan, Yinda Zhang

conference: IEEE Conference on Computer Vision and Pattern Recognition
conference-brief: CVPR
year: 2024

link: https://augmentedperception.github.io/monoavatar-plus/

# img: /assets/images/ReFA.png
---

3D head avatars built with neural implicit volumetric representations have achieved unprecedented levels of photorealism. However, the computational cost of these methods remains a significant barrier to their widespread adoption, particularly in real-time applications such as virtual reality and teleconferencing. While attempts have been made to develop fast neural rendering approaches for static scenes, these methods cannot be simply employed to support realistic facial expressions, such as in the case of a dynamic facial performance. To address these challenges, we propose a novel fast 3D neural implicit head avatar model that achieves real-time rendering while maintaining fine-grained controllability and high rendering quality. Our key idea lies in the introduction of local hash table blendshapes, which are learned and attached to the vertices of an underlying face parametric model. These per-vertex hash-tables are linearly merged with weights predicted via a CNN, resulting in expression dependent embeddings. Our novel representation enables efficient density and color predictions using a lightweight MLP, which is further accelerated by a hierarchical nearest neighbor search method. Extensive experiments show that our approach runs in real-time while achieving comparable rendering quality to state-of-the-arts and decent results on challenging expressions.
