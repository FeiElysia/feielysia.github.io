---
permalink: /
title: "Welcome to Junjie Fei's Homepage!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a second-year PhD student at King Abdullah University of Science and Technology (KAUST), advised by [Prof. Mohamed Elhoseiny](https://www.mohamed-elhoseiny.com/). My research interests lie in vision-language learning and long visual context modeling. Recently, I completed a Research Scientist Internship at Meta AI, hosted by Dr. [Chenchen Zhu](https://sites.google.com/andrew.cmu.edu/zcckernel), where my work focused on long video understanding.

Prior to KAUST, I received my BS and MS degrees from Chongqing University and Xiamen University, respectively. I also gained research experience as a research assistant and visiting scholar at SUSTech VIP Lab and [KAUST Vision CAIR](https://cemse.kaust.edu.sa/vision-cair). For more details, please refer to my [CV](https://feielysia.github.io/images/CV.pdf).

> 💡 **Open to collaboration:** I am actively seeking research internship opportunities! I am also widely open to talks, discussions, and collaborations in the multimodal learning community. Feel free to reach out to me at [junjiefei@outlook.com](mailto:junjiefei@outlook.com) or [junjie.fei@kaust.edu.sa](mailto:junjie.fei@kaust.edu.sa).

<style>
  .news-wrapper {
    max-height: 140px; 
    overflow: hidden;
    transition: max-height 0.6s ease; 
    position: relative;
    padding-bottom: 10px; 
  }
  
  .news-wrapper:hover {
    max-height: 1000px;
  }

  /* can be remove */
  .news-wrapper::after {
    content: "";
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 40px;
    background: linear-gradient(to bottom, transparent, white);
    pointer-events: none;
    transition: opacity 0.4s ease;
  }

  .news-wrapper:hover::after {
    opacity: 0;
  }
</style>

News
======

<div class="news-wrapper" markdown="1">

* [2026/06] [*Tempo*](https://feielysia.github.io/tempo-page/) has been accepted to ECCV 2026! 🎉
* [2026/04] Project [*Tempo*](https://feielysia.github.io/tempo-page/) from my Meta AI internship is publicly released!
* [2025/09] One paper has been accepted by NeurIPS 2025!
* [2025/09] Joined Meta AI as a Research Scientist Intern!
* [2025/06] Two papers have been accepted by ICCV 2025!
* [2025/02] One paper has been accepted by CVPR 2025!
* [2024/08] Joined KAUST as a PhD student!
* [2023/07] One paper has been accepted by ICCV 2023!
* [2023/04] Project [*Caption Anything*](https://github.com/ttengwang/Caption-Anything) is publicly released!

</div>

Experience
======

<table style="width:100%; border:0px; border-collapse:collapse; margin: 20px 0;"><tbody>

  <tr style="border:0px;">
    <td style="padding:10px; width:10%; vertical-align:middle; text-align:center; border:0px;">
      <img src='images/meta_logo.png' style="width: 35px; height: auto;">
    </td>
    <td style="padding:10px; width:90%; vertical-align:middle; border:0px;">
      <p style="margin:0; font-size: 1.05em;">
        <strong>Meta AI</strong> <br>
        <span style="font-size: 0.95em; color: #333;">Research Scientist Intern | <em>Sep. 2025 - Feb. 2026</em></span>
      </p>
    </td>
  </tr>

  <tr style="border:0px;">
    <td style="padding:10px; width:10%; vertical-align:middle; text-align:center; border:0px;">
      <img src='images/kaust_logo.png' style="width: 32px; height: auto;">
    </td>
    <td style="padding:10px; width:90%; vertical-align:middle; border:0px;">
      <p style="margin:0; font-size: 1.05em;">
        <strong>Vision CAIR Research Group, KAUST</strong> <br>
        <span style="font-size: 0.95em; color: #333;">Visiting Scholar | <em>Jan. 2024 - May 2024</em></span>
      </p>
    </td>
  </tr>

  <tr style="border:0px;">
    <td style="padding:10px; width:10%; vertical-align:middle; text-align:center; border:0px;">
      <img src='images/sustech_logo.png' style="width: 30px; height: auto;">
    </td>
    <td style="padding:10px; width:90%; vertical-align:middle; border:0px;">
      <p style="margin:0; font-size: 1.05em;">
        <strong>VIP (Visual Intelligence & Perception) Lab, SUSTech</strong> <br>
        <span style="font-size: 0.95em; color: #333;">Visiting Scholar / Research Assistant | <em>Oct. 2022 - Jan. 2024</em></span>
      </p>
    </td>
  </tr>

</tbody></table>

Research
======
(* equal contribution)

<table style="width:100%;max-width:800px;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto"><tbody>

  <tr onmouseout="tempo_stop()" onmouseover="tempo_start()">
    <td style="padding:20px;width:25%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <!-- <div class="one">
          <img src='images/tempo.jpg' width="400">
        </div> -->
        <div class="one">
          <!-- <video width="100%" height="auto" muted autoplay loop playsinline>
            <source src="videos/demo.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video> -->
          <video width="100%" height="auto" muted autoplay loop playsinline poster="images/tempo.jpg">
            <source src="videos/demo.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
        </div>
    </td>
    <td style="padding:20px;width:75%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <a href="https://arxiv.org/abs/2604.08120">
          <papertitle>Small Vision-Language Models are Smart Compressors for Long Video Understanding</papertitle>
        </a>
        <br>
        <strong>Junjie Fei</strong>, Jun Chen, Zechun Liu, Yunyang Xiong, Chong Zhou, Wei Wen, Junlin Han, Mingchen Zhuge, Saksham Suri, Qi Qian, Shuming Liu, Lemeng Wu, Raghuraman Krishnamoorthi, Vikas Chandra, Mohamed Elhoseiny, Chenchen Zhu
        <br>
        <em>arXiv</em>, 2026
        <br>
        <a href="https://feielysia.github.io/tempo-page/">project</a>
        /
        <a href="https://github.com/feielysia/Tempo">code</a>
        /
        <a href="https://arxiv.org/pdf/2604.08120.pdf">paper</a>
        /
        <a href="https://huggingface.co/spaces/Vision-CAIR/Tempo">demo</a>
        <p></p>
        <p>
        Tempo is a highly efficient, query-aware framework that leverages a <strong>Small Vision-Language Model (SVLM)</strong> as an intelligent temporal compressor. It adaptively distills long-form video content into semantic-rich tokens in a single forward pass, achieving SOTA performance on LVBench while significantly reducing the computational overhead of processing hour-long videos.
        </p>
    </td>
  </tr>

  <tr onmouseout="iadsurvey_stop()" onmouseover="iadsurvey_start()">
    <td style="padding:20px;width:25%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <div class="one">
          <img src='images/Kestrel.jpg' width="400">
        </div>
    </td>
    <td style="padding:20px;width:75%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <a href="https://arxiv.org/abs/2405.18937">
          <papertitle>Kestrel: 3D Multimodal LLM for Part-Aware Grounded Description</papertitle>
        </a>
        <br>
        Mahmoud Ahmed*, <strong>Junjie Fei*</strong>, Jian Ding, Eslam Mohamed Bakr, Mohamed Elhoseiny
        <br>
        <em>ICCV</em>, 2025
        <br>
        <a href="https://feielysia.github.io/Kestrel.github.io/">project</a>
        /
        <a href="https://arxiv.org/pdf/2405.18937">paper</a>
        <p></p>
        <p>
        Kestrel is a part-aware point grounding 3D MLLM, capable of comprehending and generating language and locating the position of the object and its materials at the part level.
        </p>
    </td>
  </tr>

  <tr onmouseout="iadsurvey_stop()" onmouseover="iadsurvey_start()">
    <td style="padding:20px;width:25%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <div class="one">
          <img src='images/WikiAutoGen.jpg' width="400">
        </div>
    </td>
    <td style="padding:20px;width:75%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <a href="https://arxiv.org/abs/2503.19065">
          <papertitle>WikiAutoGen: Towards Multi-Modal Wikipedia-Style Article Generation</papertitle>
        </a>
        <br>
        Zhongyu Yang*, Jun Chen*, Dannong Xu, <strong>Junjie Fei</strong>, Xiaoqian Shen, Liangbing Zhao, Chun-Mei Feng, Mohamed Elhoseiny
        <br>
        <em>ICCV</em>, 2025
        <br>
        <a href="https://wikiautogen.github.io/">project</a>
        /
        <a href="https://github.com/01yzzyu/wikiautogen">code</a>
        /
        <a href="https://arxiv.org/pdf/2503.19065">paper</a>
        <p></p>
        <p>
        WikiAutoGen is a novel system for automated multimodal Wikipedia-style article generation, retrieving and integrating relevant images alongside text to enhance both the depth and visual appeal of the generated content.
        </p>
    </td>
  </tr>

  <tr onmouseout="iadsurvey_stop()" onmouseover="iadsurvey_start()">
    <td style="padding:20px;width:25%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <div class="one">
          <img src='images/Dochaystack.jpg' width="400">
        </div>
    </td>
    <td style="padding:20px;width:75%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Chen_Document_Haystacks__Vision-Language_Reasoning_Over_Piles_of_1000_Documents_CVPR_2025_paper.html">
          <papertitle>Document Haystacks: Vision-Language Reasoning Over Piles of 1000+ Documents</papertitle>
        </a>
        <br>
        Jun Chen*, Dannong Xu*, <strong>Junjie Fei*</strong>, Chun-Mei Feng, Mohamed Elhoseiny
        <br>
        <em>CVPR</em>, 2025
        <br>
        <a href="https://github.com/Vision-CAIR/dochaystacks">code</a>
        /
        <a href="https://arxiv.org/pdf/2411.16740">paper</a>
        /
        <a href="https://huggingface.co/datasets/DanielXu0208/Document_Haystacks">benchmark</a>
        <p></p>
        <p>
        The Document Haystack Benchmarks aim to evaluate the performance of VLMs on large-scale visual document retrieval and understanding.
        </p>
    </td>
  </tr>

  <tr onmouseout="iadsurvey_stop()" onmouseover="iadsurvey_start()">
    <td style="padding:20px;width:25%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <div class="one">
          <img src='images/ViECap.jpg' width="400">
        </div>
    </td>
    <td style="padding:20px;width:75%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Fei_Transferable_Decoding_with_Visual_Entities_for_Zero-Shot_Image_Captioning_ICCV_2023_paper.html">
          <papertitle>Transferable Decoding with Visual Entities for Zero‑Shot Image Captioning</papertitle>
        </a>
        <br>
        <strong>Junjie Fei*</strong>, Teng Wang*, Jinrui Zhang, Zhenyu He, Chengjie Wang, Feng Zheng
        <br>
        <em>ICCV</em>, 2023
        <br>
        <a href="https://github.com/FeiElysia/ViECap">code</a>
        /
        <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Fei_Transferable_Decoding_with_Visual_Entities_for_Zero-Shot_Image_Captioning_ICCV_2023_paper.pdf">paper</a>
        <p></p>
        <p>
        Improving the transferability of zero-shot captioning for out-of-domain images by addressing the modality bias and object hallucination that arise when adapting pre-trained vision-language models and large language models.
        </p>
    </td>
  </tr>

  <tr>
    <td style="padding:20px;width:25%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <div class="one">
          <img src='images/cat.gif' width="400">
        </div>
    </td>
    <td style="padding:20px;width:75%;vertical-align:middle;border:0px;border-spacing:0px;border-collapse:separate">
        <a href="https://arxiv.org/abs/2305.02677">
          <papertitle>Caption Anything: Interactive Image Description with Diverse Multimodal Controls</papertitle>
        </a>
        <br>
        Teng Wang*, Jinrui Zhang*, <strong>Junjie Fei*</strong>, Hao Zheng, Yunlong Tang, Zhe Li, Mingqi Gao, Shanshan Zhao
        <br>
        <em>arXiv</em>, 2023
        <br>
        <a href="https://github.com/ttengwang/Caption-Anything">code</a>
        /
        <a href="https://arxiv.org/pdf/2305.02677.pdf">paper</a>
        /
        <a href="https://huggingface.co/spaces/TencentARC/Caption-Anything">demo</a>
        <p></p>
        <p>
        Caption Anything is an interactive image‑to‑text generative tool that can generate diverse descriptions for any user-specified object within an image, providing a variety of language styles and visual controls to cater to diverse user preferences.
        </p>
    </td>
  </tr>

</tbody></table>

Academic Services
======

<div style="margin-left: 10px; margin-bottom: 20px; margin-top: 20px;">
  <h4 style="font-size: 1.1em; font-weight: 500; color: #333; margin-bottom: 5px;">Conference Reviewer</h4>
  <p style="font-size: 0.95em; color: #555; margin: 0; padding-left: 15px; line-height: 1.5;">
    CVPR, ECCV, NeurIPS, ICML, ICLR
  </p>
</div>

<div style="margin-left: 10px; margin-bottom: 20px;">
  <h4 style="font-size: 1.1em; font-weight: 500; color: #333; margin-bottom: 5px;">Journal Reviewer</h4>
  <p style="font-size: 0.95em; color: #555; margin: 0; padding-left: 15px; line-height: 1.5;">
    IEEE TMM, Neurocomputing, CVIU
  </p>
</div>

<div style="max-width: 400px; margin-top: 30px; margin-left: 10px; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 10px rgba(0,0,0,0.05);">
    <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=g9SZs5u3hwA_RMZqdhNPB716AxHRJQYXSMQDCKNg77g&cl=ffffff&w=a"></script>
</div>