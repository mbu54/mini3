## Mini Project 3: Demonstration of POPPY python package

I collabroated with Jenny Campbell on the demostration of POPPY with approval from Prof. Osama

### What is POPPY?

POPPY (Physical Optics Propagation in PYthon) is a python package that can be used to simulate light propagtion. POPPY is primarily designed for astronomical telescope applications but can be used for more imaging applications. Fraunhofer and Fresnel diffraction can be modeled in this package.

### What is the appeal of POPPY?

Most software used for optical modeling and light propagation is very expensive and so there is limited access to this software. POPPY is free open source software that has been consistently updated (last update in Nov. 2019) and was designed for the NASA James Webb Space Telescope (JWST) so it has been used for simulations to design real telescopes. POPPY must must be a robust python package to use for designing something as expensive as a telescope. POPPY has commonly used apertures and pupils as well as other imaging elements that can be used to model imaging systems. There is also the capability to make custom elements and use them your imaging system.

### What are the problems with POPPY?

POPPY is very coputational heavey like most imaging software. When trying to the run the package on my computer it would crash, because I didn't have enough memory. When working with Jenny Campbell we were able to get POPPY to run the computations on her computer. 

### Demo

POPPY was used to make two different apertures and display the resulting point spread functions (PSF) for the resulting apretures. The first aperture was a simple circular aperture (not displayed). The resulting PSF can be seen in the image below, which displays the the expected airy pattern for circular apertures.

<p align="middle"><img src="https://github.com/mbu54/mini3/blob/master/example_airy.png" align="middle" style="width:200px;height:200px;"></p>

For the next demo a complex hexagon based aperture was created. Hexagons are commonly used in telescope designs. The pupil for this design can be seen in the image below. 

<p align="middle"><img src="https://github.com/mbu54/mini3/blob/master/example_atlast_pupil.png" align="middle" style="width:200px;height:200px;"></p>

The PSF was found for the pupil and is displayed in the below image. 

<p align="middle"><img src="https://github.com/mbu54/mini3/blob/master/example_atlast_psf.png" align="middle" style="width:200px;height:200px;"></p>

The PSF for this image is very complex which motivates the need for having software that can model complex imaging systems.

### POPPY website:

https://poppy-optics.readthedocs.io/en/stable/
