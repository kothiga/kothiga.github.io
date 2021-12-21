---
title: "Speech envelope dynamics for noise-robust auditory scene analysis in robotics"
pub_id: 4
date: 2021-01-21
layout: single
permalink: /pubs/IJHR_2021_Speech_envelope
feature_row:
  - url: https://www.worldscientific.com/doi/abs/10.1142/S0219843620500231
    image_path: /assets/images/preview/banner_2021_ijhr.png
    alt: "International Journal of Humanoid Robotics"
    btn_label: "Download Paper"
    btn_class: info
gallery_robots:
  - url:        /assets/images/pubs/IJHR_2021/icub_iit.png
    image_path: /assets/images/pubs/IJHR_2021/icub_iit.png
    alt:        "iCub robot at the Italian Institute of Technology"
    title:      "iCub robot at the Italian Institute of Technology"
  - url:        /assets/images/pubs/IJHR_2021/icub_leth.png
    image_path: /assets/images/pubs/IJHR_2021/icub_leth.png
    alt:        "iCub head at the University of Lethbridge"
    title:      "iCub head at the University of Lethbridge"
gallery_model_1:
  - url:        /assets/images/pubs/IJHR_2021/model_features.png
    image_path: /assets/images/pubs/IJHR_2021/model_features.png
    alt:        "Processing pipeline for extracting features from the input audio"
    title:      "Processing pipeline for extracting features from the input audio"
gallery_model_2:
  - url:        /assets/images/pubs/IJHR_2021/model_bayes.png
    image_path: /assets/images/pubs/IJHR_2021/model_bayes.png
    alt:        "Processing pipeline for computing Bayesian updates of probable sound source"
    title:      "Processing pipeline for computing Bayesian updates of probable sound source"
gallery_room_layout:
  - url:        /assets/images/pubs/IJHR_2021/room_layout_1.png
    image_path: /assets/images/pubs/IJHR_2021/room_layout_1.png
    alt:        "Room layout for experiments"
    title:      "Room layout for experiments"
  - url:        /assets/images/pubs/IJHR_2021/room_layout_2.png
    image_path: /assets/images/pubs/IJHR_2021/room_layout_2.png
    alt:        "Room layout for experiments"
    title:      "Room layout for experiments"
  - url:        /assets/images/pubs/IJHR_2021/room_layout_3.png
    image_path: /assets/images/pubs/IJHR_2021/room_layout_3.png
    alt:        "Room layout for experiments"
    title:      "Room layout for experiments"
gallery_overtime:
  - url:        /assets/images/pubs/IJHR_2021/pink_amp_overtime.png
    image_path: /assets/images/pubs/IJHR_2021/pink_amp_overtime.png
    alt:        "Localization of a human voice among a pink noise distraction using an amplitude based approach"
    title:      "Localization of a human voice among a pink noise distraction using an amplitude based approach"
  - url:        /assets/images/pubs/IJHR_2021/pink_env_overtime.png
    image_path: /assets/images/pubs/IJHR_2021/pink_env_overtime.png
    alt:        "Localization of a human voice among a pink noise distraction using an envelope based approach"
    title:      "Localization of a human voice among a pink noise distraction using an envelope based approach"
gallery_envelope:
  - url:        /assets/images/pubs/IJHR_2021/representative_wav_envelope.png
    image_path: /assets/images/pubs/IJHR_2021/representative_wav_envelope.png
    alt:        "Representative audio signal with the low-frequency envelope overplotted in red"
    title:      "Representative audio signal with the low-frequency envelope overplotted in red"
  - url:        /assets/images/pubs/IJHR_2021/voice_pink_urban_periodograms.png
    image_path: /assets/images/pubs/IJHR_2021/voice_pink_urban_periodograms.png
    alt:        "The average low-frequency envelope periodograms of the speech samples used in experiments"
    title:      "The average low-frequency envelope periodograms of the speech samples used in experiments"
---

Rea F., **Kothig A.**, Grasse L., Tata M. <br /> Published in *International Journal of Humanoid Robotics 2021 (IJHR)* 

<a href="https://www.worldscientific.com/worldscinet/ijhr">
<img width="25%" src="../../assets/images/conferences/ijhr2021.png">
</a>


### Abstract
<div style="text-align: justify">
Humans make extensive use of auditory cues to interact with other humans, especially in challenging real-world acoustic environments. Multiple distinct acoustic events usually mix together in a complex auditory scene. The ability to separate and localize mixed sound in complex auditory scenes remains a demanding skill for binaural robots. In fact, binaural robots are required to disambiguate and interpret the environmental scene with only two sensors. At the same time, robots that interact with humans should be able to gain insights about the speakers in the environment, such as how many speakers are present and where they are located. For this reason, the speech signal is distinctly important among auditory stimuli commonly found in human-centered acoustic environments. In this paper, we propose a Bayesian method of selectively processing acoustic data that exploits the characteristic amplitude envelope dynamics of human speech to infer the location of speakers in the complex auditory scene. The goal was to demonstrate the effectiveness of this speech-specific temporal dynamics approach. Further, we measure how effective this method is in comparison with more traditional methods based on amplitude detection only.
</div>


### Images
{% include gallery id="gallery_robots" layout="half" caption="iCub humanoid robot." %}
{% include gallery id="gallery_model_1" caption="Processing pipeline for extracting features from the input audio." %}
{% include gallery id="gallery_model_2" caption="Processing pipeline for computing Bayesian updates of probable sound source." %}
{% include gallery id="gallery_room_layout" layout="third" caption="Room layout for experiments." %}
{% include gallery id="gallery_overtime" layout="half" caption="Localizing a human voice with a single distractor present. Left uses an Amplitude-Only approach, while right is filtering for the Envelope-Dynamics. The white track denotes the angular position of the head over time." %}
{% include gallery id="gallery_envelope" layout="half" caption="Representative audio signal with the low-frequency envelope and the average low-frequency envelope periodograms of the audio samples." %}

---

### How to cite?

```
@article{rea2021speech,
  title={Speech envelope dynamics for noise-robust auditory scene analysis in robotics},
  author={Rea, Francesco and Kothig, Austin and Grasse, Lukas and Tata, Matthew},
  journal={International Journal of Humanoid Robotics},
  volume={17},
  number={06},
  pages={2050023},
  month={January},
  year={2021},
  publisher={World Scientific},
  url={http://dx.doi.org/10.1142/S0219843620500231}, 
  DOI={10.1142/s0219843620500231}
}
```
---

### Downloads

{% include feature_row %}
