---
layout: post
title: GMR based non-invasive Respiration Rate monitor
categories:
- blog
---

This project was an extension of the project aiming at Heart Rate (HR) monitor developement using Giant Magneto Resistance (GMR) sensor under guidance of [Prof. Anoop C.S.](https://www.iist.ac.in/avionics/anoop.cs). While experimenting with Pass-band frequencies of analog conditioning circuit for HR estimation, we observed a low frequency signal coupling with HR signal. Which on further investigation was found to be Respiration signal.

I worked on signal processing in digital domain using Arduino-uno to give real-time estimation of Respiration Rate (RR) along with HR using Fast fourier Transform (FFT) implementation. A working prototype was developed and was verified alongside waveforms observed from standard air-flow meter. We performed accuracy testing of the prototype on 20 volunteers and found accuracy of upto 2 breadths per minute. The results of experimentation were published in proceedings of 38th Annual International Conference of the IEEE Engineering in Medicine and Biology Society [(EMBC)](#) and can be accessed [here](https://ieeexplore.ieee.org/document/7591196).

### Action Shots
![](https://github.com/chughvinit/chughvinit.github.io/blob/master/_RR/IMG_20160314_215650228.jpg)
![](https://github.com/chughvinit/chughvinit.github.io/blob/master/_RR/IMG_20181101_153400.jpg)

<!--
Tattooed roof party *vinyl* freegan single-origin coffee wayfarers tousled, umami yr 
meggings hella selvage. Butcher bespoke seitan, cornhole umami gentrify put a bird 
on it occupy trust fund. Umami whatever kitsch, locavore fingerstache Tumblr pork belly
[keffiyeh](#). Chia Echo Park Pitchfork, Blue Bottle [hashtag](#) stumptown skateboard selvage 
mixtape. Echo Park retro butcher banjo cardigan, seitan flannel Brooklyn paleo fixie 
Truffaut. Forage mustache Thundercats next level disrupt. Bicycle rights forage tattooed
chia, **wayfarers** swag raw denim hashtag biodiesel occupy gastropub!

---

# It's all in the game.

## You come at the king, you best not miss.

### Be subtle with it, man. You know what subtle means?

VHS post-ironic cred **bespoke** banjo. Yr wayfarers literally gentrify, flexitarian fap 
dreamcatcher plaid cornhole Intelligentsia paleo. Beard try-hard direct trade, shabby chic 
Helvetica `look ma, I can code`. Lo-fi American Apparel tattooed [Vice](#) tofu, yr vinyl. 
Williamsburg butcher hella mumblecore fixie mlkshk, cliche wolf keytar mixtape kitsch banh mi 
salvia. High Life Odd Future *chambray* kale chips hoodie, cray pop-up. Helvetica narwhal 
iPhone try-hard jean shorts.

> This is a quote from someone famous about productivity


Syntax highlighting with Solarized theme.

{% highlight ruby %}
class User < ActiveRecord::Base
  attr_accessible :email, :name

  ... tons of other crap ...

end

{% endhighlight %}
-->
