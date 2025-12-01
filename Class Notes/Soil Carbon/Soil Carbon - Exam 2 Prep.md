# Why is Soil Organic Matter so Complex?
+ Many different sources
+ Large heterogeneous decomposer community
+ Multiple degradation pathways
+ Formation and persistence of SOM is affected by soil and climate properties

# Methods to Characterize SOM

## Conceptual Models
+ Pools like:
	+ active (<10y), passive, slow (>100y)
	+ Decomposable plant material, Resistant plant material, Microbial biomass, Humified OM
	+ Litter (Very labile, labile, resistant), Microbes (Labile, resistant), Humads (Labile, resistant), Passive humus
	+ 
## Computational Models
+ Current earth system models apply soil models that assume first-order kinetic exchanges among conceptual pools defined by empirical turnover times. 
+ These models reflect the cutting edge of C cycle science in the 1970s and 1980s (Century, RothC)
	+ Still useful, they are spatially efficient and capture essential dynamics
	+ Parameters for C flux include Temp, Texture, Moisture
	+ They do not explicitly represent the characteristic processes of C transformation such as adsorption, protection, desorption, and microbial activity
	+ default turnover rates are justified by the combined influence of physical protection and inferred resistance to decomposition
	+ RothC and DNDC explicitly include 'slow' and 'passive' "recalcitrant" pools (humified, passive humus)
	+ lack of mechanistic representation of the decomposition process produces disagreement among models and between model predictions and observational data
+ More recent models take advantage of more computational strength and a better understanding of SOM fractions:
	+ Parameters now include Exoenzymes, Microbial Functional Groups, Roots, pH
	+ Instead of conceptual pools, many now use pools that can be separated by extraction or fractionation (fPOM, oPOM, LDWM, MAOM, Microbial Biomass)
	+ Flows have been updated to include rhizosphere vs bulk-soil as well as multiple horizon dynamics and more complex plant litter modeling

## Soil Incubations
+ Soil samples are incubated in the laboratory:
	+ Optimal moisture content
	+ Constant temperature
	+ Time controlled
+ CO2 production is main measurement
+ Often, net N mineralization is determined as well
+ Analyzing data from incubation:
	+ Two-pool model based on first order kinetics
		+ $\ce{CO2 = C_{pool1}*(1- e^{-tk1}) + C_{pool2}*(1 - e^{-tk2})}$
	+ $\ce{CO2}$ = $\ce{CO2}$ produced
	+ $\ce{C_{pool1}}$ and  $\ce{C_{pool2}}$ = Size of pools
	+ $\ce{k1}$ and $\ce{k2}$ = degradation constants of the two pools
	+ $\ce{t}$ = time
	+ The unknowns ($\ce{k1, k2, C_{pool1}, C_{pool2}}$) can be calculated using non-linear regression.

## Physical Fractionation
+ Experimental separation of SOM into homogeneous and ecologically meaningful fractions.
	+ Aggregates: Size (Dispersion, Sieving)
	+ OM-mineral complexes: Size (Dispersion, Sieving, Sedimentation)
	+ Organic Particles and OM-mineral complexes: Density (Na-Polytungstate)
	+ Organic Particles: Mass/surface ratio (Electrostatic attraction)
+ **Ecologically meaningful fractions:**
	+ **fPOM**
		+ MRT of <1 - 50 years, up to 80% of SOC in topsoils
		+ Sensitive in the short-term to land use and management
		+ Energy for microorganisms, soil structure
	+ **WEOM**
		+ MRT of <1 - <100 years, up to 15% of SOC in topsoils
		+ Most mobile fraction: transfer of energy and nutrients
		+ Energy for microorganisms
	+ **MAOM**
		+ MRT of >100 years, up to 80% of SOC in full soil
		+ largely influenced by soil mineral characteristics
		+ stabilized against microbial decay -> long-term C sink
	+ **oPOM**
		+ MRT of <100 - 400 years, up to 90% of C in topsoils
		+ influenced by multiple factors
		+ soil productivity and long-term C sink
