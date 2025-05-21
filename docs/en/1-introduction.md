---
layout: page
title: BANZ-FS
permalink: /docs/en/introduction
key: docs-introduction
article_header:
  type: cover
  theme: dark
  image:
    src: /docs/assets/images/banzfs_title.png
---


<div>{%- include extensions/youtube.html id='x4ckW_cj8q8' -%}</div>


**Fingerspelling** plays a vital role in sign languages, particularly for conveying names, technical terms, and words not found in the standard lexicon.
However, evaluation  of two-handed fingerspelling detection and recognition is rarely addressed in  existing sign language datasets—particularly for BANZSL (British, Australian, and New Zealand Sign Language), which share a common two-handed manual alphabet.
To bridge this gap, we curate a large-scale dataset, dubbed **BANZ-FS**, focused on BANZSL fingerspelling in both controlled and real-world environments.

Our dataset is compiled from three distinct sources: (1) live sign language interpretation in news broadcasts, (2) controlled laboratory recordings, and (3) diary vlogs from online platforms and social media.
This composition enables BANZ-FS to capture variations in signing tempos and fluency across diverse signers and contents.
Each instance in BANZ-FS is carefully annotated with multi-level alignment: video ↔ subtitles, video ↔ fingerspelled letters, and video ↔ target lexicons.
In total, BANZ-FS includes over 35,000 video-aligned fingerspelling instances.
Importantly, BANZ-FS highlights the unique linguistic and visual challenges posed by two-handed fingerspelling, including handshape coarticulation, self-occlusion, intra-letter variation, and rapid inter-letter transitions.
We benchmark state-of-the-art models on the key tasks, including fingerspelling detection, isolated fingerspelling recognition, and fingerspelling recognition in context.
Experimental results show that BANZ-FS presents substantial challenges while offering rich opportunities for BANZSL understanding and broader sign language technology.
