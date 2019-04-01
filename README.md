# GSQ Survey Profile
This is a generic model of a *survey* - a temporal observation event. Within this model too are more detailed models of special kinds of `Surveys`, such as `Seismic Surveys`, for the aquisition of seismic data. Figure 1 below shows the basic properties of the generic `Survey` class. 

<img src="model/survey.svg" style="width:300px;" alt="The GSQ Survey object and its direct properties" />  

**Fig. 1**: The GSQ Survey object and its direct properties  

The sepcialised surveys and their relation to `Survey` are given in Figure 2.

<img src="model/survey-hierarchy.svg" style="width:100px;" alt="Survey hierarchy" />  

**Fig. 2**: Survey hierarchy  


## Profile contents
The contents of this profile - files within this repository - are:

1. [model/](model/) - folder containing image and machine-redable versions of this profile's models
2. [shapes/](shapes] - folder containing [SHACL](https://www.w3.org/TR/shacl/) *shapes* files used to validate data's conformance to this profile's model
3. [profile.ttl](profile.ttl) - the formal description of this Profile according to the [The Profiles Vocabulary](https://www.w3.org/TR/dx-prof/).


## License
The content of this repository is licensed for use with the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by/4.0/). See the [license deed](LICENSE) for details.


## Contacts
*owner*:  
**Geological Survey of Queensland**  
1 William St, Brisbane, Queensland, Australia  

*author*:  
**Nicholas Car**  
*Senior Experimental Scientist*  
CSIRO Land & Water, Environmental Informatics Group  
<nicholas.car@csiro.au>
