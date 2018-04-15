# BuildHer 2018

## LiveStreamCap
An application that captions your livestream on the go
### Inspiration
All of us wanted to explore google cloud platform & machine learning tools, as we had never worked extensively with either of these things. We decided to take machine learning to video and see how we could apply available resources.

### What it does
As you are livestreaming (or maybe even FaceTiming) from your computer, your words will be captioned in real-time. This provides potential accessibility to hard of hearing users or users with different native languages (where we could apply a quick translation on the captions). Such a tool serves to enhance virtual communication.

### How we built it
We used the opencv package in python in order to capture the user's video directly from their camera. From there, we used the sounddevice package to extract audio in realtime. Finally, we decided to apply the google cloud platform speech to text API on every two-five seconds of audio in order to display the translations on the video.

### What's next for LiveStreamCap
We hope to make it less laggy and to be able to display the text in a slightly prettier fashion.

## SoundBleps
Do you ever feel bored out of your mind? Well, don't worry, this is an app for YOU!
### Inspiration
We hit a rut on our video-captioning project, and from there... we decided to mess around with the sound we had captured. Now, you can record yourself and your friends and come out with a fleek new track of your own making. Want to recite Hamlet? Belt out Taylor Swift? Rap some Kendrick? Now you get a combo of all three (even if you didn't ask for it.)

### What it does
It captures your conversation and mixes it into a sick beat.

### How we built it
We used python, opencv (for the video) and sounddevice (for the audio). Then, we used numpy to shuffle our tracks.

### What's next for SoundBleps
Can we make an EDM soundBlep? Tune in, next hackathon!
