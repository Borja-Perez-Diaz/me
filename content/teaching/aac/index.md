---
title: Astrophysics and Cosmology
summary: Handnotes for bachelor students. WARNING underconstruction!
date: 2025-09-02
type: docs
math: true
tags:
  - Astronomy
  - Astrophysics
  - Cosmology
image:
  caption: 'JWST NIRCam view of planetary nebula NGC 6072. Credits: ESA, NASA, CSA, STScI.'
---

# 1. Introduction to Astrophysics and Cosmology

## 1.1. What it is Astrophysics?

It is worthwhile to review the ethimology of the categories mainly studied in this field: "astronomy", "astrophysics" and "cosmology". The distinction between these three categories is by far arbitrary, although it shows partially the historical development of this branch of science.

These three categories may be defined as follows:

* Astronomy: It is devoted to the stuy and determination of the measurements of coordinates, proper motions, brightness, spectra of any object in space.

* Astrophysics: It is fouced on analyzing the behavior of any object in space, but applying physical theories to understand observations and make predictions.

* Cosmology: It studies the large-scale structure of the Universe, but also its origin, composition and evolution.

Of course, once these cateogires have been defined, the reader might disagree with the definitions, the number of categories, or even the use of categories. Indeed, nowadays these categories are completely intertwined. Astronomy comes first as it is the oldest one, but then cosmology is the big jump that came in the mid 1900s. But it is imposible to not apply physics to understand everything that is being observed in the sky. Thus, we can certainly use "astrophysics" in its wide and general definition.

A very important aspect in this field of science is that it is extremely hard (although not impossible [reference to dust lab at the IAA]) to perform experiments, as most of the physical conditions are (nowadays) unacheivable on Earth laboratories. Hence, astrophysics is focused on observations and data analysis. Observations mainly come from photons, but in the recent years there has been clear advances towards multi-messenger astronomy by neutrinos ([reference here]) and gravitational waves ([reference here]). 

Nonetheless, astrophysics also offers a unique framework to test most of the different branches from physics: mechanics, electromagnetism, magneto-hydrodynamics, thermodynamics, statistical physics, special and general relativity, atomic and molecular physics, ... Hence, it is necessary to understand the different temperature-, length- and timescales that are involved, and at which extent the different quantum and/or relativistic effects take place. In return, we have en excellent benchmark to test recent theories such as:

* New matter states and new quantum particles

* The vacuum

* Intense magnetic fields

* General Relativity tests

Overall, these lectures will not be versed neither in positional astronomy, neither on pre-planck cosmology, but rather in providing a complete picture of all the aspects involved in astrophysics.

## 1.2. A brief historical summary

As it has been already mentioned, astrophysics is both one of the oldest and newest scientific disciplines. Hence, it is useful to review all the advances in the field across human history. We can review them in terms of specific epochs:

