This repository contains draft versions (as releases) of the specification for the *extremely small executable* and the *extremely small loadable* file formats.

The specification can also be found [here](https://oscapl.github.io/Extremely-Small-File-Format/). The formatting is a bit messed up on the website though, but it's pretty readable nonetheless.

Check the `Releases` section for previous versions of the specification.

Releases are tagged according to the following grammar: *type* **-** *month-of-release* **-** *year-of-release* **-** *revision*

*type*: **one of**  
**Draft** **Final**  

**Draft** is of course a draft version of the standard and **Final** the final.

*revision*:  
**R** *digit-sequence*  
**F**  
**I**  

The first form specifies a revision of a draft version, the revision number indicated by the digit sequence following the **R**. The second form indicates a final release. And the third form indicates the initial release of a draft version.

*month-of-release*:  
*digit-sequence*  

*year-of-release*:  
*digit-sequence*  

*digit-sequence*:  
*digit*  
*digit-sequence* *digit*

*digit*: **one of**  
**0** **1** **2** **3** **4** **5** **6** **7** **8** **9**
