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



