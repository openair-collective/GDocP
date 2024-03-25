# Documentation Practice for OpenAir Projects
Good documentation practice for OpenAir open hardware projects. _This repository is a work in progress!_

### A checklist for ensuring your repository's documentation is complete 
This checklist is adapted from the article templates for [_HardwareX_](https://www.doi.org/10.5281/zenodo.3364474).
- [ ] Is the subject of the submission under an open source license?
- [ ] Are design files in the preferred format for making modifications as defined by the [Open Source Hardware definition](https://www.oshwa.org/definition/)?
- [ ] Can the hardware be reproduced with the details provided in the repository?
- [ ] Are all relevant design files available in the repository? Are they described in a README, and clearly documented? (_e.g._, descriptive file names, commented code, labeled images, etc.) 
- [ ] Are visual instructions used when necessary?
- [ ] Is the utility of the hardware to the scientific community explained clearly? Has a specific scientific application been demonstrated using the hardware?
- [ ] Is the performance of the hardware adequately demonstrated and characterized? (Are data demonstrating the hardware performance, such as .csv files, lab notes and graphs, included in the repository or posted to a FAIR repository and cited?)
- [ ] Are all potential safety concerns addressed?
- [ ] Has all [personally identifiable information (PII)](https://www.ibm.com/topics/pii) and sensitive information (such as passwords) been removed?
- [ ] Are all comments and inline notes necessary and [appropriate](https://retractionwatch.com/2014/11/11/overly-honest-references-should-we-cite-the-crappy-gabor-paper-here/)? Keep in mind that the repository will be *permanent.*


### A checklist for making your repository FAIR and cross-referenced
- [ ] Make sure your repository is ready to share openly and permanently (see notes on PII, comments above)
- [ ] Make sure your README is clear and includes the OpenAir logo and a clear statement of what your project does and what its state of development is
- [ ] Pick an open hardware license at https://www.choosealicense.org and save it as a *License.txt* file
- [ ] Add your repository to the OpenAir Github Community
- [ ] Get ORCID accounts for as many authors as possible at orcid.org
- [ ] As the project maintainer, set up an account on www.zenodo.org, and connect it to your ORCID account.
- [ ] Implement Zenodo/Github sync for your repository
- [ ] Issue a release on Github. (v.0.0.1 is a good tag to use when starting out.) This will generate a Zenodo repository and give you a DOI
- [ ] Add authorship information to Zenodo repository, including ORCIDs for all authors and contributors
- [ ] Add your Zenodo repository to the OpenAir Zenodo community
- [ ] Add a `CITATION.cff` file to your Github repository which includes the Zenodo DOI
- [ ] Add the DOI badge for your repository to Github. (You can copy Markdown code for this from the right sidebar on Zenodo)
- [ ] Add the correct hardware license to the metadata of your Zenodo repository
- [ ] If applicable, add relevant funding sources (e.g., NSF grants) to the metadata of your Zenodo repository
- [ ] _OPTIONAL:_ Apply to the Open Source Hardware Association for an OSHWA ID. (That isn't implemented in this repository because it isn't hardware, but you can see an example here: https://certification.oshwa.org/us002582.html)
- [ ] _OPTIONAL:_ If you receive an OSHWA ID, add the logo to your README on Github and add the number to your Zenodo repository as an Alternate Identifier.

## Links and Terms of Art

### CITATION.cff File
See this link to learn more about citation files: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files

### DOI
"DOI" stands for "Digital Object Identifier." Learn more here: https://www.doi.org/the-identifier/what-is-a-doi/
You can think of a DOI as being similar to an International Standard Book Number (ISBN), but for any digital object. It can reference a dataset, a journal paper, a Github repository, etc. Different versions of the same project can also have different DOIs, so that you can reference a specific version. 

### FAIR Data
FAIR is a grassroots standard for science data. The initalism stands for Findable, Accessible, Interoperable and Reusable. 
Learn more here: https://www.go-fair.org/fair-principles/

### Logos and Badges
OpenAir logos can be found in this repository. You can embed them in your README file. 
Badges (see https://shields.io/badges) are a great way to encode information, including Zenodo DOIs. 

### Licensing
A good open source project should have an open source license! There are many available which cover all kinds of use cases for software and hardware. Check out https://choosealicense.com/ for a guide on how to pick the right license for your project. Once you have a license that fits, copy it into your Github repository as a LICENSE.txt file. You'll notice that this automatically creates a License tab next to the README tab, and that the license you have chosen will appear in the top right sidebar on Github. 

### ORCIDs
Just as DOIs are a persistent identifier for digital objects, ORCID is a persistent identifier for people. This can be useful for you as a researcher to track your publications and work over time. It also helps affirm your authorship if you have a common name or if you change your name. All OpenAir participants are encouraged to get an ORCID, because it helps us to track contributions. Learn more at https://orcid.org/.

### OSHWA UID
The Open Source Hardware Association (OSHWA) provides their own identifier system for open hardware projects. You can apply for an OSHWA UID here: https://application.oshwa.org/


