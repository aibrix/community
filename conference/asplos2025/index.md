# ASPLOS'25 Tutorial - AIBrix: An Open Source Large-Scale LLM Inference Infrastructure for System Research


## Abstract

The rapid advancements in large language model (LLM) inference have spurred numerous innovations. Our findings suggest that for LLMs to be effectively deployed in production environments, optimization at the engine level alone is insufficient. Successful production deployment demands a holistic approach  that integrates optimizations across three key layers: the model layer, the engine layer, and the system layer.

AIBrix is an open-source system-level solution designed to address the complexities of LLM inference in production environments. It provides a seamless platform to transform large models into scalable APIs, focusing on critical system aspects such as LLM specific autoscaling strategies, model locality scheduling, cost-efficient management of heterogeneous hardware, and efficient online and offline request colocation. AIBrix facilitates cutting-edge research in large-scale LLM inference by offering researchers a flexible framework to explore system-level challenges, accelerating innovation in areas that go beyond engine optimization. Some popular paper ideas like OSDI'24 ServerlessLLM, ASPLOS'24 QLM, Preble, have been integrated into AIBrix for benchmarking.

## Location & Time

- **Venue**: Postillion Hotel & Convention Centre WTC Rotterdam, Rotterdam, The Netherlands
- **Room**: Leeuwen room II
- **Date & Time**: Sunday 30 March, 2025, Afternoon 2:00 PM to 5:30 PM 

