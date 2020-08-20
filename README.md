# DOT.

## Inspiration:


Everyone has heard of Stephen Hawking. The British physicist was world famous for his work on space and time. So how did a wheelchair-ridden man who could barely move his muscles get around to giving lectures and writing books? Hawking used a speech-generating device developed by Intel that helps with speech/writing for people who have trouble communicating. Inspired by this we created DOT. -an application that converts eye movements to meaningful text and audio which allows disabled people to communicate freely with the rest of the world.

## What it does:


DOT. uses eye movements as sensory input and converts it into meaningful text. The text will be read out loud by the embedded program so people can communicate with others just by blinking their eyes.

## How we built it:
Used a Keras library with Tensorflow backend to train a binary classifier using 'Closed Eyes in the Wild' dataset between open and closed eyes. The data is then being translated into Morse code and is further decrypted into plain text.

## Challenges we ran into:
Converting eye movements to Morse code. The program picked up undesired Morse code segments from real time webcam signals. Eliminating those undesired symbols was one of the greatest challenges we ran into.

## Accomplishments that we're proud of:
Successfully converted eye movements to meaningful text and audio outputs which allow people to communicate by only blinking their eyes.

## What we learned:
Through out the project development, we gained significant experience in training and deploying machine learning models, specifically using Tensorflow.js and Transfer Learning.
