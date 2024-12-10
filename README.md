# The Seeds of the FUTURE Sprout from History: Fuzzing for Unveiling Vulnerabilities in Prospective Deep-Learning Libraries


<p align="center">
    <a href="http://arxiv.org/abs/2412.01317"><img src="https://img.shields.io/badge/arXiv-2412.01317-b31b1b.svg">
    <a href="https://sourcemap.ac.cn/#/" ><img src="https://img.shields.io/badge/supported_by-Yuantu-blue?link=https%3A%2F%2Fsourcemap.ac.cn%2F%23%2F"></a>
</p>

This is the source code repo for "**The Seeds of the FUTURE Sprout from History: Fuzzing for Unveiling Vulnerabilities in Prospective Deep-Learning Libraries**" (accepted by ICSE 2025).

## Introduction
FUTURE is the first universal fuzzing framework tailored for both newly introduced and prospective DL libraries. This framework significantly reduces the effort required to adapt fuzzing techniques to any new DL library, making it a forward-thinking tool. Additionally, FUTURE is the first fuzzing method that targets Apple MLX. FUTURE establishes a code conversion mapping between existing and prospective libraries by fine-tuning LLMs. This mapping allows it to convert historical bug codes from existing libraries into seed codes for prospective libraries, pioneering a fuzzing method from historical insights to future anticipations. FUTURE demonstrates remarkable efficacy by detecting 148 bugs across 452 targeted APIs in Apple MLX, Huawei MindSpore, and OneFlow, including 142 previously unknown bugs. Among these bugs, 10 have been assigned CVE IDs. In addition, FUTURE has identified 7 bugs in PyTorch. Beyond bug detection, FUTURE identifies 20 enhancement issues and 12 documentation problems, further showcasing its effectiveness and adaptability.

Here is the overview of FUTURE: 
![OVERVIEW](https://github.com/Redmept1on/FUTURE/blob/main/docs/overview.png)