+ **Water-stable aggregates**
	+ Fractionation of soil into classes of water stable aggregates by a wet-sieving procedure
		+ Microaggregates (>250um)
		+ Microaggregates (53-250um)
		+ Minerals and very stable, very small microaggregates (<53um)
+ **Density Fractionation**
	+ Mineral density 2.65
	+ Organic density <<1.85
	+ Density of organo-mineral complexes > density of organic material
	+ Free organic material floats
	+ Mineral associated sinks
	+ MAOM is less available to microbial degradation
	+ **Example with Na-Polytungstate**
		+ Density < 1.8 -> POM >20um & POM <20um
		+ Density 1.8-2.4 -> OM-mineral associations
		+ Density > 2.4 -> Minerals
+ **Dispersion of aggregates by application of ultrasound**
	+ Ultrasonic waves are induced under pressure which results in vapor bubbles (cavitation)
	+ When the cavitation implodes, a micro jet is produced
	+ A micro jet produced near or in an aggregate will destroy it
## General Problems
+ Transfer and redistribution of organic molecules between different fractions during separation
	+ Artifacts lead to misinterpretation of, for example, turnover times
	+ Kaiser's example of C from Coal dust (from nearby train) impacting turnover time measurements
+ OM fractions separated by the same method can be derived from different locations within the soil matrix
	+ Physically uncomplexed vs aggregate occluded
+ Overlapping influence of environmental, anthropogenic, and experimental factors on amount, composition, and turnover of OM fractions.
## Effects of Sample Preparation on Experimental Outcome
* **Alterations due to Airdrying***
	* New or stronger organo-mineral interactions
	* Increased water repellency
	* Increased mineral surface acidity
	* Increased EPS-mineral interactions
	* Increased microbial mortality and accumulation of osmolytes
* **Alterations due to Rewetting**
	* Slaking and disruption of aggregates
	* Increased microbial mortality and release of osmolytes
* **Variables impacted from Wet Sieving**
	* Redistribution of aggregate size classes and associated OM
	* Isotopic signature of aggregate associated OM
* **Variables impacted from Water Extraction**
	* Concentration of OM
	* Isotopic signature of OM
	* Biodegradability of OM
* **Variables impacted from Decomposition Experiments**
	* Preferential decomposition of individual organic compound classes
	* "Birch" effect
		* Spike in microbial respiration after rewetting

## Geomorphic Pump Study
+ **Background and Challenges**
	+ Degradation due to erosion is a problem
	+ Erosion affects the OC dynamics in soil. The net effect of erosion resulting in a terrestrial sink or source for CO2 depends on OC composition and deposition rates, but also on the rate of OC incorporation of the newly synthesized plant material into the eroded soil
	+ Seek to describe OC dynamics in erosional settings using the concept of "dynamic replacement" as continuous OC loss combined with its compensation by OC inputs.
+ **Objectives**
	+ Corroborate or refute the assumption that subsoil exposed by erosion can quickly incorporate and efficiently protect root-derived OC inputs.
	+ Quantitatively describe incorporation pathways and to understand the time scale associated with the incorporation of freshly assimilated C into the soil matrix
+ **Conclusions and Implications**
	+ Higher percentage of the 14C and higher absolute amount of recently assimilated C in the eroded soil -> dynamic replacement of OC losses due to input of OC from crops growing in eroded soils
	+ Enrichment of recently assimilated C -> Fraction indicative of OC stabilization by associations with minerals as well as occlusion in <20um aggregates -> potential of eroded soils to serve as a C sink if reactive mineral surfaces increase.
	+ Short time between labeling and the end of the experiment (20 days) -> 14C found in the <20um fraction mainly originates from LMWC from root exudates or their metabolites.
