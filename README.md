## Reference
When reporting results that use the dataset or code in this repository, please cite the paper below:

Haipeng Li, Mabon Ninan, Boyang Wang, John M. Emmert, "TinyPower: Side-Channel Attacks with Tiny Neural Networks," IEEE International Symposium on Hardware Oriented Security and Trust (**IEEE HOST 2024**), Washington DC, USA, May 6-9 2024

# Unstructed-Masked-Pruning-for-SCA
Unstructued Mased Pruning for SCA.
# Introduction:
This section focuses on unstructured masked pruning for deep learning side channel attacks, providing insights into the application of this technique within the context of GitHub, a popular platform for collaborative software development. By understanding the potential risks associated with side channel attacks on deep learning models deployed on GitHub, developers can take appropriate precautions to safeguard their projects and mitigate potential vulnerabilities.

# Overview of Unstructured Masked Pruning:
The section begins by explaining the concept of unstructured masked pruning in the context of deep learning models. It outlines the purpose of this technique, which involves selectively removing connections or neurons from a neural network to reduce its size while maintaining its functionality. The addition of masking mechanisms further obfuscates the pruned elements, making it challenging for attackers to identify the patterns and reverse engineer the model.

# Side Channel Attacks on Deep Learning Models:
This subsection delves into side channel attacks, emphasizing their significance in the realm of deep learning models hosted on GitHub. It highlights the various side channels, such as power consumption or timing variations, that adversaries can exploit to extract sensitive information from a model. The potential consequences of successful side channel attacks on GitHub projects are discussed, stressing the importance of taking appropriate security measures.

# Implications for GitHub Projects:
Here, the section explores the implications of unstructured masked pruning and side channel attacks specifically within the context of GitHub. It emphasizes the vulnerability of deep learning models shared on the platform and the potential impact on the integrity, confidentiality, or availability of software projects. The section also underlines the importance of addressing these concerns to maintain the trust and security of GitHub's collaborative ecosystem.

# Mitigation Strategies and Best Practices:
To assist developers in safeguarding their GitHub projects, this subsection offers a range of mitigation strategies and best practices. It covers countermeasures such as secure hardware implementations, model hardening techniques, and differential privacy approaches. Additionally, it highlights the significance of keeping software dependencies up to date, performing regular security audits, and fostering a culture of security awareness among contributors.

# Requirements:

TensorFlow:

Version: TensorFlow 2.0 or higher
Installation: Follow the official TensorFlow installation guide for the specific version required for your project.
System Requirements: Ensure that your system meets the hardware and software requirements specified by TensorFlow. These requirements typically include a compatible CPU, GPU, operating system, and library dependencies.
CUDA:

Version: CUDA 10.0 or higher (compatible with TensorFlow version)
Installation: Visit the NVIDIA CUDA Toolkit download page and follow the instructions to install CUDA on your system.
System Requirements: Check the CUDA documentation for hardware compatibility with your GPU and ensure that your system meets the minimum requirements for CUDA installation.
GPU: Titan V with 64 GB RAM

Model: NVIDIA Titan V
GPU Memory: 64 GB of dedicated GPU memory
Installation: Install the Titan V GPU into your system according to the manufacturer's instructions.
Driver: Ensure that you have the latest NVIDIA GPU driver installed for the Titan V GPU. Visit the NVIDIA driver download page to obtain the appropriate driver version for your operating system.
Note: It is crucial to check the compatibility between the versions of TensorFlow, CUDA, and the GPU driver. Different versions may have specific requirements and dependencies, so refer to the official documentation for compatibility guidelines.

By meeting the above requirements, you will have the necessary software stack and hardware configuration to utilize TensorFlow with CUDA support and leverage the capabilities of the Titan V GPU with 64 GB of RAM for deep learning tasks.


# Conclusion:
The section concludes by reiterating the importance of understanding unstructured masked pruning and side channel attacks within the context of GitHub. It emphasizes the need for developers to remain vigilant, adopt secure coding practices, and stay informed about emerging threats. By following these guidelines, GitHub users can enhance the security posture of their deep learning models, reducing the risk of side channel attacks and protecting their projects from potential vulnerabilities.



# ALL CODE IN THIS REPO IS SUBJECT TO COPY RIGHT.
# Autherized use only
Contact Mabon Ninan

UCDasec

ninanmm@mail.uc.edu