* **Epoch 1**: During this first epoch, which started around 4,000 BC, and ended around 600 BC, mithology and science are extremely correlated. During this epoch, mistic problems (astrology) and the need for orientation and agriculture enhances studies on the sky. We can observed in the Neolithic period (e.g. [Szucs-Csillik & Maxim 2019](https://ui.adsabs.harvard.edu/abs/2019amet.rept..267S/abstract)) representations of constellations, the Chinese culture is well-known for the elaboration of calendars and register of astronomical events (e.g. [Sun 2009](https://ui.adsabs.harvard.edu/abs/2011IAUS..260...98S/abstract)), the Egyptian culture focused on the orientation of the pyramids and the observation of the Syrius star (e.g. [Haack 1984](https://ui.adsabs.harvard.edu/abs/1984JHAS...15..119H/abstract), [Rawlins & Pickering 2001](https://ui.adsabs.harvard.edu/abs/2001Natur.412..699R/abstract), [Nell & Ruggles 2014](https://ui.adsabs.harvard.edu/abs/2014JHA....45..304N/abstract)), and the Babylonians also elaborated calendars and the so-called "Saros Cycle" (solar eclipses, e.g. [Goldstein 2002](https://ui.adsabs.harvard.edu/abs/2002JHA....33....1G/abstract)).

* **Epoch 2**: This epoch (between 600 BC and 200 AD) occurs mainly in Greece. Thanks to philosophers such as Thales of Miletus[^1] or Pythagoras[^2], the first scientific formulations came into play. For example, the first geometrical models for the Universe were proposed:

    * Geocentric model: Defended, among many others, by Eudoxus of Cnidus[^3], Plato[^4] and Aristotle[^5].
    
    * Epicylic model: Porposed by Claudius Ptolemaeus[^6], which introduces some modifications in the celestial motions with respect to the goecentric model.
    
    * Heliocentric model: Defended by Aristarchus of Samos[^7] and Seleucus of Seleucia[^8].
    
    Additionally, the first star catalogs are published:
    
    * The Hipparchus[^9] catalog, containing the position and magnitud of around 850 stars.
    
    * The Ptolemaus catalog, also known as *the Almagest*, containing over 1,100 stars, and whose use extent to the Middle Age.
    
* **Epoch 3**: This epoch lasted between 200 and 1500 AD, being mainly focused on the Middle Age. In the year 964, the arab astronomer al-Sufi[^10] published a catalog containing different nebulae. During this period of time, we have reports of observing two supernovae in 1006 (reported by Chinese, Japanese and Egyptian astronomers) and in 1054 (observed by Chinese, Japanese and Amerindian cultures). In Spain, during the XIII century, the so-called *Tablas Alonsíes*[^11] were elaborated, containing all celestial observations between 1263 and 1272 AD of the Toledo's night sky.

* **Epoch 4**: Between 1500 and 1870 AD, this epoch is characterized mainly by an opening to different theories. In a very first place, we can highlight the early works from Copernicus, Galileo, Kepler and Newton:

    * Copernicus[^12] returned to the Heliocentric model already postulated in the Ancient Greece.
    
    * In 1608, the telescope is invented in Netherlands, and Galileo[^13] used it to observe four satellites around Jupyter, solar spots, Venus phases, mountains in the moon, etc.
    
    * Two supernovae events were observed, in 1572 by Brahe[^14] and in 1604 by Kepler[^15], as well as comets (in 1577 by Brahe) and the variable star Mira Ceti (in 1596 by Fabricius[^16]). These events were milestones in shifting from the Geocentric to the Heliocentric model.
    
    * Between 1609 (first two) and 1619 (the third one), Kepler published the so-called "Kepler's Laws of Planetary Motion".
    
    * Newton[^18] formulated the his Theory of Gravity and Universal Gravitation in this famous *Principae* (1687), unifying Kepler's laws and the free-fall of objects. He also worked on understading light and its composition.
    
    * In 1676, Rømer[^18] measured the speed of light to a first approximation (see [Shea 1998](https://ui.adsabs.harvard.edu/abs/1998AmJPh..66..561S/abstract)).
    
    * In 1705, Halley[^19] predicted that the comet observed in 1682 would be observed again in 1758.
    
    In a second place, we can also highlight the advancements beyond the telescope that came with:
    
    * The advancements made by Wollaston[^20], Fraunhofer[^21] and Kirchhoff[^22] between 1800 and 1860 resulted in the development of spectroscopy, allowing for instance the determination of the chemical composition of the Sun by its absorption lines.
    
    * The development of photography and its application to astronomy by Draper[^23] in 1840.
    
    * Finally, it is important to mention the work by Argelander[^24], who published between 1859 and 1862 the largest catalog, *Bonner Durchmusterung*, of stars (~324,000) without the use of photography.
    
* **Epoch 5**: This epoch corresponds to the XX century, characterized by new conceptual and observational horizons. Einstein[^25] postulated his theories of Special ([Einstein 1905](https://ui.adsabs.harvard.edu/abs/1905AnP...322..891E/abstract)) and General ([Einstein 1916](https://ui.adsabs.harvard.edu/abs/1916AnP...354..769E/abstract)) Relativity, which led to new models of our understanding of the Universe, such as those proposed by de Sitter[^26], Friedmann[^27] and Lemaître[^28], and also lead to the formulation of black hole formation theories by Schwarzschild[^29] ([1916](https://ui.adsabs.harvard.edu/abs/1916AbhKP1916..189S/abstract)) (for a non-rotating, uncharged object), by Reissner[^30] ([1916](https://ui.adsabs.harvard.edu/abs/1916AnP...355..106R/abstract)) (for a non-rotating, charged object), by Kerr[^31] ([1963](https://ui.adsabs.harvard.edu/abs/1963PhRvL..11..237K/abstract)) (for a rotating, uncharged object) and by Newman[^32] et al. (1965[a](https://ui.adsabs.harvard.edu/abs/1965JMP.....6..918N/abstract),[b](https://ui.adsabs.harvard.edu/abs/1965JMP.....6..915N/abstract)) (for a rotating, charged object).

    In early 1910s, the independent works by Hertzsprung[^33] ([1911](https://ui.adsabs.harvard.edu/abs/1911POPot..22A...1H/abstract)) and Russell[^34] ([1913](https://ui.adsabs.harvard.edu/abs/1913Obs....36..324R/abstract), 1914[a](https://ui.adsabs.harvard.edu/abs/1914PA.....22..275R/abstract),[b](https://ui.adsabs.harvard.edu/abs/1914PA.....22..331R/abstract)) found a correlation between the color and brightness of the stars, leading to the so-called "Hertzsprung-Russell diagram" (H-R diagram). The early works by Eddington[^35] ([1916](https://ui.adsabs.harvard.edu/abs/1916MNRAS..77...16E/abstract), [1918](https://ui.adsabs.harvard.edu/abs/1918ApJ....48..205E/abstract), [1919](https://ui.adsabs.harvard.edu/abs/1919MNRAS..79R.177E/abstract), [1922](https://ui.adsabs.harvard.edu/abs/1922MNRAS..83...32E/abstract), [1926](https://ui.adsabs.harvard.edu/abs/1926ics..book.....E/abstract)) led to the stellar evolution theory.
    
    During this epoch, the core idea of "Universe" was also revisited, moving away from the theory of *Universes as Isles* by Kant[^36], thanks to the a more robust classification of the observed nebulae by the *New General Catalogue* (NGC, [Dreyer 1888](https://ui.adsabs.harvard.edu/abs/1888MmRAS..49....1D/abstract)). Thus, in 1920 the *Great Debate" between Shapley[^37] and Curtis[^38] on tha size of the Universe and the existence of other galaxies. While both astronomers use correct arguments, the idea defended by Curtis (that some of the observed nebulae were independent galaxies) was proven true by Hubble[^39] (e.g. [Hubble 1926](https://ui.adsabs.harvard.edu/abs/1926ApJ....64..321H/abstract)), by meausring Cepheids in Andromeda. Later on, Hubble works proved that the Universe was expanding as galaxies were redshifting ([Hubble 1929](https://ui.adsabs.harvard.edu/abs/1929PNAS...15..168H/abstract)).
    
    Several advancements on the field of subatomic and quantum physics led to several predictions, such as the existence of neutrons ([Rutherford 2020](https://ui.adsabs.harvard.edu/abs/1920RSPSA..97..374R/abstract)), pions ([Yukawa 1942](https://ui.adsabs.harvard.edu/abs/1942ZPhy..119..201Y/abstract)), neutrinos (Pauli letter), quarks ([Gell-Mann 1964](https://ui.adsabs.harvard.edu/abs/1964PhL.....8..214G/abstract), [Zweig 1964](https://cds.cern.ch/record/570209)), the Higgs boson (Higgs 1964[a](https://ui.adsabs.harvard.edu/abs/1964PhL....12..132H/abstract),[b](https://ui.adsabs.harvard.edu/abs/1964PhRvL..13..508H/abstract), [1966](https://ui.adsabs.harvard.edu/abs/1966PhRv..145.1156H/abstract)) and the Supersymmetry (SUSY) theory (e.g. [Salam & Strathdee 1974](https://ui.adsabs.harvard.edu/abs/1974PhLB...51..353S/abstract)). The majority of these predictions were confirmed by observations and experiments (Chadwick [1932](https://ui.adsabs.harvard.edu/abs/1932Natur.129Q.312C/abstract), [1933](https://ui.adsabs.harvard.edu/abs/1933RSPSA.142....1C/abstract), [Lattes et al. 1947](https://ui.adsabs.harvard.edu/abs/1947Natur.159..694L/abstract), [Cowan et al. 1956](https://ui.adsabs.harvard.edu/abs/1956Sci...124..103C/abstract), [Bloom et al. 1969](https://ui.adsabs.harvard.edu/abs/1969PhRvL..23..930B/abstract), [Breidenbach et al. 1969](https://ui.adsabs.harvard.edu/abs/1969PhRvL..23..935B/abstract), [Herb et al. 1977](https://ui.adsabs.harvard.edu/abs/1977PhRvL..39..252H/abstract), [Abrams et al. 1974](https://ui.adsabs.harvard.edu/abs/1974PhRvL..33.1453A/abstract), [Augustin et al. 1974](https://ui.adsabs.harvard.edu/abs/1974PhRvL..33.1406A/abstract), [CERN collaboration 2012](https://ui.adsabs.harvard.edu/abs/2012PhLB..716....1A/abstract)).
    
    It is also important to highlight the advancements in the field of astronomical observations by observing radio, X-ray and $\gamma$-ray radiation. Radio wavelength observations allowed the discovery of the Cosmic Microwave Background radiation ([Penzias & Wilson 1965](https://ui.adsabs.harvard.edu/abs/1965ApJ...142..419P/abstract)) or pulsars ([Hewish et al. 1968](https://ui.adsabs.harvard.edu/abs/1968Natur.217..709H/abstract)). Thanks to the technology development of the Cold War, this epoch was characterized by the first confirmation of x-ray emission coming from outside the Solar System ([Giacconi et al. 1962](Evidence for x Rays From Sources Outside the Solar System)). Finally, it is worthwhile to mention the detection of $\gamma$-rays through the Vela USA military satellites, originally dsegined the $\gamma$-ray burst from nuclear bomb detonations, but eventually detecting the $\gamma$-ray emission from our own Galaxy ([Klebesadel, Strong and Olson 1973](https://ui.adsabs.harvard.edu/abs/1973ApJ...182L..85K/abstract)).
    
* **Epoch 6**: It is difficult to explain this epoch as, from our point of view, is the one we are currently leaving. We can highlight three major aspects: the increase of statistics and quality of the data, and the multi-messenger astronomy. However, this major break in astronomy also push to the limits some of our assumed theories for the formation of the Universe. As of 2025, it is difficult to assess such impact.

    Ground-based observatories have contributed significantly in astronomy. Surveys such as Sloan Digital Sky Survey (SDSS[^40], [York et al. 2000](https://ui.adsabs.harvard.edu/abs/2000AJ....120.1579Y/abstract)), have signficantly increased astronomy in many fronts: the imaging data covers around 35,000 square degrees (see the official [website](https://www.sdss4.org/dr17/imaging) for more details); the supernovae survey containing over 900 SNe events spectroscopically confirmed (see the official [website](https://classic.sdss.org/supernova/snlist_confirmed.php) for more details); the spectra of over 2,800,000 galaxies, 1,020,000 stars and 960,000 quasars (see the official [website](https://www.sdss4.org/dr17/spectro/) for more details); spatially resolved spectroscopic observations of around 10,000 galaxies (see the official [website](https://www.sdss4.org/dr17/manga/) for more details) and many other added-value products (see the offical [website](https://www.sdss.org/dr18/) for more details). Although SDSS was a singificant revolution back in the day, now the Dark Energy Spectroscopy Instrument(DESI[^41], [DESI collaboration et al. 2022](https://ui.adsabs.harvard.edu/abs/2022AJ....164..207D/abstract)) is pushing the limits to a new standard, as the first data release (DR1) has provided spectroscopic information for over 13,100,000 galaxies, 4,000,000 stars and 1,600,000 quasars ([DESI collaboration et al. 2025](https://ui.adsabs.harvard.edu/abs/2025arXiv250314745D/abstract)). There has been also significant advancements in other surveys, such as the search for exoplanets with Calar Alto high-Resolution search for M dwarfs with Exoearths with Near-infrared and optical Echelle Spectrographs (CARMENES[^42], [Quirrenbach et al. 2016](https://ui.adsabs.harvard.edu/abs/2016SPIE.9908E..12Q/abstract)). Other important highlights come from the Very Large Telescope (8.2m, [VLT](https://www.eso.org/public/spain/teles-instr/paranal-observatory/vlt/)), the Gran Telescopio de Canarias (10.4m, [GTC](https://www.gtc.iac.es/)) or the future Extremely Large Telescope (39m, [ELT](https://elt.eso.org/about/)), and their instrumentation. Radio observations have also been enhanced by facilities such as the Atacama Large Millimeter Array (ALMA, [Kurz & Shaver 1999](https://ui.adsabs.harvard.edu/abs/1999Msngr..96....7K/abstract)).
    
    In terms of space-based observatories, have been proben to as essential as their ground-based counterparts. Missions such as Planck[^43] (see [Planck Collaboration 2008](https://ui.adsabs.harvard.edu/abs/2006astro.ph..4069T/abstract) for more details) have been crucial in our understanding and modeling of the Universe (e.g. Planck Collaboration et al. 2014[a](https://ui.adsabs.harvard.edu/abs/2014A%26A...571A..16P/abstract),[b](https://ui.adsabs.harvard.edu/abs/2014A%26A...571A..22P/abstract), 2016[a](https://ui.adsabs.harvard.edu/abs/2016A%26A...594A..13P/abstract),[b](https://ui.adsabs.harvard.edu/abs/2016A%26A...594A..20P/abstract), 2020[a](https://ui.adsabs.harvard.edu/abs/2020A%26A...641A...6P/abstract),[b](https://ui.adsabs.harvard.edu/abs/2020A%26A...641A..10P/abstract)). The infrardd regime, limited by the sky absorption, also experienced a signficant improvement thanks to missions such as the Infrared Space Observatory (ISO, [Kessier et al. 1996](https://ui.adsabs.harvard.edu/abs/1996A%26A...315L..27K/abstract)), the Spitzer Space Telescope (Spitzer, [Werner et al. 2004](https://ui.adsabs.harvard.edu/abs/2004ApJS..154....1W/abstract)), the AKARI mission ([Murakami et al. 2007](https://ui.adsabs.harvard.edu/abs/2007PASJ...59S.369M/abstract)), the Herschel Space Observatory (Herschel, [Pilbratt et al. 2010](https://ui.adsabs.harvard.edu/abs/2010A%26A...518L...1P/abstract)) or the James Webb Space Telescope (JWST, [Gardner et al. 2910](https://ui.adsabs.harvard.edu/abs/2006SSRv..123..485G/abstract)). The optical and near-ultraviolet regime has been exploited in many other ways by the launched of the Hubble Space Telescope (HST, [Turnsheck et al. 1990](https://ui.adsabs.harvard.edu/abs/1990AJ.....99.1243T/abstract)). X-rays observations have been also increased thanks to the Chandra X-ray Observatory (CXO, [Weisskopf et al. 2002](https://ui.adsabs.harvard.edu/abs/2002PASP..114....1W/abstract)) and the XMM-Newton Observatory ([Jansen et al. 2001](https://ui.adsabs.harvard.edu/abs/2001A%26A...365L...1J/abstract)).
    
    In the realm of our models and theories for understanding the Universe, this epoch has been characterized by the enigmas, and the remaining open questions. The Hubble Constant has been a matter of discussion, as different techniques provides different measurements, leading to the so-called "Hubble Tension" (e.g. [Di Valentino et al. 2021](https://ui.adsabs.harvard.edu/abs/2021CQGra..38o3001D/abstract), [Efstathiou 2021](https://ui.adsabs.harvard.edu/abs/2021MNRAS.505.3866E/abstract), [Hu et al. 2024](https://ui.adsabs.harvard.edu/abs/2024ApJ...975L..36H/abstract), [Verde, Schnöneberg & Gil-Marín 2024](https://ui.adsabs.harvard.edu/abs/2024ARA%26A..62..287V/abstract)). The amplitude of the matter fluctuations has also been under debate (e.g. [Planck Collaboration et al. 2020](https://ui.adsabs.harvard.edu/abs/2020A%26A...641A...6P/abstract), [Adil et al. 2024](https://ui.adsabs.harvard.edu/abs/2024MNRAS.528L..20A/abstract)). Our understanding of galaxy formation, from Dark Matter halos following a hierarchal growth and capturing pristine gas (e.g. [Cole et al. 2000](https://ui.adsabs.harvard.edu/abs/2000MNRAS.319..168C/abstract), [Springel et al. 2018](https://ui.adsabs.harvard.edu/abs/2018MNRAS.475..676S/abstract), [Martizzi et al. 2019](https://ui.adsabs.harvard.edu/abs/2019MNRAS.486.3766M/abstract)), has some problemas such as the "Missing Satellite Problem" (e.g. [Nashimoto et al. 2022](https://ui.adsabs.harvard.edu/abs/2022ApJ...936...38N/abstract)) or the "Too-Big-To-Fail Problem" (e.g. [Ogiya & Burkert 2015](https://ui.adsabs.harvard.edu/abs/2015MNRAS.446.2363O/abstract)). Overall, both our comoslogical model and theory for galaxy formation have several caveats and problems that suggest further research (e.g. [Bullock & Boylan-Kolchin 2017](https://ui.adsabs.harvard.edu/abs/2017ARA%26A..55..343B/abstract), [Efstathiou 2025](https://ui.adsabs.harvard.edu/abs/2025RSPTA.38340022E/abstract)).
    


    
    
[^1]: The Ancient Greek philosopher from Miletus in Ionia, Asia Minor (626/623 - 548/545 BC).
[^2]: The Ancient Greek philosopher (570 - 495 BC).
[^3]: The Ancient Greek astronomer (390 - 340 BC).
[^4]: The Ancient Greek philosopher (428/423 - 348/347 BC).
[^5]: The Ancient Greek philosopher (384 - 322 BC).
[^6]: The Greco-Roman astronomer (100-160/170 AD).
[^7]: The Ancient Greek astronomer (310 - 230 BC).
[^8]: The Ancient Greek astronomer (190 - 150 BC).
[^9]: The Ancient Greek astronomer (190 - 120 BC).
[^10]: The Persian astronomer Abd a-Rahman al-Sufi (903 - 986).
[^11]: They received their name after Alfonso X of Castile, who sponsored their creation. It was created by Toledo School of Translators, composed by several scholars, and taking advantage from previous works from Islamic astronomers.
[^12]: The Polish astronomer Nicolaus Copernicus (1473 - 1543).
[^13]: The Italian astronomer and Physicist Galileo di Vincenzo Bonaiuti de' Galilei (1564 - 1642).
[^14]: The Danish astronomer Tycho Ottesen Brahe (1546 - 1601).
[^15]: The German astronomer Johannes Kepler (1571 - 1630).
[^16]: The Frisian astronomer Johannes Fabricius (or Johann Golsmid, 1587 - 1616).
[^17]: The English mathematician, physicist, astronomer and *warden of the Royal Mint* Sir Isaac Newton (1643 - 1727).
[^18]: The Danish astronomer Ole Christensen Rømer (1644 - 1710).
[^19]: The English astronomer Edmond Halley (1656 - 1742).
[^20]: The English chemist and physicist William Hyde Wollaston (1766 - 1828).
[^21]: The German astronomer and physicist Joseph Ritter von Fraunhofer (1787 - 1826).
[^22]: The German physcist Gustav Robert Kirchhoff (1824 - 1887).
[^23]: The American medical doctor and amateur astronomer Henry Draper (1837 - 1882).
[^24]: The German astronomer Friedrich Wilhelm August Argelander (1799 - 1875).
[^25]: The German physicist Albert Einstein (1879 - 1955).
[^26]: The Dutch mathematician Willem de Sitter (1872 - 1934).
[^27]: The Rusian physicist Alexander Alexandrovich Friedmann (1888 - 1925).
[^28]: The Belgian priest and physicist Georges Henri Joseph Édouard Lemaître (1894 - 1966).
[^29]: The German physicist and astronomer Karl Schwarzschild (1873 - 1916).
[^30]: The German aeronatuical engineer Hans Jacob Reissner (1874 - 1967).
[^31]: The New Zealand mathematician Roy Patrick Kerr (1934).
[^32]: The American physicist Ezra Theodore Newman (1929 - 2021).
[^33]: The Danish chemist and astronomer Ejnar Hertzsprung (1873 - 1967).
[^34]: The American astronomer Henry Norris Russell (1877 - 1957).
[^35]: The Englsh physicist and astronomer Sir Arthur Stanley Eddington (1882 - 1944).
[^36]: The Prusian philosopher Emanuel Kant (1724 - 1804).
[^37]: The American astronomer Harlow Shapley (1885 - 1972).
[^38]: The American astronomer Heber Doust Curtis (1872 - 1942).
[^39]: The American astronomer Edwin Powell Hubble (1889 - 1953).
[^40]: This survey is conducted with a 2.5m f/5 modified Ritchey-Chretien wide-field altitude-azimuth telescope at the Apache Point Observatory ([York et al. 2000](https://ui.adsabs.harvard.edu/abs/2000AJ....120.1579Y/abstract)).
[^41]: This survey is conducted with a 4m Ritchey-Chretien telescope at the Kitt Peak National Observatory ([DESI collaboration et al. 2022](https://ui.adsabs.harvard.edu/abs/2022AJ....164..207D/abstract)).
[^42]: This survey is conducted with a 3.5m telescope at the Calar Alto Observatory ([Quirrenbach et al. 2016](https://ui.adsabs.harvard.edu/abs/2016SPIE.9908E..12Q/abstract)).
[^43]: Planck was a satellite launched in 2009 to map the anisotropies and polarization of the Cosmic Microwave Background by measuring and imaging light in the infrared and micowave regimes.







