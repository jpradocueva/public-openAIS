# Tools
**[LwM2M Validator](http://devtoolkit.openmobilealliance.org/OEditor/OMNAVerify)**
  * It validates content in:
    * **DDF.xml file**: 
        * the metadata information published in [OMNA LwM2M Registry](http://www.openmobilealliance.org/wp/OMNA/LwM2M/LwM2MRegistry.html).
        * this information is contained in a ```DDF.xml``` file located in GitHub
        
    * **Common.xml**: 
        * the reusable resources defined in [OMNA LwM2M Registry](http://www.openmobilealliance.org/wp/OMNA/LwM2M/LwM2MRegistry.html).
        * this information is contained in a ```Common.xml``` file located in GitHub.
        
    * **LwM2M Registry API**:
        * the [OMNA LwM2M Registry](http://www.openmobilealliance.org/wp/OMNA/LwM2M/LwM2MRegistry.html) information is exposed via a API.
        
    * **Single Object**: 
        * in a publically available URL that describe a LwM2M Object. 
        * It is possible to validate a LwM2M Object stored in GitHub, just use the "Raw" link that contains the Object.
        
    * The error codes provided by the tool can be found here: [Error Codes](https://wiki.openmobilealliance.org/display/TOOL/Validation+Criteria+for+OMNA+LwM2M+Registry)    
    
**[LwM2M Editor](http://devtoolkit.openmobilealliance.org/OEditor/Default)**
 * The LwM2M Editor allows to: create, view, update, add a license, import, export and register a LwM2M Object

**How to update an existing LwM2M Object**
 
   1/ Import the Object into the [LwM2M Editor](http://devtoolkit.openmobilealliance.org/OEditor/Default)
 
   2/ Edit the Object as needed
 
   3/ Export the Object
  
   4/ Copy and past the exported Object into a Pull Request
