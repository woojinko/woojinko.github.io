---
title: "(2020 IEEE VR Paper) Optimization and Manipulation of Contextual Mutual Spaces for Multi-User Virtual and Augmented Reality Interaction"
layout: splash
excerpt: ""
header:
  image: /assets/projects/spacefind/image.gif
  teaser: /assets/projects/spacefind/teaser.gif
gallery:
  - url: /assets/projects/spacefind/furniture-2.png
    image_path: assets/projects/spacefind/furniture-2.png
    alt: "slide 1"
  - url: /assets/projects/spacefind/furniture-1.png
    image_path: assets/projects/spacefind/furniture-1.png
    alt: "slide 2"
  - url: /assets/projects/spacefind/furniture-3.png
    image_path: assets/projects/spacefind/furniture-3.png
    alt: "slide 3"
  - url: /assets/projects/spacefind/floor-rooms.png
    image_path: assets/projects/spacefind/floor-rooms.png
    alt: "slide 4"
  - url: /assets/projects/spacefind/floor-changes.gif
    image_path: assets/projects/spacefind/floor-changes.gif
    alt: "floor changes gif"
  - url: /assets/projects/spacefind/cover-graphic.gif
    image_path: assets/projects/spacefind/cover-graphic.gif
    alt: "spacefind graphic gif"
  - url: /assets/projects/spacefind/Hololens-2.gif
    image_path: assets/projects/spacefind/Hololens-2.gif
    alt: "hololens gif 2"
  - url: /assets/projects/spacefind/hololens_vis.png
    image_path: assets/projects/spacefind/hololens_vis.png
    alt: "hololens visualization"
pdf_file: "/assets/pdf/Spacefind.pdf"
---

{% include gallery %}

Under the supervision of Prof. Luisa Caldas, Dr. Allen Yang, and an Architecture PhD student, I explored the concept of mixed reality telepresence, a technology that envisions users interacting seamlessly with life-sized, full-body holograms of other users calling in remotely. In theory, telepresence could elicit the same vivid emotions and connections that come from in-person encounters. While this field has improved on constraints such as latency, reconstruction quality, and motion tracking, a key hindrance to practical implementation remains in the spatial constraints of user locomotion, given that users should be able to see each other clearly, even when they are each located in cramped indoor spaces that are often cluttered with objects. With this in mind, we created SpaceFind, a multi-stage system that generates the best shared space boundary for multiple people to interact safely and fluidly within their own everyday locations. I spent months in the lab and at home taking on a major share of the technical workload throughout the project; I taught myself how to work with Grasshopper’s C# scripts and visual programming circuits to integrate correctly with our Rhino 3D spatial representations. I also contributed to preparing 3D scan datasets and defining complex spatial optimization problems. Our system’s generated results demonstrated promising solutions with increases in total interaction area upon varying degrees of furniture rearrangement. To see SpaceFind in action, I created a basic HoloLens AR application to visualize final space layouts, again quickly learning how to develop and deploy on HoloLens with Unity with minimal prior experience.  

{% pdf {{ page.pdf_file }} %}