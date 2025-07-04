---
layout: page
title: Overview
permalink: /
weight: 1
---

<div style="text-align: center; display: flex; width: 100%; justify-content: space-evenly; align-items: center; gap: 1em; padding: 2em">
  <img style="width: 20%;" src="https://github.com/Open-Finance-Lab/AI_Openness_Workshop/blob/main/docs/assets/logos/neurips.png?raw=true" alt="Neurips Logo">
  <img style="width: 10%;" src="https://github.com/Open-Finance-Lab/AI_Openness_Workshop/blob/main/docs/assets/logos/columbiau.jpeg?raw=true" alt="Columbia Logo">
  <img style="width: 20%;" src="https://github.com/Open-Finance-Lab/AI_Openness_Workshop/blob/main/docs/assets/logos/Linux_Foundation_logo.png?raw=true" alt="Linux Foundation">
  <img style="width: 20%;" src="assets/logos/pytorch.png?raw=true" alt="Pytorch">
</div>

<p align="center" style="font-size:20px; font-weight:bold;">
  December 6-7, 2025
</p>
<p align="center" style="font-size:15px;">
  9:00 AM EST - 17:40 PM EST
</p>

## Workshop Description
With the advance of artificial intelligence (AI) in recent years, concerns have also grown regarding their transparency, reproducibility, and usability. The **first challenge is that most state-of-the-art (SOTA) models are black boxes**, making it difficult to explain their internal logic, assess fairness, and ensure accountability [1]. A **second major challenge is licensing issues** widespread for AI models. 64.67% of models and 72.13% of datasets on Hugging Face are unlicensed [2]. Some models, which claim to be open, are released under restrictive licenses that do not meet the standards required of open licenses. Many models are released under open-source licenses, such as MIT and Apache 2.0. However, these licenses are designed for conventional software code and are not appropriate for the intricacies of machine learning (ML) models. A **third challenge is the completeness of ML models**, where most models only release selected artifacts, typically model architecture and model parameters. Without the full availability of components from the model development lifecycle, it is difficult to audit and reproduce ML models. 

