# Literature Review

## Research Topic

**AI-Generated Video and Audio:** Analyse the effectiveness of generative AI in creating personalised digital content, considering content quality, production efficiency, and ethical challenges.

## Research Question

**How effective is generative AI in creating personalised digital video and audio content in terms of content quality, production efficiency, and ethical challenges?**

---

## Research Paper 1

### AnimateLCM: Computation-Efficient Personalized Style Video Generation without Personalized Video Data

**Authors:** Fu-Yun Wang, Zhaoyang Huang, Weikang Bian, Xiaoyu Shi, Keqiang Sun, Guanglu Song, Yu Liu, and Hongsheng Li  
**Year:** 2024  
**Publication:** SIGGRAPH Asia 2024 Technical Communications  
**DOI:** https://doi.org/10.1145/3681758.3698013  
**Database:** ACM Digital Library / arXiv

### Purpose

This paper investigates how diffusion-based video generation can be used to create personalised video styles while reducing the computational cost and generation time.

### Methodology

The authors propose **AnimateLCM**, which uses a dual-level decoupling learning approach. The method separates personalised style learning from video generation acceleration and separates image-generation acceleration from video-motion acceleration.

### Key Findings

- AnimateLCM supports personalised style video generation without requiring personalised video training data.
- The reported generation time is reduced from about **25 seconds to around 1 second** for similarly sized videos while maintaining comparable performance.
- The method improves generation efficiency and reduces some of the negative effects associated with low-quality video training data.

### Contribution to Our Research

This paper is highly relevant to our topic because it directly addresses **personalisation** and **production efficiency** in AI-generated video. It demonstrates that generative AI can potentially reduce the time required to produce customised digital video content.

### Research Gap

The study focuses mainly on technical generation efficiency and personalised visual style. It does not fully evaluate broader factors such as human-perceived content quality, user satisfaction, long-term production workflows, or ethical issues. Therefore, further research is needed to evaluate AI-generated video across technical and social dimensions.

---

## Research Paper 2

### A Survey of Deep Learning Audio Generation Methods

**Authors:** Matej Božić and Marko Horvat  
**Year:** 2024  
**Database:** arXiv / digital academic databases  
**Paper:** https://arxiv.org/abs/2406.00146

### Purpose

This paper reviews major deep learning techniques used for audio generation and provides an overview of how different architectures and evaluation methods are used to assess generated audio.

### Methodology

The authors conduct a literature survey covering:

- Audio representations, including raw waveforms and spectrograms.
- Autoencoders.
- Generative Adversarial Networks (GANs).
- Normalizing flows.
- Transformer models.
- Diffusion models.
- Evaluation metrics for generated audio.

### Key Findings

- Deep learning has significantly changed audio generation by reducing reliance on manually designed audio features.
- Transformer and diffusion-based approaches have become increasingly important in modern audio generation.
- Audio generation can be applied to text-to-speech, music generation, voice assistants, games, movies, and other digital media.
- Evaluation is important because generated audio must be assessed not only by technical metrics but also by human perception and quality.

### Contribution to Our Research

This paper provides the **technical foundation for the audio component** of our research. It helps us understand how AI-generated audio is produced and how its quality can be evaluated.

### Research Gap

The paper provides a broad technical review but does not focus specifically on personalised digital content or the ethical consequences of voice cloning. It also indicates that different evaluation metrics measure different aspects of audio quality, suggesting that a single metric may not be sufficient for evaluating personalised AI-generated audio.

---

## Research Paper 3

### Not My Voice! A Taxonomy of Ethical and Safety Harms of Speech Generators

**Authors:** Wiebke Hutiri, Orestis Papakyriakopoulos, and Alice Xiang  
**Year:** 2024  
**Publication:** ACM Conference on Fairness, Accountability, and Transparency (FAccT 2024)  
**DOI:** https://doi.org/10.1145/3630106.3658911  
**Database:** ACM Digital Library

### Purpose

This paper examines the ethical and safety risks associated with AI-generated speech, including synthetic voices, voice cloning, and audio deepfakes.

### Methodology

The researchers analyse reported AI incidents and use a **design science research approach** to develop a conceptual framework for understanding how harms arise. They then create a taxonomy of harms associated with speech generation systems.

### Key Findings

The study shows that AI speech generation can create different types of harm depending on:

- Who is affected by the AI system.
- Who creates or deploys the system.
- The motivation for using the system.
- How the technology interacts with different stakeholders.

The paper highlights issues including impersonation, loss of agency and authorship, copyright concerns, misuse of speaker data, non-consensual use of biometric data, and deepfakes.

### Contribution to Our Research

This paper is important for the **ethical dimension** of our research. It shows that evaluating generative AI should not focus only on quality and efficiency. Personalised AI-generated audio can also create privacy, identity, consent, copyright, and safety risks.

### Research Gap

The study focuses mainly on speech generation rather than the complete combination of video and audio generation. More research is needed to examine ethical risks in **multimodal personalised content**, where AI-generated video and audio are combined.

---

# Common Themes Across the Three Papers

The three papers share several important themes:

1. **Rapid improvement in generative AI**

   All three papers show that generative AI has developed quickly and is becoming capable of producing increasingly realistic digital content.

2. **Personalisation and controllability**

   AnimateLCM demonstrates personalised video generation, while audio-generation research shows how different conditioning methods can control generated audio.

3. **Production efficiency**

   AI can reduce the time and technical effort required to create digital content. AnimateLCM provides a clear example of significant generation-time reduction.

4. **Quality evaluation**

   High-quality output is essential. Audio generation research shows that different technical and human-based evaluation methods may be necessary to measure quality properly.

5. **Ethical and safety challenges**

   More realistic generated media also increases risks related to impersonation, privacy, consent, copyright, misinformation, and misuse.

---

# Comparison of the Papers

| Paper | Main Focus | Methodology | Key Contribution | Main Limitation |
|---|---|---|---|---|
| AnimateLCM | Personalised video generation and efficiency | Diffusion/consistency-based generation method | Faster personalised video generation | Limited evaluation of ethical and user-centred factors |
| A Survey of Deep Learning Audio Generation Methods | Audio generation techniques and evaluation | Literature survey | Explains architectures and quality evaluation | Broad survey; limited focus on personalisation and ethics |
| Not My Voice! | Ethics and safety of speech generation | Incident analysis + design science | Taxonomy of AI speech harms | Focuses mainly on speech rather than full video-audio multimodal content |

---

# Research Gaps Identified

Based on the three papers, several research gaps can be identified:

- Existing studies often examine **video generation, audio generation, or ethical risks separately**.
- There is limited research evaluating **personalised video and audio together as one digital content creation process**.
- Technical performance does not necessarily equal **human-perceived quality or user satisfaction**.
- Efficiency improvements should be evaluated together with quality to determine whether faster generation actually produces useful content.
- Ethical issues such as consent, privacy, copyright, identity misuse, and deepfakes need to be considered alongside technical effectiveness.
- More empirical research is needed to develop a **combined evaluation framework covering content quality, production efficiency, and ethical risks**.

---

# Overall Conclusion

The literature suggests that generative AI has strong potential for personalised digital content creation. Research such as AnimateLCM demonstrates that personalised video generation can become much faster, while audio-generation research shows that modern deep learning architectures can generate increasingly sophisticated audio. However, technical effectiveness alone is not enough. Ethical research highlights significant risks related to identity, privacy, consent, copyright, and misuse.

Therefore, our research can contribute by evaluating generative AI from a **combined perspective of content quality, production efficiency, personalisation, and ethical challenges**, rather than examining only one technical aspect.
