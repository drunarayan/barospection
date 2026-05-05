### Determining Star Types Assignment Notes

![](computers.png)


Knowing a star's distance defeats the purpose of this exercise. It is intended to walk in the footsteps of astronomers like [Williamina Fleming](https://en.wikipedia.org/wiki/Williamina_Fleming), [Annie Jump Cannon](https://en.wikipedia.org/wiki/Annie_Jump_Cannon), [Cecilia Payne-Gaposchkin](https://en.wikipedia.org/wiki/Cecilia_Payne-Gaposchkin), and other "Computers" (women hired to analyze astronomical data, long before the term referred to machines).

The Harvard work flow looked something like this:

It is important to realize that when astronomers led by Pickering at Harvard set out to establish the [cosmic distance ladder](https://en.wikipedia.org/wiki/Cosmic_distance_ladder), all they could measure from stars was their electromagnetic radiation -- specifically three things: 

    - Star Brightness (visual magnitude) 
    - Spectral Energy Distribution profiles (by analyzing the spectra of thousands of stars)
    - Periods of Cepheid variable stars (a method pioneered by [Henrietta Swan Leavitt](https://en.wikipedia.org/wiki/Henrietta_Swan_Leavitt)).

Most significantly, the distance -- and therefore the Absolute Magnitude -- was not known for most stars. There was no Gaia satellite then either.
For a handful of nearby stars, astronomers could calculate distance using visual parallax: measuring the apparent shift in a star’s position as the Earth orbits the Sun, using that orbit as the baseline of a triangle.
They then checked whether any of those parallax-measured stars belonged to the Hyades cluster, which is relatively close to Earth. The key advantage: all stars in a cluster are at essentially the same distance from us, so the distance measured for one applies to all.
With both apparent (visual) magnitude and parallax distance in hand, astronomers could calculate each star’s Absolute Magnitude -- its true luminosity or power output. 

For stars with known parallax, they could now plot both axes of the HRD: the x-axis (color, temperature, spectral type) and the y-axis (Absolute Magnitude). This gave them a calibrated diagram with real physical meaning. 
This is the foundation of the Spectroscopic Parallax method -- a technique for estimating a star’s distance using only its spectrum and where it falls on the HRD. (These equations were derived from first principles in my first seminar, and HRD plots were created for several clusters, including the Hyades, clearly showing the Main Sequence and the luminosity classes.)
They then compared distances derived from visual parallax with those derived from spectroscopic parallax for stars in the Hyades cluster -- and confirmed the two methods agreed. This validation was the critical step in building the cosmic distance ladder. <br><br> What it meant was profound: for any unknown star, you only need to know its spectral type (the x-axis) and its luminosity class (which band of the HRD it falls in) to estimate its Absolute Magnitude, and from that, its distance. 
The method itself is elegant. Draw a vertical line at the star’s spectral type. Find where it intersects the appropriate Main Sequence or luminosity class line. Then draw a horizontal line across to read off the Absolute Magnitude. Distance follows directly. Brilliant.

### Your Assignment

This is exactly the method I want you to follow in the final project. We will discuss it in detail throughout this seminar.
For now, we are just getting practice. Using your 5 assigned stars, estimate the star type and approximate temperature by making educated guesses from the SED (spectral energy distribution) profile in your analyzed FITS image. Do this by examining the absorption lines: their width, depth, and the elements they correspond to, comparing against standard wavelengths for Hydrogen, Helium, Magnesium, Sodium, Calcium, Titanium Oxide, and similar species.
Do not use distance -- assume it is unknown. If you watched the full video for this assignment, you will notice that we never once mentioned a star’s distance or Absolute Magnitude when determining star type. That is the key point.