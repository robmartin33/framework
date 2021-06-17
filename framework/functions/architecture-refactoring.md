---

layout: default
tag: architecture-refactoring

---

# Architecture Refactoring

## Introduction
Architecture Refactoring is the process of making adjustments to an application or infrastructure to change the services used or the application design methodology used to better meet the requirements of the application or infrastructure. In the context of FinOps, the goal of architecture refactoring would typically be to achieve cost savings while maintaining or improving other aspects of the application's performance, reliability, security, resilience, etc. 

Architecture refactoring will typically be called for when using a lift and shift model of cloud migration. Applications which are not optimized to use native cloud services, and which may bring inefficiencies with them into the cloud which may increase costs.

Architecture refactoring may also be done when an organization adopts new models of software development, such as the use of containers or serverless architectures, or when new managed or platform services become available from cloud providers which could replace bespoke architecture components used previously. 

## Sample Implementation
As an example of architecture refactoring, imagine that an organization is working toward a deadline to close a datacenter, and determines that the best course of action will be to "lift and shift" applications currently running in the datacenter to cloud without modifying their architecture, design or components. One application is a batch application which runs on a dedicated virtual machine in the datacenter several times per day, producing a set of output data from collected logs in its database. If this virtual machine is moved to the public cloud as a running compute or VM instance, it will likely cost the company more to operate 24 hours a day, but will perform as it does on premises. After the datacenter has been closed and all applications moved, an engineering team can return to this application and may determine that the program which runs the batch job can be ported to a serverless model triggered by a time schedule. They may additionally determine that the licensed database which was installed on the server is too costly for the value this application brings, so may choose to instead use a license-included key value database native to the cloud provider instead to reduce costs further. 

## Common Approaches
List common approaches for using this function within a FinOps practice.
## Maturity Examples
Explain how this function may differ depending on the maturity level of the FinOps practice.

In each phase (crawl, walk, run) identify one incorrect practice that people are doing at this stage, to help them identify where they are at. If there are many, simply state the most common, easiest & most impactful one that will be identified by most organizations. Just state the incorrect practice, do not address why its bad or the impact. There will always be 1 incorrect practice at the crawl, there may not be incorrect practices at walk/run.
State the incorrect practice in a positive way - do not state the opposite of the best practice. Consider: Users are doing repetitve tasks manually. Do not use: Users are *not doing* things programatically.
 
Then state what customers should be doing at this stage to rectify the issue. If there are multilpe things to do - group them into a higher level concept, or state the most common and simple things. Each activity must result in a change or have something implemented, and be completed in the stage. Tasks like *Planning*, *considering*, or *producing* will not result in a change and should not be used. Partially completing an activity or completing an activity on a small scale such as *automate simple tasks* or *automate some tasks* followed by *automate all tasks* should not be used.
keep it simple, 1 or 2 sentences for each, focus on the outcomes or what is delivered, do not specify the busy tasks required to produce the output.


* **Crawl:**
* **Walk:**
* **Run:**
## Common KPIs
List and explain common KPIs that help track the effectiveness of the function. Alternatively, list favorable outcomes that represent success if specific KPIs aren’t clear enough.
## Cautionary Tales
Explain to users what to look out for or any pitfalls to avoid when building and implementing the function into their FinOps practice.

When looking at what they should do above, they can do the right things in the wrong way, or rely too much on one & not the other. Here you further guide them to ensure they're getting the right outcomes, by adding some more definition or calling out a way that a good thing can result in a bad result.

## Related Functions
List existing related functions and link to them here.
* [example]()
* [example]()
* [example]()
## Related FinOps Stories
** These stories are curated via site metadata and are sourced from the Stories repo. Visit that part of the FinOps Framework to contribute a story. **
## Resources
These links are provided as potentially relevant industry resources. The FinOps Foundation does not recommend any individual technology vendor and is not responsible for the content below.

** All of the below should be formatted as a list **
### Cloud-specific Best Practices
### Cloud-native Tooling
### Open Source
### Reading List
### Relevant FinOps-Certified Platforms
### Relevant FinOps-Certified Service Providers
### Relevant FinOps Training Partners
