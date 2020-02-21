---
title: Audio Feature Extraction Toolboxes
link: http://davemoffat.com/wp/index.php/2015/09/18/audio-feature-extraction-toolboxes/
author: admin
description: 
post_id: 70
created: 2015/09/18 09:11:30
created_gmt: 2015/09/18 09:11:30
comment_status: open
post_name: audio-feature-extraction-toolboxes
status: publish
post_type: post
---
# Audio Feature Extraction Toolboxes

I have recently been working on Evaluation of Audio Feature Extraction Toolboxes. I have had a paper accepted to DAFx on the subject. While there are a range of ways to analyse and each feature extraction toolbox, the computational time can be an effective evaluation metric. Especially when people within the MIR community are looking at larger and larger data sets. 16.5 Hours of audio, 8.79Gbs of audio, was analysed, and the MFCC's using eight different feature extraction toolboxes. The computation time for every toolbox was captured, and can be seen in the graph below.

![Time(s) Aubio	742 Essentia	252 jAudio	840 Librosa	3216 LibXtract	395 Marsyas	526 MIR	1868 YAAFE	211](/wp-content/uploads/2015/09/ComputationTime.png)