---
title: "Connecting humans and robots using physiological signals -- closing-the-loop in HRI"
pub_id: 6
date: 2021-08-08
layout: single
permalink: /pubs/RO-MAN_2021_Connecting_humans
feature_row:
  - url: https://ieeexplore.ieee.org/document/9515383
    image_path: /assets/images/preview/banner_2021_ro-man.png
    alt: "Robot and Human Interactive Communication 2021"
    btn_label: "Download Paper"
    btn_class: info
gallery_arch:
  - url:        /assets/images/pubs/RO-MAN_2021/architecture.png
    image_path: /assets/images/pubs/RO-MAN_2021/architecture.png
    alt:        "Overview of the HRI Physio Lib. Color code explanation of the categories per each component as follows: purple--body process, yellow--hardware elements, grey/white--software elements with its individual components, and blue--data or information flow"
    title:      "Overview of the HRI Physio Lib. Color code explanation of the categories per each component as follows: purple--body process, yellow--hardware elements, grey/white--software elements with its individual components, and blue--data or information flow"
gallery_qt_coach:
  - url:        /assets/images/pubs/RO-MAN_2021/qt_resting.png
    image_path: /assets/images/pubs/RO-MAN_2021/qt_resting.png
    alt:        "Calibration phase of the exercise scenario. The QT robot plays relaxing music and videos while collecting the participants heart rate for three minutes to compute the resting heart rate"
    title:      "Calibration phase of the exercise scenario. The QT robot plays relaxing music and videos while collecting the participants heart rate for three minutes to compute the resting heart rate"
  - url:        /assets/images/pubs/RO-MAN_2021/qt_exercise.png
    image_path: /assets/images/pubs/RO-MAN_2021/qt_exercise.png
    alt:        "Conditioning phase of the exercise scenario. The QT robot leads the participant through a variety of cardio activities with an aerobic step platform"
    title:      "Conditioning phase of the exercise scenario. The QT robot leads the participant through a variety of cardio activities with an aerobic step platform"
gallery_hr_time:
  - url:        /assets/images/pubs/RO-MAN_2021/hr_time.png
    image_path: /assets/images/pubs/RO-MAN_2021/hr_time.png
    alt:        "Change in heart rate (beats per minute - BPM) over time (minutes) of exercising with the QT Cardio-Aware Coach. Green shaded region between 125.2 (HRR_40) and 155.1 (HRR_70) BPM shows the target heart rate zone of the participant. The HR_max for our participant was 184.9 BPM and the HR_rest was 85.4 BPM. Top shows the four phases of the exercise experiment. With the exception of the calibration phase, times that do not have an orange box the participant was instructed to perform a basic marching exercise. The activities used were: (a1) step-up reach and pull; (a2) lateral knees; (a3) both arms forward"
    title:      "Change in heart rate (beats per minute - BPM) over time (minutes) of exercising with the QT Cardio-Aware Coach. Green shaded region between 125.2 (HRR_40) and 155.1 (HRR_70) BPM shows the target heart rate zone of the participant. The HR_max for our participant was 184.9 BPM and the HR_rest was 85.4 BPM. Top shows the four phases of the exercise experiment. With the exception of the calibration phase, times that do not have an orange box the participant was instructed to perform a basic marching exercise. The activities used were: (a1) step-up reach and pull; (a2) lateral knees; (a3) both arms forward"
---

**Kothig A.**, Muñoz J., Akgun SA., Aroyo AM., Dautenhahn K. <br /> Published in *IEEE International Conference on Robot and Human Interactive Communication '30. 2021 (RO-MAN)*

<a href="https://ro-man2021.org/">
<img width="25%" src="../../assets/images/conferences/ro-man2021.png">
</a>


### Abstract
<div style="text-align: justify">
Technological advancements in creating and commercializing novel unobtrusive and wearable physiological sensors generate new opportunities to develop adaptive human-robot interaction (HRI) scenarios. Detecting complex human states such as engagement and stress when interacting with social agents could bring numerous advantages to create meaningful interactive experiences. Despite being widely used to explain human behaviors in post-interaction analysis with social agents, using bodily signals to create more adaptive and responsive systems remains an open challenge. This paper presents the development of an open-source, integrative, and modular library created to facilitate the design of physiologically adaptive HRI scenarios. The HRI Physio Lib streamlines the acquisition, analysis, and translation of human body signals to additional dimensions of perception in HRI applications using social robots. The software framework has four main components: signal acquisition, processing and analysis, social robot and communication, and scenario and adaptation. Information gathered from the sensors is synchronized and processed to allow designers to create adaptive systems that can respond to detected human states. This paper describes the library and presents a use case that uses a humanoid robot as a cardio-aware exercise coach that uses heartbeats to adapt the exercise intensity to maximize cardiovascular performance. The main challenges, lessons learned, scalability of the library, and implications of the physio-adaptive coach are discussed.
</div>


### Images
{% include gallery id="gallery_arch" caption="Overview of the HRI Physio Lib. Color code explanation of the categories per each component as follows: purple--body process, yellow--hardware elements, grey/white--software elements with its individual components, and blue--data or information flow." %}
{% include gallery id="gallery_qt_coach" layout="half" caption="Left, calibration phase of the exercise scenario. The QT robot plays relaxing music and videos while collecting the participants heart rate for three minutes to compute the resting heart rate. Right, conditioning phase of the exercise scenario. The QT robot leads the participant through a variety of cardio activities with an aerobic step platform." %}
{% include gallery id="gallery_hr_time" caption="Change in heart rate (beats per minute - BPM) over time (minutes) of exercising with the QT Cardio-Aware Coach. Green shaded region between 125.2 (HRR_40) and 155.1 (HRR_70) BPM shows the target heart rate zone of the participant. The HR_max for our participant was 184.9 BPM and the HR_rest was 85.4 BPM. Top shows the four phases of the exercise experiment. With the exception of the calibration phase, times that do not have an orange box the participant was instructed to perform a basic marching exercise. The activities used were: (a1) step-up reach and pull; (a2) lateral knees; (a3) both arms forward." %}

---

### How to cite?

```
@inproceedings{kothig2021connecting, 
    title={Connecting Humans and Robots Using Physiological Signals -- Closing-the-Loop in {HRI}}, 
    author={Kothig, Austin and Mu{\~n}oz, John and Akgun, Sami Alperen and Aroyo, Alexander M. and Dautenhahn, Kerstin},
    booktitle={2021 30th IEEE International Conference on Robot and Human Interactive Communication (RO-MAN)}, 
    publisher={IEEE}, 
    month={August},
    year={2021}, 
    url={http://dx.doi.org/10.1109/RO-MAN50785.2021.9515383}, 
    DOI={10.1109/ro-man50785.2021.9515383}
}
```
---

### Downloads

{% include feature_row %}