Although more and more models are being made publicly available, many of these models are falsely being promoted as “open-source.” It is a practice that has been characterized as [“openwashing”](https://www.nytimes.com/2024/05/17/business/what-is-openwashing-ai.html) [3], where “open” has been used loosely for both minimally and fully transparent systems. The lack of transparency and reproducibility in AI models hinders scientific progress and erodes trust in AI research and development (R&D). Without a standardized framework to evaluate and promote openness, it becomes challenging to verify claims, build upon existing work, and ensure responsible development.

To address these challenges, new standards are being developed, such as the [Open Source AI Definition 1.0](https://opensource.org/ai/open-source-ai-definition) [4]; tools for auditing model explainability, fairness, and robustness [5]; and frameworks to evaluate model openness, such as the AAAI Reproducibility Checklist [6] and the NeurIPS 2019 ML Reproducibility Checklist [7]. The [Model Openness Framework (MOF)](https://lfaidata.foundation/blog/2024/04/17/introducing-the-model-openness-framework-promoting-completeness-and-openness-for-reproducibility-transparency-and-usability-in-ai/) [8], developed by the Linux Foundation, is designed to evaluate the completeness and openness of ML models across the model development. However, there is not yet a formally agreed-upon definition of “open source AI,” highlighting the need for broader interdisciplinary discussion. This workshop aims to promote discussions and collaborations among researchers, practitioners, and policymakers on openness in AI. 



<div style="text-align:center; margin-bottom:40px;">
  <h2 style="margin-bottom:30px;">Confirmed Invited Speakers and Pannelists</h2>

  <div style="display:flex; flex-wrap:wrap; justify-content:center; gap:40px;">

  <a href="https://www.linkedin.com/in/lehors/" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/speakers/arnaud_le_hors.jpeg" alt="Arnaud Le Hors" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Arnaud Le Hors</h3>
        <p style="color:#777;">IBM</p>
      </div>
  </a>


  <a href="https://www.linkedin.com/in/greglindahl/" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/speakers/greg-lindahl.png" alt="Greg Lindahl" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Greg Lindahl</h3>
        <p style="color:#777;">Common Crawl</p>
      </div>
  </a>

   <a href="https://www.linkedin.com/in/annilai/" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/speakers/anni_lai.jpeg" alt="nni Lai" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Anni Lai</h3>
        <p style="color:#777;">Futurewei Technologies</p>
      </div>
  </a>

  <a href="https://www.cs.princeton.edu/~sayashk/" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/speakers/Sayash_Kapoor.png" alt="Sayash Kapoor" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Sayash Kapoor</h3>
        <p style="color:#777;">Princeton University</p>
      </div>
  </a>

  <a href="https://profiles.ucl.ac.uk/56579-hao-ni" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/speakers/hao-ni.png" alt="Hao Ni" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Hao Ni</h3>
        <p style="color:#777;">UCL</p>
      </div>
  </a>

  <a href="https://armancohan.com/" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/speakers/arman-cohan.png" alt="Arman Cohan" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Arman Cohan</h3>
        <p style="color:#777;">Yale University</p>
      </div>
  </a>

  <a href="https://guestrin.su.domains/" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/speakers/Carlos-Guestrin.jpeg" alt="Carlos Guestrin" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Carlos Guestrin</h3>
        <p style="color:#777;">Stanford University</p>
      </div>
  </a>

  </div>

</div>



<div style="text-align:center; margin-bottom:40px;">
  <h2 style="margin-bottom:30px;">Workshop Organizers</h2>

<div style="display:flex; flex-wrap:wrap; justify-content:center; gap:40px;">

  <a href="https://scholar.google.com/citations?user=C83b8ncAAAAJ&hl=en" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/organizers/supervisors/liu-xy.png" alt="Xiao-Yang Liu" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Xiao-Yang Liu</h3>
        <p style="color:#777;">Columbia University</p>
      </div>
  </a>

  <a href="https://www.matt-white.com/" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/speakers/matt-white.png" alt="Matt White" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Matt White</h3>
        <p style="color:#777;">Linux Foundation & PyTorch Foundation</p>
      </div>
  </a>

  <a href="" target="_blank" style="text-decoration:none; color:inherit;">
    <div style="width:180px;">
      <img src="assets/organizers/keyi.jpeg" alt="Keyi Wang" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
      <h3 style="margin-top:15px;">Keyi Wang</h3>
      <p style="color:#777;">Columbia University</p>
    </div>
  </a>

  

  <a href="https://www.oii.ox.ac.uk/people/profiles/cailean-osborne/" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/organizers/Cailean_Osborne.jpeg" alt="Cailean Osborne" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Cailean Osborne</h3>
        <p style="color:#777;">Oxford University</p>
      </div>
  </a>

  <a href="" target="_blank" style="text-decoration:none; color:inherit;">
      <div style="width:180px;">
        <img src="assets/organizers/Sachin.jpeg" alt="Sachin Mathew Varghese" style="width:180px; height:180px; border-radius:50%; object-fit:cover;">
        <h3 style="margin-top:15px;">Sachin Mathew Varghese</h3>
        <p style="color:#777;">Linux Foundation Generative AI Commons</p>
      </div>
  </a>


  </div>
</div>






<p style="font-size: 10px;">
[1]  R. Bommasani, D. A. Hudson, E. Adeli, R. Altman, S. Arora, S. von Arx, M. S. Bernstein, J. Bohg, A. Bosselut, E. Brunskill, et al., “On the opportunities and risks of foundation models,” arXiv:2108.07258, 2021.
</p>
<p style="font-size: 10px;">
[2] C. Osborne, J. Ding, and H. R. Kirk, “The AI community building the future? A quantitative analysis of development activity on Hugging Face Hub,” Journal of Computational Social Science, pp. 1–39, 2024.
</p>
<p style="font-size: 10px;">
[3] S. Kessler, “Openwashing,” New York Times, 2024.
</p>
<p style="font-size: 10px;">
[4] O. S. Initiative, “Open source AI deep dive,” Open Source Initiative, 2023.
</p>
<p style="font-size: 10px;">
[5] I. D. Raji, A. Smart, R. N. White, M. Mitchell, T. Gebru, B. Hutchinson, J. Smith-Loud, D. Theron, and P. Barnes, “Closing the AI accountability gap: Defining an end-to-end framework for internal algorithmic auditing,” in Proceedings of the ACM Conference on Fairness, Accountability, and Transparency, pp. 33–44, Association for Computing Machinery, 2020. 
</p>
<p style="font-size: 10px;">
[6] B. A. Nosek, G. Alter, G. C. Banks, D. Borsboom, S. D. Bowman, S. J. Breckler, S. Buck, C. D. Chambers, G. Chin, G. Christensen, M. Contestabile, A. Dafoe, E. Eich, J. Freese, R. Glennerster, D. Goroff, D. P. Green, B. Hesse, M. Humphreys, J. Ishiyama, D. Karlan, A. Kraut, A. Lupia, P. Mabry, T. Madon, N. Malhotra, E. Mayo-Wilson, M. McNutt, E. Miguel, E. L. Paluck, U. Simonsohn, C. Soderberg, B. A. Spellman, J. Turitto, G. VandenBos, S. Vazire, E. J. Wagenmakers, R. Wilson, and T. Yarkoni, “Promoting an open research culture,” Science, vol. 348, no. 6242, pp. 1422–1425, 2015.
</p>
<p style="font-size: 10px;">
[7] J. Pineau, P. Vincent-Lamarre, K. Sinha, V. Larivière, A. Beygelzimer, F. d’Alché Buc, E. Fox, and H. Larochelle, “Improving reproducibility in machine learning research (a report from the neurips 2019 reproducibility program),” Journal of Machine Learning Research, vol. 22, no. 164, pp. 1–20, 2021.
</p>
<p style="font-size: 10px;">
[8] M. White, I. Haddad, C. Osborne, X.-Y. Y. Liu, A. Abdelmonsef, S. Varghese, and A. L. Hors, “The model
openness framework: Promoting completeness and openness for reproducibility, transparency, and usability in
artificial intelligence,” arXiv:2403.13784, 2024.
</p>


## Contact
Contact email: 




