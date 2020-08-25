<p align="center">
 <img src="https://img.itch.zone/aW1nLzM0NDY5MTEucG5n/original/H3Rt8p.png" >
</p>

# FlappyBirdAI
###### Creating an AI that is able to play Flappy Bird

 ## Background
I was around 12 when Flappy Bird was released and I remember it being the biggest thing at my school. Everyone was competing against each other which any chance they got whether that be between classes, break time, during lunch or even on the bus. At the time I had just recieved my fathers old iPhone 4 which was able to run the game. It shocked me that a game so simple could get so many people hooked onto it. I also remember the disruption caused when Flappy Bird was taken off the app store. Back then I didn't know any programming but looking back on it now I can see why people who would so fixated on becoming the best. This project was for me to learn how to make games using Pygame. I have tried a few other projects using Pygame however this project allowed me to make something I was very interested in. However I saw a tutorial online looking at intergrating a AI that can learn to play Flappy Bird through different generations. For those who know me, I have been interested in AI and ML alot over the past few years and this summer I have endevaoured to start experimenting with it. This is one of (hopefully) many more projects I hope to make in the future that implement AI in different applications. I also want to experiment with how to make AI better and try different techniques and this is one of the ways I shall go about this.

## Technolgies used:
1. Python
2. NEAT-Python
3. Pygame

# NEAT-Python
- <b>Inputs</b> into NN (Neural Network) = bird_y, top_pipe, bottom_pipe (Potential for just one pipe however both pipes will speed up training time of NN)
- <b>Outputs</b> of NN = bird_jump
- <b>Activation Function</b> = Tan(H)  (Value will be between 1 and -1 which helps us determine if we jump or not)
- <b>Population Size</b> = (Gen 0 = 100) -> (Gen 1 = 100)
- <b>Fitness Function</b> (How do we evaluate which bird is the best) = distance (which bird makes it the furthest)
- <b>Max Generations</b> = 30

