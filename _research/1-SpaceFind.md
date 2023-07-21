---
title: "SpaceFind | Mohammad Keshavarzi, Allen Y Yang, Woojin Ko, and Luisa Caldas"
layout: splash
excerpt: "Paper: Optimization and Manipulation of Contextual Mutual Spaces for Multi-User Virtual and Augmented Reality Interaction"
header:
  image: /assets/images/research/spacefind/spacefind_graphic.gif
  teaser: /assets/images/research/spacefind/spacefind_graphic.gif
gallery:
  - url: /assets/images/research/spacefind/furniture-2.png
    image_path: assets/images/research/spacefind/furniture-2.png
    alt: "slide 1"
  - url: /assets/images/research/spacefind/furniture-1.png
    image_path: assets/images/research/spacefind/furniture-1.png
    alt: "slide 2"
  - url: /assets/images/research/spacefind/furniture-3.png
    image_path: assets/images/research/spacefind/furniture-3.png
    alt: "slide 3"
  - url: /assets/images/research/spacefind/floor-rooms.png
    image_path: assets/images/research/spacefind/floor-rooms.png
    alt: "slide 4"
  - url: /assets/images/research/spacefind/floor-changes.gif
    image_path: assets/images/research/spacefind/floor-changes.gif
    alt: "floor changes gif"
  - url: /assets/images/research/spacefind/spacefind_graphic.gif
    image_path: assets/images/research/spacefind/spacefind_graphic.gif
    alt: "spacefind graphic gif"
  - url: /assets/images/research/spacefind/Hololens-1.gif
    image_path: assets/images/research/spacefind/Hololens-1.gif
    alt: "hololens gif 1"
  - url: /assets/images/research/spacefind/Hololens-2.gif
    image_path: assets/images/research/spacefind/Hololens-2.gif
    alt: "hololens gif 2"
  - url: /assets/images/research/spacefind/hololens_vis.png
    image_path: assets/images/research/spacefind/hololens_vis.png
    alt: "hololens visualization"
---

{% include gallery %}

Under the supervision of Prof. Luisa Caldas, Dr. Allen Yang, and an Architecture PhD student, I explored the concept of mixed reality telepresence, a technology that envisions users interacting seamlessly with life-sized, full-body holograms of other users calling in remotely. In theory, telepresence could elicit the same vivid emotions and connections that come from in-person encounters. While this field has improved on constraints such as latency, reconstruction quality, and motion tracking, a key hindrance to practical implementation remains in the spatial constraints of user locomotion, given that users should be able to see each other clearly, even when they are each located in cramped indoor spaces that are often cluttered with objects. With this in mind, we created SpaceFind, a multi-stage system that generates the best shared space boundary for multiple people to interact safely and fluidly within their own everyday locations. I spent months in the lab and at home taking on a major share of the technical workload throughout the project; I taught myself how to work with Grasshopper’s C# scripts and visual programming circuits to integrate correctly with our Rhino 3D spatial representations. I also contributed to preparing 3D scan datasets and defining complex spatial optimization problems. Our system’s generated results demonstrated promising solutions with increases in total interaction area upon varying degrees of furniture rearrangement. To see SpaceFind in action, I created a basic HoloLens AR application to visualize final space layouts, again quickly learning how to develop and deploy on HoloLens with Unity with minimal prior experience.  

Along with the many learning opportunities and triumphs over obstacles, there came some real struggles in this research experience. Despite spending countless hours scrolling through documentation and clacking away at the umpteenth unforeseen error in integrating parts of our system, I found the time constraints of the CHI 2019 conference submission deadline to be too tight. As I realized I would not be able to produce multi-user capabilities or user-oriented designs for the HoloLens experience in time, we were forced to pivot away in order to invest our time in putting a paper publication together. For our submission to CHI 2019, our reviewers seemed impressed and interested in SpaceFind overall, but they were hesitant about our lack of user experiments for such an HCI-focused conference. I felt humbled as we decided to withdraw our submission, but we greatly appreciated and internalized the feedback. After retargeting our work to a more quantitative and analytical basis, our latest paper version was submitted and accepted at IEEE VR 2020.