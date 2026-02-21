---
layout: archive
title: "CV"
permalink: /cv-json/
author_profile: false
redirect_from:
  - /resume-json
---

{% include base_path %}

{% include cv-template.html %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download CV as PDF</a>
  <a href="{{ base_path }}" class="btn btn--inverse">View Markdown CV</a>
</div>
{
  "basics": {
    "name": "Jiayi Guo",
    "label": "B.Eng. Student (Communication Engineering)",
    "email": "jiayiguo@std.uestc.edu.cn",
    "phone": "",
    "website": "https://richarf22.github.io",
    "summary": "Final-year undergraduate student in the UESTC & University of Glasgow joint program. Research interests include large language models (LLMs) and computer vision.",
    "location": {
      "address": "",
      "postalCode": "",
      "city": "Chengdu",
      "countryCode": "CN",
      "region": ""
    },
    "profiles": [
      {
        "network": "GitHub",
        "username": "richarf22",
        "url": "https://github.com/richarf22"
      },
      {
        "network": "Google Scholar",
        "username": "",
        "url": ""
      }
    ]
  },
  "work": [
    {
      "company": "National Supercomputing Center",
      "position": "Research Intern — Diffusion Models for Virtual Try-On Systems",
      "startDate": "2024-09",
      "endDate": "2025-04",
      "summary": "Supervisor: Dr. Changwei Wang (Jinan, China)",
      "highlights": [
        "Developed a virtual try-on framework using diffusion models, enabling clothing visualization from a single image.",
        "Improved realism and garment-fitting accuracy to enhance the online shopping experience.",
        "Addressed long-sleeve to short-sleeve replacement using staged and partial replacement strategies."
      ]
    },
    {
      "company": "University of Electronic Science and Technology of China (UESTC)",
      "position": "Research Assistant — Generative AI in Semantic Communication Systems",
      "startDate": "2024-04",
      "endDate": "2025-05",
      "summary": "Supervisor: Prof. Yusha Liu (Chengdu, China)",
      "highlights": [
        "Applied generative AI models to compress information into latent space before transmission and reconstruct it after transmission to conserve communication resources.",
        "Explored underwater semantic communication enhancement by learning from large underwater communication datasets.",
        "Adapted models for complex-valued communication systems (most AI models are designed for real-valued inputs)."
      ]
    },
    {
      "company": "Johns Hopkins University",
      "position": "Research Project Lead — LLMs for Automated Machine Learning",
      "startDate": "2024-02",
      "endDate": "2025-05",
      "summary": "Supervisor: Dr. Yiqing Shen (Baltimore, MD)",
      "highlights": [
        "Led an independent project applying LLMs to automate both discriminative and generative machine learning.",
        "Ran experiments across multiple datasets; the framework performed better in most settings.",
        "Conducted a user study with 25 participants validating usability and convenience.",
        "Authored a paper accepted by IEEE BIBM 2025."
      ]
    }
  ],
  "education": [
    {
      "institution": "UESTC & University of Glasgow",
      "area": "Bachelor of Engineering | Communication Engineering (Joint Program)",
      "studyType": "",
      "startDate": "2022-09",
      "endDate": "2026-07",
      "gpa": "84.9 / 3.73",
      "courses": [
        "Linear Algebra and Space Analytic Geometry (98)",
        "Elements of Information Theory (88)",
        "Introductory Programming (95)",
        "Digital Circuit Design (92)"
      ]
    }
  ],
  "skills": [
    {
      "name": "Programming",
      "keywords": [
        "Python (NumPy, SciPy, Matplotlib, Pandas, PyTorch)",
        "MATLAB",
        "C"
      ]
    },
    {
      "name": "Document Preparation",
      "keywords": [
        "Microsoft Office Suite",
        "LaTeX"
      ]
    }
  ],
  "languages": [
    {
      "language": "English",
      "fluency": "IELTS 7.5"
    }
  ],
  "interests": [
    {
      "name": "Research Interests",
      "keywords": [
        "Large Language Models (LLMs)",
        "Computer Vision"
      ]
    }
  ],
  "references": [],
  "publications": [
    {
      "name": "A Human-Centered Multimodal AutoML Framework for Discriminative and Generative Tasks with Large Language Models",
      "publisher": "IEEE BIBM 2025",
      "releaseDate": "2025-01-29",
      "website": "",
      "summary": "J. Guo, L. Zhang, and Y. Shen."
    }
  ],
  "presentations": [],
  "teaching": [],
  "portfolio": [
    {
      "name": "Automated Pace Tracking Drone",
      "category": "project",
      "date": "2025-01",
      "url": "",
      "description": "Designed and built a fully autonomous drone capable of tracking, object recognition, and object grasping; completed hardware assembly, programming, and validation independently (UESTC, Chengdu)."
    },
    {
      "name": "Mini Smart Home Using Embedded Processor (STM32)",
      "category": "project",
      "date": "2023-04",
      "url": "",
      "description": "Built a smart home prototype using STM32 to sense temperature/luminance/humidity and respond accordingly; independently programmed, built circuits, and tested (UESTC, Chengdu)."
    },
    {
      "name": "Transformer-based Object Classification Model",
      "category": "project",
      "date": "2024-12",
      "url": "",
      "description": "Built a Transformer model to classify 7 object categories; contributed to dataset creation; achieved better performance than peer models (UESTC)."
    },
    {
      "name": "Reviewer, CVPR",
      "category": "activity",
      "date": "2024-12",
      "url": "",
      "description": "Reviewed papers related to medical computer vision frameworks."
    },
    {
      "name": "Champion, College Football Tournament",
      "category": "activity",
      "date": "2022-10",
      "url": "",
      "description": "Recognized as the Champion Class in the tournament."
    },
    {
      "name": "Outstanding Class Committee Member",
      "category": "activity",
      "date": "2023-10",
      "url": "",
      "description": "Granted to class committee members who demonstrated exceptional dedication (also awarded in 2024-10)."
    }
  ]
}
