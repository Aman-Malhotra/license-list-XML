# License Inclusion Principles
Determining whether a candidate license should be included on the SPDX License List requires the SPDX Legal Team to engage in a case-by-case evaluation of each candidate license based on a number of factors. The list below attempts to set out an order of priority to that end. However, the list of factors here is not necessarily exhaustive. The ultimate decision will be based on the totality of the factors and SPDX's goals and objectives. 

## Candidate License Analysis

**Definitive factors:**
* The submitted license must not match another license already on the SPDX License List as per the SPDX matching guidelines.
* All OSI-approved licenses will be included on the SPDX License List.
  * This is consistent with early collaboration between SPDX and OSI (2011) to ensure that all OSI-approved licenses were represented on the SPDX License List. Also at that time, OSI began using the SPDX license identifiers in their URLs and on the license pages.
* Binary-only software licenses or licenses that do not provide for the availability of the source code will not be included on the SPDX License List.
  
**Other factors (roughly in order of importance):**
* The license substantially complies with one of the following open source definitions (even if not submitted for approval, as in the case of OSI) or these organization consider the license to meet their definition:
  * [Open Source Definition (OSD)](https://opensource.org/osd) from the Open Source Initiative (OSI)
  * [Free Software Definition](https://www.gnu.org/philosophy/free-sw.en.html) from the Free Software Foundation (FSF)
  * [Open Source Hardware Definition](https://www.oshwa.org/definition/) from the Open Source Hardware Association (OSHWA)
  * [Open Definition](http://opendefinition.org/od/2.1/en/) from the Open Knowledge Foundation (for open data)
* The license is structured to be generally usable by anyone. It is not a "vanity" license or specific to one project, consortium or corporation.
* The license has actual, substantial use such that it is likely to be encountered. Substantial use may be demonstrated via use in many projects, or in one or a few highly significant projects.
* The license has identifiable and stable text; it is not in the midst of drafting. The license steward is committed not modifying after addition to the list and to versioning new versions in the future.
* If the license does not substantively comply with one of the above open source definitions, then the license is primarily intended for free distribution of content (including, in the case of software, its source code) with limited restrictions, and also meets other factors listed here.
* The license steward supports or is at least aware of and does not oppose its submission to the SPDX License List.

The SPDX legal team will also consider any information considered relevant by the license steward or open source community.

Comments on license inclusion will be noted in the Github issue for the license (or reference to meeting minutes, as necessary). Some license requests may be decided solely via comments in the Github issue and some may involve discussion on the bi-weekly legal call. Thus it is imperative that requestors join the mailing list and calls to fully participate.

*last updated Feb 2020*

## Historical Background
The first beta version of the SPDX License List was published in August 2010 and had approximately one hundred licenses on it. The initial set of licenses was included based on informal discussion and consensus on the SPDX working group calls and email list. Although various "guidelines" were identified in regards to which licenses to include or not during this time, formal guidelines were not recorded beyond the meeting minutes. We had to start somewhere, and the obvious was the easy beginning point. Decisions or guidelines that evolved out of discussion or by implication included the following:
* Include commonly found open source licenses. Although discussion was not explicit in regards to how to define an "open source license," this was always an implicit guiding principle
* Include all OSI approved licenses, both current and those approved but now deprecated. The rationale being that once OSI-approved, always OSI-approved and deprecated licenses still appear "in the wild"

At some point in these early days, there was consensus to include all of the Creative Commons licenses, even though the NC and ND do not fit the OSD. Other older licenses that were accepted on the list by consensus before we had formal inclusion guidelines may also fall under this "grand-licensed-in" reality.

Before long we recognized the need for a more formal process for requesting new licenses to be added to the SPDX License List. Such a process was discussed in terms of an ideal goal and pragmatic approach for the current reality (people sent an email to the mailing list). A process that bridged the former, with more weight on the latter was implemented in April 2012. 

In the waning days of 2012, we realized the need to make it clear and transparent to the world what criteria was being used to determine when to "accept" or "reject" a request to add a license to the SPDX License List. The result of those discussions was the publication of the license inclusion guidelines on the SPDX website in early 2013.

These guidelines served us well. But as time marches on and things evolve, we set out to consider a revision in 2019...


## Historical/Original Principles 
(est. early 2013)
The Software Package Data Exchange® (SPDX®) specification is a standard format for communicating, among other things, the components, licenses, and copyrights associated with open source software packages. Use of this standard streamlines license identification across the supply chain while reducing redundant work.

The goal of SPDX is not to evaluate licensing information or to provide legal interpretations. The only goal is to reliably and consistently communicate and share objective factual information so that organizations using software components will have the information necessary to conduct their independent analysis and evaluation. Establishing a consistent, reliable, and reusable way to communicate license information for software components will facilitate open source license compliance along the supply chain.

Although SPDX has traditionally focused on open source licensing, software may contain a mix of open-source licensed, commercially-licensed, freeware licensed, and other varieties of licensed software. Thus, it is feasible that a future version of the standard may develop a standardized method of identifying non-open source licenses contained within software packages.

Because the present focus of SPDX is the collection and presentation of the open-source software licenses contained in a software package, any license that is a candidate for inclusion on the SPDX License List must have the general attributes of an "open source" license.

Open Source Definition 
The terms "free software," "open source software," or their variants (FOSS, FLOSS, libre software, etc.) are defined differently by different organizations. At a minimum, all definitions of open source or free software include the characteristic that the source code be made available for inspection and modification and that the source code may be freely distributed. However, there are a number of other characteristics that vary depending on the policy focus of the defining organization. Even though the various definitions of open source software differ in some respects, there are certain fundamental characteristics commonly incorporated in all these definitions.

The SPDX Legal Team uses the definition promulgated by the Open Source Initiative (OSI) as the basis for analyzing candidate licenses for inclusion on the SPDX License List. 
