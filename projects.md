## PhD in Astroparticle Physics
Thesis on "Cosmic chirps: extracting cosmological and astrophysical information from compact binary mergers"

This thesis explores the multi-faceted and promising science of gravitational waves (GWs) from \compact binary coalescneces (CBCs), focusing on the information they provide and how we can extract it. Central to our work is the question: What is the data content of the GW signals from CBCs, and how can we effectively analyze it to enhance our understanding of the Universe? This study addresses current detector networks and next-generation (XG) instruments, linking data analysis with \acrfull{MM} applications and cosmology.

In the first part, the analysis centers on current detectors, using data from the LIGO-Virgo-KAGRA (LVK) network. We explore spectral siren cosmology by applying hierarchical Bayesian inference to simulated and measured data. A significant focus is on quantifying the bias in the inferred Hubble constant value, $H_0$, that arises from mismodeling the black hole (BH) population—specifically, the effects of neglecting the redshift dependence of the BH mass spectrum. We report a bias at $2\sigma$ level, signaling the impact of the mass model. We also show preliminary results from the O4a observational run, presenting the latest estimate of $H_0$ and the impact of a new mass model that encompasses all the observed CBCs, without the need to distinguish between BHs or neutron stars (NSs). Being able to use all the available GW events gives us tighter constraints on $H_0$, although still far from the level of Planck or supernovae results.

The second part shifts the focus to future GW observatories, with the Einstein Telescope (ET) exemplifying XG capabilities. We thoroughly discuss forecasting analysis techniques based on the Fisher matrix approximation, which is the current approach for assessing XG detectors performance. In this context, we present the software tool GWFish, which simulates GW detector networks and implements fast Fisher matrix parameter estimation. Additionally, we integrate prior information into GWFish to study the interplay between signal-to-noise ratio and parameter correlations effectively, testing it to be a reliable method for predicting detectors performance against measured data from the LVK Collaboration. 

GWFish is employed for several different applications related to the rich ET science case. It is one of the two Fisher codes used for the design comparison (ET-$\Delta$ versus ET-2L) paper of ET. Specifically, one of the key aspects that we explore is multi-messenger (MM) astrophysics, evaluating the prospects for synergy between GWs and electromagnetic (EM) observatories based on sky localization and pre-merger alerts analyses. This work highlights the performance of different ET designs, particularly stressing the role of the sensitivity at low frequencies.

Furthermore, we conduct an in-depth study of the joint GW and kilonovae (KNe) detections using future EM telescopes like the Vera Rubin Observatory, pinpointing which are the primary sources of uncertainties in MM studies, from the GW network to population models to the microphysics of NS systems. 

Additionally, we investigate ET prospects for cosmological analysis using both bright siren -binary neutron star events with gamma-ray burst counterparts- and dark siren -binary black holes events along with the large-scale structure data as mapped through the $21$\,cm emission from neutral hydrogen- approaches to infer cosmological parameters up to redshifts as high as $z\sim 3$ in the dark siren case. In both scenarios, we demonstrate the enormous potential of ET in constraining cosmological parameters, thanks to the enhanced parameter estimation and detection numbers.

This work builds a framework that links advanced data analysis techniques, predicts detector performance, and includes MM observations and cosmological inference. The findings improve our understanding of GW astronomy, paving the way for future studies with existing and XG observatories.

- PhD Thesis [here](PhD_Thesis_Dupletsa.pdf)

Projects I developed before my PhD:

## Super Massive Black Holes
Project on the analysis of supermassive black hole (SMBH) merger trees.

Supermassive black holes are giant monsters residing at the centre of every galaxy. They present masses ranging form millions to hundreds of billions solar masses. How black holes can grow to such huge masses is still unanswered. Studying black holes merging history, alongside the structure formation across the cosmos, is fundamental to shed some light on the dynamics and evolution of these mysterious objects. This acquire a renewed importance in the light of the recent discovery of gravitational waves. Coalescences of supermassive black holes binaries, in fact, are sources of gravitational waves in the low frequency regime, detectable by the future space based interferometeres (millihertz band), as LISA, and by the current and future PTA experiments (nanohertz band).

There are different simulations that explore the formation of structures, from the origins of the Universe to the present day. I am working on the data given by the Millennium Simulation. These data are processed to reconstruct the merging trees of thousands of black holes. Then for each galactic merger in the tree, the delay time for the black hole binary coalescence is implemented. This delay time takes into account:
* the dynamical friction drives the black holes at the centre of the merging galaxies down to the centre of the newly formed galaxy, until the two black holes enter the sphere of influence of each other and become a keplerian binary 
* stellar or gaseous hardening subtract energy from the binary making it shrink progressively until the separation is small enough for gravitational wave emission to overtake and bring the binary to coalescence

When following the merger history of a black hole and implementing delay times between galactic and binary merger, it is possible that, in some cases, the black hole binary isn't able to coalesce before the subsequent galactic merger. This results in the formation of multiple systems (mainly triplets), where the pre-existing binary. In the Notes section I've posted how I've implemented the triplet interaction for the Millennium data.

Time delays affect the binary merger rates with respect to the galactic merger rates, shifting lower redshifts the moment when most mergers occur.

- Find notes [here](SMBH_TreeMerger.pdf)

## Projects in C/C++
Here are some [notes](computational_master.pdf) on the two projects you can find open-source on my GitHub:
- Harmonic oscillator [Github project](https://github.com/ulyanadupletsa/HarmonicOscillator)
- Lattice phi4 theory [Github project](https://github.com/ulyanadupletsa/LatticePhi4Theory)

## Master's degree

Black holes are the most fascinating objects in the Universe! Regions of spacetime where the gravitational force is so strong to not even let light can escape if it passes too close. Yet we do know so little about them. Often they are refered to as singularities meaning that a coordinate-independent quantity, the curvature, which measures the strenght of gravitational pull, becomes infinite and our physics fails to describe what's inside a black hole. Everything seems shielded by a horizon and it is sensible to require that there are no singularities without a horizon. 

There is a theorem - the no-hair theorem - stating that all the accessible information about a black hole is its mass, its charge, if it has one, and its angular momentum if it's rotating. It was an extraordinary breakthrough to find out that black holes behave as thermodynamic objects: they possess a temperature, emit radiation and, on top, they have entropy.

The discovery of the concept of black hole entropy goes to Jacob Bekenstein. Here is an extract from an article by Thibault Damour, which you can find at the following link [Damour](https://arxiv.org/pdf/hep-th/0401160.pdf) and which is a good introduction to the thermodynamic aspects of black holes. Damour takes it from John Wheeler's book **A journey into gravity and spacetime** and it is John Wheeler, who's speaking.

> One afternoon in 1970 Bekenstein -then a graduate student- and I were discussing black hole physics in my office in Princeton's Jadwin Hall. I told him the concern I always feel when a hot cup of tea exchanges heat energy with a cold cup of tea. By allowing that transfer of heat I do not alter the energy of the universe, but I do increase its microscopic disorder, its information loss, its entropy. The entropy of the world always increases in an irreversible process like that.

> *The consequence of my crime, Jacob, would echo down to the end of time,* I noted. *But if a black hole swims by, and I drop the teacups into it, I conceal from all the world the evidence of my crime. How remarkable!*

> *You don't destroy entropy when you drop those teacups into the black hole. The black hole already has entropy, and you only increase it!*

I've studied black hole's entropy during my master degree
- Master thesis [here](master.pdf)

## Bachelor's degree
- Bachelor thesis [here](BachelorThesis.pdf)



