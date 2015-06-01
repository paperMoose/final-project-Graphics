# final-project-Graphics
An interactive webgl implementation of the Boids flocking algorithm using TIE fighters from star wars
Written by Ryan Brandt and Erfan Azad
The program uses webGL and mrdoobs THREE.js package. 
It's contained within a bounding sphere with its interior texture mapped to an image of the sky, which provides a nice sky environment 
for the TIE fighters to fly around in. Each fighter moves based the movements of it's neighbors around it. 
The default is for the fighter to have access to all the other fighters velocities, 
but by toggling neighboring to on a fighter will only be able to access info from it's immediate neighbors, 
leading to multiple clusters. Please let us know what you think!
