# FlappyPlane

Here you can experience flying with boids...

https://user-images.githubusercontent.com/109744044/201940932-9426f347-6fd7-4e30-ac4f-2964c3cb1ed2.mp4

Boids for the uninitiated are bird-oid type objects. Groups of objects that demonstrated swarming behaviour such as the murmurations of the starlings.

Using the most simple rules available one can create something like what you can observe in the video. This implementation solely uses cohesion, allignment and separation to govern the behaviour of the birds with the player is allowed to add a greater weight to their positional information thus acting as a group leader.

https://user-images.githubusercontent.com/109744044/201939825-1d70af40-1969-47b9-bfd7-8174a1fb2710.mp4

This however leaves plenty of room for experimentation and improvement. Using raycasting you can further teach boids to avoid objects, this could probably also be achieved by adding a higher weight when calculating separation values in relation to obstacles much like the player has been allowed greater influence for directing the crowd.

Further still, some clever folk have modelled the dispersion of pheromones through the swarm to increase the realism of their models. I might like to add a sense of fear to the birds so they escape from potential danger and behave erratically when doing so. As far you can see there are some gameplay elements not being demonstrated in these videos including the timer, strange orbs and points. This is simply due to the changing nature of the project. The game is intended to be played not using a keyboard but in fact using gyroscope readings from a hand held device. If this doesn't stir the imagination I don't know what does, boids, physical movement and points, what will come from such experimentation?