[Venue Map & Directions](https://www.asplos-conference.org/asplos2025/conference-venue/)
 

## Schedule
Section 1 (2:00PM - 3:30PM):
- Introducing AIbrix: A Testbed for Large-Scale LLM Inference System Research
- LLM-Tailored Autoscaling: Leveraging LLM-specific Metrics and Embracing Resource Heterogeneity 
- Reducing Inference Bottlenecks in Shared Prompt Environments with Prefix Caching
- KV Cache Offloading for Cross-Engine KV Reuse
- Multi-LoRA Management in Production Environment 
- Open Research Challenges in LLM Inference systems

Section 2 (4:00PM - 5:30PM):
- Hands-on AIBrix Feature Demo in AWS Studio Workshop  


> Note: All the slides will be made available shortly before the tutorials.


## Organizer

| <div style="width:360px">Author</div> | Introduction |
| ------------------------------------- | ------------ |
| <img src="https://avatars.githubusercontent.com/u/4739316?v=4" alt="Jiaxin Shan" width="360px" height="100px"> | Jiaxin Shan, Software Engineer in Bytedance Serverless Compute Infrastructure Team. He received a MS degree from University of Pittsburgh. His research interests focus on ML Infra and Serverless systems. He is a co-chair in Kubernetes WG-Serving and Kubeflow community. |
| <img src="https://lexu1.web.engr.illinois.edu/images/profile-cropped.jpg" alt="Le Xu" width="360px" height="100px"> | Le Xu is a Researcher in Bytedance. She got her Ph.D. degree from UIUC, advised by Professor Indranil Gupta. Her research focuses on distributed systems, streaming systems and AI systems. She has authored several publications in top-tier conferences, including NSDI, SoCC, and EuroSys. |
| <img src="https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=71rG3bEAAAAJ&citpid=4" alt="Haiyang Shi" width="360px" height="100px"> | Haiyang Shi is a Researcher/Engineer in Bytedance Serverless Compute Infrastructure Team. He obtained his Ph.D. from The Ohio State University, advised by Prof. Xiaoyi Lu. His research focuses on distributed systems, AI infra, and high-performance interconnects and protocols. |
| <img src="https://media.licdn.com/dms/image/v2/D5603AQEwpRd7DJEUvg/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1698611002277?e=1748476800&v=beta&t=2syCEM3OiLVBmlOaK6cwEa73tlCSRX47FaXYJsXDW84" alt="Gangmuk Lim" width="360px" height="100px"> | Gangmuk Lim is a Ph.D. student at University of Illinois at Urbana-Champaign and is currently working as a Research Intern at ByteDance. His research area is improving performance and resilience of microservice applications, and LLM inference application in the cloud-native environment. He is particularly interested in request routing leveraging application layer knowledge.|
| <img src="https://wangncs.github.io/images/profile.jpg" alt="Ning Wang" width="360px" height="100px"> | Ning Wang works as a Research Engineer at ByteDance. He earned his Ph.D. from Temple University. His research interests include developing innovative on-device and cloud-based AI systems and applications. |
| <img src="https://shuoweijin.com/authors/admin/avatar_hu47311af3cf29288c7e7c3a30ecf0e3ad_16517156_270x270_fill_lanczos_center_3.png" alt="Shuowei Jin" width="360px" height="100px"> | Shuowei Jin is a fifth-year PhD candidate at the University of Michigan, advised by Professor Morley Mao. His research focuses on enhancing LLM inference efficiency through algorithm and systems codesign.  |
| <img src="https://media.licdn.com/dms/image/v2/D5603AQHd6Pgk-ysUgA/profile-displayphoto-shrink_400_400/B56ZVGI2v8GUAk-/0/1740638482118?e=1746057600&v=beta&t=vJB4uzFFLxCFCE3xOXW8yntHXI0pdiJlfh_zKNDNikQ" alt="Rong Kang" width="360px" height="100px"> | Rong Kang is a Research Engineer at ByteDance. He obtained his Ph.D. degree from Tsinghua University. Passionate about the synergy between AI and systems, his academic and engineering interests are centered around AI for DB, DB for AI, and LLM Serving. |
| <img src="https://media.licdn.com/dms/image/v2/D5603AQEJQQgN_capHg/profile-displayphoto-shrink_100_100/B56ZVGIslvHoAY-/0/1740638440411?e=1746057600&v=beta&t=fzVOBgzuKhhzn-YboypbnHFv17qfA_URjB9eIfMM-Ho" alt="Linhui Xu" width="360px" height="100px"> | Linhui Xu, ByteDance Research Engineer. Master from Institute of Computing Technology Chinese Academy of Sciences. He is interested in AI for DB, LLM Acceleration. |
| <img src="https://media.licdn.com/dms/image/v2/D4E03AQFVqETCOAwZnw/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1681390275508?e=1748476800&v=beta&t=f91LcvqfQVu6bz9dkZ1pk65ZuTITuwEVQ1aqUnAe9ys" alt="Premdass Ravi" width="360px" height="100px"> | Premdass works as Specalist TAM for AWS, on the enterprise support team. He works on helping AWS customers solve scaling probelms of the EKS clusters. His interests focus on cloud infrastructure, ML Infra and startups. |
| <img src="https://avatars.githubusercontent.com/u/12957223?v=4" alt="Liguang Xie" width="360px" height="100px"> | Liguang Xie is the Director of Engineering, Serverless Compute Infrastructure at ByteDance, where he leads the growth of compute infrastructure across North America, Europe, and Asia Pacific to support the company’s global business units. He holds a Ph.D. in Computer Engineering from Virginia Tech and is passionate about accelerating innovation in AI and machine learning. A recipient of the IEEE INFOCOM 2023 Test of Time Award, Liguang’s research focuses on cloud infrastructure, cloud-native architecture, large-scale LLM inference systems, and machine learning systems and infrastructure. |
 

## Contact us

For any further questions, please reach out to us on [vLLM Slack Channel](https://vllm-dev.slack.com/archives/C08EQ883CSV) or send email to [Liguang Xie](liguang.xie@bytedance.com) or [Jiaxin Shan](jiaxin.shan@bytedance.com).

<p align="center">
 <img src="https://www.asplos-conference.org/wp-content/uploads/2024/06/ASPLOS2025-Logo-black-1.png" width="200px">
</p>
