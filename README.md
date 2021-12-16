# gravity_assist
N-body gravity simulation. Link: https://gravitysimulation-ac648.web.app/

## How to use the application


## Initial condition cases

### Kepler orbit - circle
The first 4 cases demonstrate the 4 types of Kepler orbits. For the circular orbit, the initial velocity of the smaller mass should be set such that the centrigual force is equal to the gravitational force it experiences.

### Kepler orbit - ellipse
To make the orbit elliptical, increase the initial velocity of the smaller mass so that the eccentricity of the orbit is > 0 but < 1.

### Kepler orbit - parabola
The transition from elliptical to parabolic orbit means that the smaller mass has the enough energy to escape the gravitational potential trap of the larger mass. Thus, set the initial velocity of the former equal to its escape velocity, namely the velocity at which its kinetic energy is equal to potential energy.

### Kepler orbit - hyperbola
Increasing the kinetic energy of the smaller mass even further makes the orbit of it less affected by the gravity of the larger mass.

### Binary system with equal masses
Stable binary stars with equal masses revolving around the center of mass.

### 3-body with equal masses
3 bodies with equal masses revolve around the center of mass in a rotating-equilateral-triangle fashion. Remains stable until numerical errors accumulate and render the system unstable.

### Stable 3-body with a dominant binary system
Another way to make a 3-body system stable is to create a dominant binary system and have a satellite star orbits around it.

### 3-body with satellite star being too close to the binary system
In many cases, we are interested in the dynamics of the satellite star in the above case. For example, we may be interested in the habitability of a planet in a stellar system. If this is the case, meaning that we want to find out the stability of the trajectory of the satellite star, then the distance between it and the dominant binary system is an important factor to consider.

### 4-body with satellite stars being too close to each other
In addition to the distance between the dominant binary stars and the satellite star that we are interested in, the distances between the latter and other satellite stars in the stellar system are also crucial. Essentially, when investigating the trajectory stability of such a satellite star, we can model the gravitional attraction of the binary stars as the dominant driving force and the gravitational attractions of other satellite stars as perturbations. When the distances between satellite stars are close, the perturbations become significant enough to affect the trajectory stability of the interested satellite star.
