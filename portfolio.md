# R resources for ecologists
Here is a summary and portfolio of [rfrelat Github public repositories](https://github.com/rfrelat). The resources are organized in three sections: [tutorial and workshops](#tuto); [dashboards/shiny apps](#shiny); and [companion scripts from published scientific articles](#open).

All scripts were developed by R. Frelat and are under [GNU General Public Licence v3](https://www.gnu.org/licenses/gpl-3.0). 

Last update October 2024. 



## Tutorials <a name="tuto"></a>

All tutorials below suppose basic knowledge of the [statistical software R](https://cran.r-project.org/). 

* [Spatial analysis in R for marine scientists](https://rfrelat.github.io/SpatialR.html)   
  Full day workshop, divided in two session of approx. 2h. Guidelines and dataset can be download [here](https://github.com/rfrelat/SpatialR/raw/master/SpatialR.zip) (67Mb).
  * [How to load, extract and analyse spatial data in R?](https://rfrelat.github.io/Spatial1_LoadExtractGIS.html)
  * [Hands-on multidimensional examples](https://rfrelat.github.io/Spatial2_MultiExamples.html)  
 <br>   

* [Introduction to food webs metrics](https://rfrelat.github.io/BalticFoodWeb.html)  
  2h tutorial introducing marine food web analyses and how to compute weighted and unweighted food web metrics.  
  
  
* Fish morphometrics  
  * [Fish outline analysis with R](https://rfrelat.github.io/FishMorpho.html)  
  2h tutorial introducing outline analysis on pictures of fish and how to interpret the output from  Elliptical Fourier Transform.
  * [Morphometric comparison with R](https://rfrelat.github.io/CoralFishes.html)  
  Introduction and comparison of 3 morphometric methods: traditional morphometric, geometric morphometric and outline analysis.    
 <br>   

* Applied multivariate analysis
  * [Introduction to multivariate analysis : from 2D to 3D](https://rfrelat.github.io/Multivariate2D3D.html)  
   2h tutorial introducing *classic* Principal Component Analysis and its extensions in 3 dimensions called Tensor Decomposition. Guidelines and dataset can be download [here](https://github.com/rfrelat/Multivariate2D3D/raw/master/Multivariate2D3D.zip)  
  * [Methods to study traits-environment relationship](https://rfrelat.github.io/TraitEnvironment.html)  
   Including advanced multivariate analysis ([RLQ analysis](https://rfrelat.github.io/RLQ.html)), and Bayesian modeling ([Hierarchical Modelling of Species Communities](https://rfrelat.github.io/HMSC.html)).
  * [Introduction to principal component analysis for measuring gender context](https://rfrelat.github.io/GenderClimate.html)  
   2h tutorial introducing Principal Component Analysis and its interpretation in the gender perspective  
 <br> 

* [Resilience Assessment](https://rfrelat.github.io/cuspra.html)  
R vignette to introduce the [cuspra R-package](https://github.com/rfrelat/cuspra) for the quantification of resilience based on empirical data using the stochastic cusp model

## Dashboards and Shiny Apps <a name="shiny"></a>

- Farm household exploration dashboard: https://startistic.shinyapps.io/farmhousehold_explo/   
  Interactive dashboard to help understand the diversity of farming systems. The dashboard is part of the [farmhoushold R package](https://github.com/rfrelat/farmhousehold) that provides tools to analyse farm household data.    
  

- CUSPRA Dashboard: https://rfrelat.shinyapps.io/CUSPRA/  
  Interactive dashboard to quantify the resilience based on empirical data using the stochastic cusp model ([Sguotti et al. 2024](https://doi.org/10.1098/rspb.2024.0089))  

  
- GAIA Dashboard: https://startistic.shinyapps.io/GAIA_Dashboard/   
  Interactive dashboard to Guiding Acid Soil Investments in sub-Saharan Africa [DOI: 10.5281/zenodo.7242765](https://doi.org/10.5281/zenodo.7242765)


- COMITA: https://rfrelat.shinyapps.io/comita   
  Comparative tools for Integrative Trend Analysis developed as an [R-package](https://github.com/rfrelat/comita) for the ICES working group COMEDA. More explanations can be found in the report of the working group:  
  ICES. 2019. Working Group on Comparative Analyses between European Atlantic and Mediterranean marine ecosystems to move towards an Ecosystem-based Approach to Fisheries (WGCOMEDA). *ICES Scientific Reports*. 1:49. 30 pp. [DOI 10.17895/ices.pub.5542](http://doi.org/10.17895/ices.pub.5542)
  
  
- MetaBTS: https://rfrelat.shinyapps.io/metabts  
  Interactive map of the inventory of bottom trawl surveys published in Global Change Biology by Maureaud A. *et al.* in 2020, *Are we ready to track climate‐driven shifts in marine species across international boundaries? ‐ A global survey of scientific bottom trawl data* [DOI: 10.1111/gcb.15404](https://doi.org/10.1111/gcb.15404)



  
  
  
## Open science <a name="open"></a>

Below is a list of companion data and scripts from published articles, ordered chronologically:

* Sguotti, C., Vasilakopoulos, P., Tzanatos, E., & Frelat, R. (2024). “Resilience assessment in complex natural systems”. *Proceedings of the Royal Society B*, 291, 20240089. [DOI 10.1098/rspb.2024.0089](https://doi.org/10.1098/rspb.2024.0089)  
  **data+script**: [DOI 10.5281/zenodo.10912017](https://doi.org/10.5281/zenodo.10912017)   
  **R-package**: https://github.com/rfrelat/cuspra   
  **tutorial**: https://rfrelat.github.io/cuspra.html  

* Frelat, R., Kortsch, S., Kröncke, I., Neumann, H., Nordström, M. C., Olivier, P. E., & Sell, A. F. (2022). “Food web structure and community composition: a comparison across space and time in the North Sea”. *Ecography*, 2: e05945. [DOI 10.1111/ecog.05945](https://doi.org/10.1111/ecog.05945)  
  **data+script**: https://github.com/rfrelat/NorthSeaFoodWeb

* Lopez, D. E., Frelat, R., & Badstue, L. B. (2022). "Towards gender-inclusive innovation: Assessing local conditions for agricultural targeting“. *Plos one*, 17(3), e0263771. [DOI 10.1371/journal.pone.0263771](https://doi.org/10.1371/journal.pone.0263771)  
  **data+script**: https://github.com/rfrelat/GenderClimate  
  **tutorial**: https://rfrelat.github.io/GenderClimate.html

* Quitzau, M., Frelat, R., Bonhomme, V., Möllmann, C., Nagelkerke, L., & Bejarano, S. (2022). "Traits, landmarks and outlines: Three congruent sides of a tale on coral reef fish morphology." *Ecology and Evolution*, 12, e8787. [DOI 10.1002/ece3.8787](https://doi.org/10.1002/ece3.8787)  
  **data+script**: https://github.com/rfrelat/CoralFish  
  **tutorial**: https://rfrelat.github.io/CoralFishes.html

* Emblemsvåg, M., Werner, K. M., Núñez-Riboni, I., Frelat, R., Torp Christensen, H., Fock, H. O., & Primicerio, R. (2022). "Deep demersal fish communities respond rapidly to warming in a frontal region between Arctic and Atlantic waters“. *Global Change Biology*, 28(9), 2979-2990. [DOI 10.1111/gcb.16113](https://doi.org/10.1111/gcb.16113)  
  **data+script**: https://github.com/rfrelat/GreenlandFish  

* Kortsch, S., Frelat, R., Pecuchet, L., Olivier, P., Putnis, I., Bonsdorff, E., ... & Nordström, M. C. (2021). Disentangling temporal food web dynamics facilitates understanding of ecosystem functioning. *Journal of Animal Ecology*. 90: 1205– 1216. [DOI: 10.1111/1365-2656.13447](https://doi.org/10.1111/1365-2656.13447)  
  **raw data**: [DOI:10.5061/dryad.6t1g1jwwn](https://doi.org/10.5061/dryad.6t1g1jwwn)  
  **data+script+tutorial**: https://rfrelat.github.io/BalticFoodWeb.html  

* Maureaud, A., Frelat, R., Pécuchet, L., Shackell, N., Mérigot, B., Pinsky, M. L., ... & T Thorson, J. (2021). “Are we ready to track climate‐driven shifts in marine species across international boundaries?‐A global survey of scientific bottom trawl data”. *Global change biology*, 27(2), 220-236. [DOI 10.1111/gcb.15404](https://doi.org/10.1111/gcb.15404)  
  **data+script+updated database**: https://github.com/AquaAuma/TrawlSurveyMetadata  
  **Shiny app**: https://rfrelat.shinyapps.io/metabts  

* Beukhof E, Frelat R, Pécuchet L, Maureaud A, Dencker TS, Sólmundsson J, Punzon A, Primicerio R, Hidalgo M, Möllmann C and Lindegren M. "Marine fish traits follow fast-slow continuum along coastal-offshore gradient.", *Scientific Report*, 9: 17878 [DOI: 10.1038/s41598-019-53998-2](https://doi.org/10.1038/s41598-019-53998-2)    
  **data+script**: Deposited in Dryad Digital Repository: (https://doi.org/10.5061/dryad.ttdz08kt8).

* Olivier, P., Frelat, R., Bonsdorff, E., Kortsch, S., Kröncke, I., Möllmann, C., ... and Nordström, M. C. (2019). “Exploring the temporal variability of a food web using long‐term biomonitoring data”. *Ecography*, 42(12):1-19, DOI 10.1111/ecog.04461.  
  **data**: Deposited in Dryad Digital Repository: (https://doi.org/10.5061/dryad.9tg3t75)

* Caillon F., Bonhomme V., Möllmann C. and Frelat R. (2018). “A morphometric dive into fish diversity”, *Ecosphere*, 9(5): e02220. [DOI 10.1002/ecs2.2220](https://doi.org/10.1002/ecs2.2220)  
  **data+script+tutorial**: https://rfrelat.github.io/FishMorpho.html

* Frelat R, Orio A, Casini M, Lehmann A, Mérigot B, Otto SA,  Sguotti C, Möllmann , (2018). “A three-dimensional view on biodiversity changes: spatial, temporal and functional perspectives on fish communities in the Baltic Sea”, *ICES Journal of Marine Science*, 75(7): 2463–2475. [DOI 10.1093/icesjms/fsy027](https://doi.org/10.1093/icesjms/fsy027)  
  **data+script**: Deposited as [Supplemetary material](https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/icesjms/75/7/10.1093_icesjms_fsy027/3/fsy027_supp.zip?Expires=1622654662&Signature=F3n0jK-2sd6VIyCYTYYMnJTcGvIwl7xOinOj0T3R8a-~u-EGUFcINsAPOpfDzl-Rz8jeTQ4-DTrBGhciUPFgiWX0qV2emTL9dzanfZijGzVwreY2a7jQgMvTUgPRqssgIzxDv3qVTGs5t~T0ObqpFqUmVIYaBYirS8Vq~A94RIwfNSpmKSxxZsGkAqK1-rG3bspPPmbhMPTX58kZjPUq186mocHP03l8hhY2TUXjPX7r7sCCmVrieedgjPTXVYEXAEZ29XhWqo4upBXsDgwJb3-t~6-HyrqdrL81wkJ6Uu7Lw48vltWH-FdCyE1OwGXSLPHG1Y5vcp2jKKQBUZiUOQ__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA)  

* Frelat R, Lindegren M, Dencker TS, Floeter J, Fock HO, Sguotti C, Stäbler M, Otto SA and Möllmann C (2017). Community ecology in 3D: Tensor decomposition reveals spatio-temporal dynamics of large ecological communities. *PLoS ONE*, 12(11): e0188205. [DOI 10.1371/journal.pone.0188205](https://doi.org/10.1371/journal.pone.0188205)  
  **data+script+tutorial**: https://rfrelat.github.io/Multivariate2D3D.html

