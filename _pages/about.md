---
layout: about
title: about
permalink: /
subtitle: <a href='https://www.bupt.edu.cn/'>Beijing University of Posts and Telecommunications</a>. chenzhi_zhao@bupt.edu.cn

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>No.10 Xitucheng Road, Haidian District</p>
    <p>Beijing, China</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](https://www.reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
I am currently a second-year Master's student at the School of Computer Science and Technology, Beijing University of Posts and Telecommunications (BUPT), advised by Prof. Wendong Wang. I received my B.E. degree from BUPT with First-Class Honours (Top 5%, Beijing Outstanding Graduate).

My research primarily centers on Computer Vision and Deep Learning. I have a strong foundation in spatiotemporal representation learning, evidenced by my recent work on efficient dense point tracking (AAAI 2026, First Author). 

Currently, I am actively seeking Ph.D. opportunities commencing in Fall 2027. My research interests are evolving towards Video Generation and Multimodal Large Models. I am eager to leverage my background in understanding temporal dynamics and foundational models to build the next generation of generative AI systems.

## Internships

**Shukun Technology (数坤科技)** | *Algorithm Intern* | *Mar 2024 - Jun 2024*
- Responsible for data processing of abdominal and brain CT and MR images, including format conversion, standardization, data augmentation, and normalization.
- **Bridged multi-modal domain gaps:** Developed a 3D medical image unsupervised style transfer pipeline from CT to MR on Amos22 dataset based on CycleGAN, eliminating 3D stacking slice blurring and checkerboard artifacts.
- **Led Unsupervised Domain Adaptation (UDA):** Fine-tuned the Uniseg model across modalities using nnUNet, incorporating generated Fake-MR images for adversarial data augmentation. Achieved significant Dice score improvements for small/long-tail organs.
- **Built efficient pre-labeling engine:** Localized the MRSegmentator model to establish a pseudo-labeling pipeline for abdominal data, enabling a closed-loop data annotation with zero human cost.
- **Broke edge inference bottlenecks:** Optimized inference pipeline and deployed the model using TorchScript and graph pruning on low-vRAM (A10) GPUs, reducing OOM risk to <1%.