## Nebraska (Cultivated vs Prairie)
+ Losses in the MAOM fraction accounted for 48% of losses in the bulk soil OC
+ MAOM in high carbon input environments (A horizon/prairie) can comprise a substantial proportion of soil OC that is prone to disturbance-induced losses
+ This fraction also contains a significant proportion of SOC most relevant for the long-term C reservoir of disturbed topsoils
+ Our findings highlight the relevance of MAOM for soil management and land use strategies that aim to restore soil OC to pre-disturbance levels

# Functions of SOM
+ Improves soil aeration and water holding capacity
+ Improves soil structure and aggregate stability and lowers bulk density and soil erosion
+ Storage and supply of nutrients
+ Substrate for microorganisms
+ Binds pollutants
+ Buffers pH value
+ Stores greenhouse gasses
+ ~={red}**Most critical for sustainable and resource efficient soil productivity**=~
+ **To reduce SOM loss**:
	+ reduce erosion
	+ reduce tillage
	+ retain more crop residue
+ **To increase SOM**:
	+ Adding small grains to rotation
	+ Adding grazed or hayed perennial grass to the rotation
	+ Increasing rotation intensity with cover crops and double-cropped forages
	+ Increase crop production
	+ Incorporate some crop residue
	+ Retain crop residue
	+ Periodically applying manure
# Improving and Maintaining SOM
## Tillage
+ **Tillage:**
	+ increases SOM in the topmost of the profile, but decreases SOM to a depth below the plowpan
	+ Decreases MRT of SOM in many climates
	+ Decreases concentration of water-stable aggregates
	+ Tillage destroys aggregates
	+ Reduced tillage leads to higher SOC
	+ Destruction of aggregates leads to exposure of oPOM, which can then be decomposed and respired
	+ Effects of conventional tillage on SOC is only seen in upper 10cm, in fact, tilled soils usually contain MORE carbon below 15cm until somewhere near plow depth due to mechanical mixing and then subsequent DOC leaching and bioturbation
+ **No/Reduced Tillage:**
	+ is a ~={red}**Win-Win System**=~ as it is cheaper for the farmer and has rapid, noticeable improvements

## Application of Manure/Compost, Fertilization, Crop Rotation, Crop Residues
+ **Manure**
	+ Meta-analyses have shown that manuring increases SOM in almost all scenarios, when applied consistently
	+ Stopping manuring will cause SOM to fall to its previous level under otherwise same management
+ **Fertilization**
	+ 
# Fractionation Experiment
1. Describe a physical/chemical/combination fractionation procedure for at least 3 separated fracs:
	a. Materials and agents
	b. Main characteristic property used for separation
	c. ecological meaning

2. Describe a scientific problem you want addressed using this method

I would like to understand the fractions of fPOM, oPOM, and MAOM in tilled vs untilled cultivated soils. My hypothesis is that tilled soils will have a higher concentration of fPOM in the A horizon, but a lower concentration of oPOM in the A horizon because tillage incorporates plant matter, but destroys aggregates and structure. fPOM is the most active and available form of SOM, and it is important as a food and nutrient source for microbes. oPOM is important for structure, which is necessary for good infiltration and respiration, and provides a long-term C sink when not disturbed. Microbes need food and nutrients, but they also need water and oxygen. MAOM should remain fairly constant between the trials, as it is influenced by soil mineral characteristics which would be controlled for in the experiment. 

First, I would remove fPOM >250um. I will take the sample and sieve out particles larger than 250um. Then I will warm and charge a plastic petri dish, and use it to electrostaticly separate the fPOM. This will be repeated several times.
Next, I will recombine the 2 size fractions of particles, and separate the rest of the fPOM using water as a density agent. This will require a sealed container, a pipette, and a 53um sieve. After the particles are combined and gently mixed with water, and the mineral component has settled to the bottom, the floating fPOM can be skimmed with the pipette, and transferred to a separate container through the sieve.
To obtain the oPOM, I would use ultrasonification to destroy the aggregates, being sure to only disperse for a time that destroys macroaggregates. After transferring to a sealed bottle and letting the mineral component settle, pipetting and sieving through a 53um sieve will separate the oPOM. Any organic matter that has not yet been separated will be the MAOM fraction. 