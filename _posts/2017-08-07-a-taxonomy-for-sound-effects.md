---
title: Sound Effects Taxonomy
link: http://davemoffat.com/wp/index.php/2017/08/07/a-taxonomy-for-sound-effects/
author: admin
description: 
post_id: 258
created: 2017/08/07 12:17:57
created_gmt: 2017/08/07 12:17:57
comment_status: open
post_name: a-taxonomy-for-sound-effects
status: publish
post_type: post
---

# Sound Effects Taxonomy

At the upcoming[ International Conference on Digital Audio Effects](https://dafx17.eca.ed.ac.uk/), I will be presenting my recent work on creating a sound effects taxonomy using unsupervised learning. A link to the paper [can be found here.](https://dafx17.eca.ed.ac.uk/papers/DAFx17_paper_26.pdf)

A taxonomy of sound effects is useful for a range of reasons. Sound designers often spend considerable time searching for sound effects. Classically, sound effects are arranged based on some key word tagging, and based on what caused the sound to be created - such as bacon cooking would have the name "BaconCook", the tags "Bacon Cook, Sizzle, Open Pan, Food" and be placed in the category "cooking". However, most sound designers know that the sound of frying bacon can sound very similar to the sound of rain ([See this TED talk for more info](https://www.ted.com/talks/tasos_frantzolas_everything_you_hear_on_film_is_a_lie)), but rain is in an entirely different folder, in a different section of the SFx Library.

Our approach, is to analyse the raw content of the audio files in the sound effects library, and allow a computer to determine which sounds are similar, based on the actual sonic content of the sound sample. As such, the sounds of rain and frying bacon will be placed much closer together, allowing a sound designer to quickly and easily find related sounds that relate to each other.

A full run down of the work is present on the [Intelligent Audio Engineering Blog](http://intelligentsoundengineering.wordpress.com/2017/08/30/sound-effects-taxonomy/)