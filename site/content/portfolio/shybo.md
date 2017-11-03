+++
image = "shybo.jpg"
showonlyimage = false
draft = false
date = "2017-11-05T19:53:42+05:30"
title = "Shybo"
weight = 1
width= 4
category= "research"
featured="yes"
+++
<!--more-->

"It is a small and shy robot, very curious about the sounds that surround it.  However it doesn’t know how to interpret these sounds that it perceives. It is just scared from too noisy sounds. So, it needs some help to discover and learn from the world around it. Children can help and guide SHYBO in this discovery of sounds."

SHYBO is part of a research project about the theme of child-robot play, developed in China, in collaboration with Haipeng Mi, Yuan Yao, and Jing Gao, at [X-Studio](http://www.x-studio.org.cn), Tsinghua University.

The aim of this research is to understand how technology is affecting the role of play in children’s everyday life and to define new meaningful scenarios of play. In particular, Shybo is designed to let children play with sound-color associations and to promote their own reasoning.

<iframe src="https://player.vimeo.com/video/233640805" width="1024" height="526" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p><a href="https://vimeo.com/233640805">Shybo Functioning</a> from <a href="https://vimeo.com/user66117537">Maria Luce Lupetti</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

![SHYBO components and design](/assets/img/shyboinside.jpg)

SHYBO’s current prototype consist of an Arduino Pro Mini board that take data from sensors (potentiometer, button, and switch) and controls a micro-servo and addressable led strips. The Arduino board communicate via Bluetooth with a laptop used to run a sound-analysis middleware, developed in Processing by [Lorenzo Romagnoli](http://lorenzoromagnoli.me) and [Wekinator](http://www.wekinator.org), a machine learning software for classification. The middleware is used as sound analysis' tool and as communication bridge. It receives input data from the Arduino, such as start recording, change class, and change mode, and forward them to the Wekinator via OSC (Open Sound Control). It also receives data from the Wekinator, which runs the trained model and send out the info about the classes.

SHYBO enabled to design a playful learning experience focused on fundamentals of color theory. The experience includes the use of a board game and game cards, that requires to player to obtain certain colors on the robot by playing sounds. Since the robot has no preset color-sound associations, children have to train the robot before playing the game.

<iframe src="https://player.vimeo.com/video/227591676" width="1024" height="526" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p><a href="https://vimeo.com/227591676">A playtest with Shybo.</a> from <a href="https://vimeo.com/user66117537">Maria Luce Lupetti</a> on <a href="https://vimeo.com">Vimeo</a>.</p>


Shybo is at the basis of an ongoing project called OpenAnimates. The project consists of playful learning activities with small robots, like Shybo, developed in collaboration with [Lorenzo Romagnoli] (http://lorenzoromagnoli.me), creative technologist, and Annalisa Gallo, manager of [10100 Percorsi] (https://10100percorsi.com). The idea is to extend the concept of trainable robots that guided the development of Shybo, for co-designing creative and playful learning experiences related to school's curricular program. The first experimental activity will be carried out at the end of November 2017, in Turin, Italy.


Publications about the project:

[Design for Children’s Playful Learning with Robots](http://www.mdpi.com/1999-5903/9/3/52)

[Shybo. An open-source low-anthropomorphic robot for children](http://www.sciencedirect.com/science/article/pii/S246806721730038X)

[Design for Learning Through Play. An Exploratory Study on Chinese Perspective](https://link.springer.com/chapter/10.1007/978-3-319-57931-3_45)
