---
layout: default
title: Research
---

## Current interests

- Galaxy evolution
- Star formation
- The multiphase interstellar medium
- Hydrodynamical simulations
- Connecting simulations with observations

## Sub-grid modeling of the interstellar medium: the TURTLE model

My doctoral research focuses on developing TURTLE (TURbulent Three-phase Low-resolution Equilibrium), a physically motivated sub-grid model of the interstellar medium for large-volume cosmological simulations. The project is carried out under the supervision of <a href="https://www.benediktdiemer.com"> Dr Benedikt Diemer </a> and in collaboration with <a href="https://vadimsemenov.com"> Dr Vadim Semenov </a> and <a href="https://sbialy.wixsite.com/astro"> Dr Shmuel Bialy</a>.

The main goal of TURTLE is to improve the physical realism of low resolution cosmological simulations as tools for testing fundamental physics and providing the essential link between theoretical models of galaxy formation and the statistical observables probed by modern surveys. The model incorporates key physical processes that occur on scales far below the resolution of cosmological simulations, including turbulence, molecular cloud formation, and stellar feedback. By capturing the impact of these unresolved processes, TURTLE enables large-volume simulations to produce more realistic predictions for star formation and the formation and evolution of galaxies across cosmic time.

## The effect of stellar feedback on ISM gas 

To understand how stars shape their surrounding environment, I perform computer simulations of Type II supernovae -- the powerful explosions that mark the end of the lives of massive stars. These explosions inject large amounts of energy into the surrounding gas, heating it, stirring it into turbulent motion, and changing its physical state.

Using the adaptive mesh refinement simulation code ART (Kravtsov et al. 1997; Rudd et al. 2008), I model supernova explosions under a range of different interstellar conditions, varying properties such as the gas density, chemical composition, and the strength of the surrounding ultraviolet radiation. The results are used to develop prescriptions that describe how supernovae redistribute mass and energy throughout the interstellar medium, which are then incorporated into the TURTLE model, enabling large-scale cosmological simulations to more accurately capture the influence of stellar feedback on galaxy evolution.

<div class="figure">

<img src="{{ '/assets/css/SN.png' | relative_url }}" alt="SNe explosion.">

<p class="caption">
Temperature projections of gas inside our turbulent-background SNe simulations, with box length of 200 pc. Each column represents a later stage in the simulation, illustrating the expansion of the shock wave over time.
</p>

</div>

## Gas evolution and star formation

This project, carried out under the supervision of <a href="https://vadimsemenov.com"> Dr Vadim Semenov</a>, investigates how the gas within galaxies evolves to form new stars. By combining computer simulations with theoretical models, it explores how dense, star-forming clouds are created, how long they survive, and how efficiently they convert gas into stars.

Using simulations of isolated disk galaxies, we extended the existing theoretical framework of Semenov et al. 2017 that describes how gas cycles between star-forming and non-star-forming states. We showed that turbulent motions within the gas can rapidly compress it into star-forming clouds, typically within a few to a few tens of millions of years. However, these clouds are short-lived, and only a small fraction of their gas is converted into stars before they are dispersed by processes such as stellar feedback.

These results help explain why galaxies form stars at the rates observed across the Universe and provide a physical understanding of one of astronomy's most important empirical relationships: the connection between the amount of gas in a galaxy and the rate at which it forms new stars, known as the Kennicutt-Schmidt law.

<div class="figure">

<img src="{{ '/assets/css/illustr.pdf' | relative_url }}" alt="Gas cycling.">

<p class="caption">
Overview of the gas cycling model (Semenov et al., 2017). Gas within galaxies continually cycles between diffuse gas and dense, star-forming clouds. The model describes how long gas spends in each phase and how quickly it is converted into stars. The balance between these processes determines how much of a galaxy's gas is actively forming stars and, ultimately, the galaxy's overall star formation rate. Figure from <a href="https://arxiv.org/abs/2602.02657"> Kocjan & Semenov 2026 </a>.
</p>

</div>

## Gas accretion and the circumgalactic medium (CGM)

Under the supervision of <a href="https://www.pontzen.co.uk/"> Dr Andrew Pontzen</a>, <a href="https://cphyc.github.io/"> Dr Corentin Cadiou </a> and <a href="https://www.astro.lu.se/~oscar"> Dr Oscar Agertz</a>, I worked on the thermal history and kinematics of the gas accreted onto galaxies. Using the AMR code <a href="https://bitbucket.org/rteyssie/ramses/src/master/"> RAMSES</a>, we focused on the relation between the two modes (hot and cold) of gas accretion and star formation activity in early galaxies. We showed that cold accreted gas forms a turbulent disk around the galactic centre, where it can remain for hundreds of millions of years before eventually flowing inward and forming stars in the central regions of the galaxy.

<div class="figure">

<img src="{{ '/assets/css/fig_illustr_together_ras.pdf' | relative_url }}" alt="Accretion.">

<p class="caption">
Trajectories of accreted gas up to 400 million of years before star formation. Hot-mode gas is shown in red, while cold-mode gas (cyan/blue) is divided into fast and slow components based on how quickly they form stars. Most cold-accreted gas settles into a turbulent disk (central panel), delaying star formation. Figure from  <a href="https://academic.oup.com/mnras/article/534/1/918/7756430"> Kocjan et al. 2024 </a>.
</p>

</div>

## Exploring dark matter through the MULTIVERSE collaboration

As part of the MULTIVERSE collaboration (PI: <a href="https://www.benediktdiemer.com"> Dr Benedikt Diemer </a>), I contribute to building a uniform simulation framework that enables systematic comparisons across various dark matter (e.g., cold, warm, self-interacting) and modified gravity models within a consistent numerical setup. The primary goal is to identify observable signatures, such as halo density profiles, subhalo structure, and satellite galaxy distributions, that can distinguish between dark matter models and provide robust predictions to guide and interpret next-generation survey data.
