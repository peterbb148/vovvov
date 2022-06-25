# Project VovVov

## Introduction

My neighbour has a small dachshound and it will bark at anything, everyone and all the time. They get up at 06 every day of the week and let the dog out in the yard where it will bark until it gives up and walks back inside.

I've tried many times to ask them to control the barking but am always met with hostility and back excuses like there was a fox in the garden (but explanation about how the fox got in while at the same time the dachhound is not able to get out.

Anyway - I've given up trying to ask them to silence the dog, so I thought I'd build something that can detect if a dog is barking and then use machine learning to detect if it's my neighbours dog and if so then post the number of barks and time somewhere.

## Overall Solution

So far this is a bit sketchy but I'm imagining something like this:

'''mermaid
graph TD
    A[Bark] -->|Get money| B(Record)
    B --> C{Is neighbour dog?}
    C -->|Yes| D[Post to Twitter]
    C -->|No| E[nothing]
'''
