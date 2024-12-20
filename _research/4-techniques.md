---
layout: single
title: "Methods & Techniques"
collection: research
permalink: /research/cryo
excerpt: 
---

## Geochemical and radioisotope analysis

We interpret geochemical and cosmochemical data to reconstruct Earth, environmental, and planetary histories. We rely on both the **elemental chemistry** of rocks as well as the compositions of specific **isotopic systems**. To collect these geo/cosmochemical measurements, we respectively rely on [elemental analysis](#elemental-analysis) and [mass spectrometry](#mass-spectrometry). We also use [computational](#computation) tools to evaluate geo/cosmochemical data in the context with mathematical models of natural processes.


---
#### First, a very brief refresher:
Atoms are made up of positively charged protons, negatively charged electrons, and "netural" neutrons. An atom's **element** is determined by the number of protons (atomic number or *z*, see the periodic table below), and its **isotope** is determined by its isotopic mass (the sum of protons and neutrons). For instance, an atom of helium (He) is determined by its atomic number *z=2*, and the isotope helium-4 has 2 neutrons:

<img src="/assets/images/He4.png" width="30%" style="display:block;margin-left:auto;margin-right: auto;">
---

### Elemental analysis

As geochemists, our first responsibility is to understand what our samples are <em>made of</em>. While we often have a reasonable first guess based on the minerals&mdash;calcite (CaCO<sub>3</sub>) contains calcium (Ca), carbon (C), oxygen (O) and quartz (SiO<sub>2</sub>) contains silicon (Si) and oxygen (O)&mdash;variations in elemental composition can give us insight into <em>how</em> these minerals formed.

<figure>
    <img style="display:block;margin-left: auto;margin-right: auto;background-color:rgb(255,255,255,0.8);" width="100%" src="https://upload.wikimedia.org/wikipedia/commons/2/2e/Simple_Periodic_Table_Chart-en.svg">
    <figcaption>Periodic table of the elements (with atomic numbers, <em>z</em>). Image: <a href="https://commons.wikimedia.org/wiki/File:Simple_Periodic_Table_Chart-en.svg">Wikimedia Commons</a></figcaption>
</figure>

We use a variety of tools to measure elemental compositions, including mapping elemental compositions with scanning electron microscopes (SEM) and measuring elemental abundances with inductively-coupled plasma atomic-emission spectroscopy (ICP-AES).

### Mass spectrometry

Mass spectrometry is a diverse and well-established technique for measuring isotopic compositions. Many of the measurements used by GRACkLe members (e.g. U-series, radiogenic Sr, δ<sup>18</sup>O, δ<sup>13</sup>C) rely on "sector" mass spectrometry, which uses an electromagnet as a "mass analyzer." 

<img src="/assets/images/tims.png" width="80%" alt="TIMS diagram, depicting a glowing filament ('Source: heated filament'), from which an ion beam passes through a box labelled 'focusing lenses' and then curves through a box labelled 'Electromagnet Mass Analyzer.' The beam splits into high and low mass beams before reaching the 'Detectors' including Faraday cups and ion counters." style="display: block;margin-left: auto;margin-right: auto;">

This diagram illustrates how a TIMS (Thermal Ionization Mass Spectrometer) operates. A heated filament ionizes a sample. A high voltage within the instrument accelerates those ions toward the back of the instrument at nearly the speed of light. Magnetic lenses focus the beam and it passes through the mass analyzer electromagnet. The magnetic field within the mass analyzer pulls the ions, curving their path. Since more massive ions have greater momentum, their trajectory curves less while less massive ions' paths curve more. This mass-separated ion beam is then measured by detectors at the "back end" of the instrument.

The details of mass spectrometers vary and need not rely on a "sector" mass analyzer. Indeed, some isotopic analysis techniques do not rely on mass spectrometry at all! 

## Computation 

We use statistical models to fit geochemical data to numerical simulations of Earth and planetary systems. For high-performance computing, we rely on our 32-core server `Nunatak`. 


<img src="../assets/images/logos/nunatak-logo.svg" style="display: block;margin-left: auto;margin-right: auto; width:60%;" > 

Most of our codes are written in the [Julia Programming Language](https://julialang.org/), a high-performance, open source scientific computing language.
<img src="https://raw.githubusercontent.com/JuliaLang/julia-logo-graphics/master/images/julia-logo-dark.svg" style="display: block;margin-left: auto;margin-right: auto; width:10%;" > 

### Packages developed &amp; maintained by GRACkLe members

<table style="font-size:14pt">
<tr>
    <td><a href="https://github.com/grahamedwards/CorePore.jl">CorePore.jl</a></td>
    <td><a href="https://github.com/grahamedwards/IsoMix.jl">IsoMix.jl</a></td>
    <td><a href="https://github.com/grahamedwards/SolarChem.jl">SolarChem.jl</a></td>
    <td><a href="https://github.com/grahamedwards/ImpactChron.jl">ImpactChron.jl</a></td>
    <td><a href="https://github.com/grahamedwards/CleanHistograms.jl">CleanHistograms.jl</a></td>
</tr>
<tr>
</tr>
</table>



