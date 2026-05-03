# Real Time Control of Virtual Orchestra by Recognition of Conducting Gestures 

<div align="center">

**[Mert Mermerci](mailto:mermerci@kth.se)**<sup>1</sup>,
**[Emile Pascoe](mailto:emile@smash.studio)**<sup>2</sup>,
**[Fredrik Edström](mailto:fredrik@ivar.studio)**<sup>3</sup>,
**[Hedvig Kjellström](mailto:hedvig@kth.se)**<sup>1,4</sup>

<sup>1</sup> KTH Royal Institute of Technology, Sweden &nbsp;
<sup>2</sup> SMASH Studios, Sweden &nbsp;
<sup>3</sup> IVAR Studios, Sweden &nbsp;
<sup>4</sup> Swedish e-Science Research Centre, Sweden

[comment]: <> (Conference / Journal Name · Year)

[![arXiv](https://img.shields.io/badge/arXiv-2604.27957-b31b1b?style=flat)](https://arxiv.org/abs/2604.27957)
[![Dataset](https://img.shields.io/badge/Dataset-Download-blue?style=flat)](https://your-dataset-link.com)

</div>

---

![Teaser](assets/teaser.png)

---

## Abstract

We present a museum installation in a 180° dome theater, which gives the museum visitor the experience of conducting a symphony orchestra. We have pre-recorded a short music piece performed by a professional orchestra. This recording is played back in the dome with the visitor standing in the conductor's position. The visitor's gestures are captured with a vision-based skeleton tracker, steering the recording playback pace via a gesture recognition module that translates the gestures into a time control signal. This is sent to a playback module that plays the recording in the dome at the corresponding speed. The gesture recognition module is based on a hierarchical LSTM network, trained with recorded sequences of multiple conductors with different level of expertise conducting the same recording. The system is evaluated with a quantitative study of the estimated timing accuracy, a user study evaluating the musical realism and usability of the real-time control, and a field study to evaluate the performance of the entire system with real museum visitors.

---

## Video

### Advertisement Video in the Wisdome Dome Theater.

This video is created for the advertisement of the installation premierred in Wisdome Dome Theater on 07/09/2025. It shows scenes from both the preperation, demoing instances and public trying the installation. 

> Local video file — `assets/demo1.mp4`


### Sveriges Radio  

This is the Facebook post from Sveriges Radio. It shows an interview with a child and chief conductor David Björkman who also supported the project during the development phase. 

> Facebook video — embedded from https://www.facebook.com/share/r/167DfQiKNi/

---

## BibTeX

```bibtex
@misc{mermerci2026realtimecontrolvirtualorchestra,
      title={Real-Time Control of a Virtual Orchestra by Recognition of Conducting Gestures}, 
      author={Mert Mermerci and Emile Pascoe and Fredrik Edström and Hedvig Kjellström},
      year={2026},
      eprint={2604.27957},
      archivePrefix={arXiv},
      primaryClass={cs.HC},
      url={https://arxiv.org/abs/2604.27957}, 
}
```

---

<div align="center">
  This webpage template is adapted from <a href="https://github.com/nerfies/nerfies.github.io">Nerfies</a>,
  under a <a href="http://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0 License</a>.
</div>
