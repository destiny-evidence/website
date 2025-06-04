+++
#date = '2025-07-09'
title = '2025-07-10 | DEST Hackathon (Potsdam, Germany)'
summary = 'Focusing on evluations and innovative user interfaces'
+++

*July 10–11*
{{< figure src="../img/pik.jpg" width="100%" >}}

This is [the signup form](https://cloud.pik-potsdam.de/index.php/apps/forms/s/sZQErTQcQcWBxZRNKbWtdfMJ) for the first
DEST hackathon in [Potsdam on the Telegrafenberg](https://www.pik-potsdam.de/en/institute/contact/where).
The event is organised by
the [Evidence for Climate Solutions](https://www.pik-potsdam.de/en/institute/departments/climate-economics-and-policy/research/evidence-for-climate-solutions)
group at PIK as part of the [Wellcome-funded DESTinY project](https://destiny-evidence.github.io/website/).

Everyone who is interested in **AI for digital evidence synthesis** / technology assisted reviews (text mining to
summarise findings published in research articles) is warmly welcome!
The main themes for the workshop will be **user interfaces** and **evaluation of AI-assisted methods** to automate (
parts of) the synthesis pipeline.

Example projects could be to compile a list of existing (interactive) platforms to share syntheses and to collect useful
features that we should be able to replicate.
At the same time, we might also want to test some of our early demonstrator products to measure real-world benefits over
conventional approaches.

This is **not just for people with programming skills**; anyone is needed and warmly welcome. Some experience in
evidence synthesis (meta-studies, systematic maps, systematic reviews) is helpful.
Data scientists get the opportunity to work with large human-annotated datasets to evaluate their tools or experiment
with ideas such as preparing (semi-)supervised fine-tuning data for domain-specific LLMs.

The hackathon is co-hosted with the DESTinY and ICASR meeting.
If you already indicated your hackathon participation there, you don't need to sign up here too.

## Themes

We are still working on preparing topics and we won't limit the choices by our proposals.
This list is to give you an idea of potential projects and projects where someone committed to prepare input.

* **Towards acceptable minimum quality requirements** for AI use in evidence synthesis; using results from our large
  community survey.
* **Effective user interfaces**: From a collection of interactive web interfaces, we want to run usability studies to
  find out what actually improves workflows. We'd also like to sketch out visions for next-generation data sharing
  platforms and tools for evidence synthesis.
* **Stopping methods:** Priority screening has the potential to save a lot of effort by seeing (potentially) relevant
  records first and then stopping early. Following the ICASR meeting, we'd like to invite others to contribute to our
  benchmarking framework.
* **Enhancement processes:** Play with the new DESTinY repository, to learn how to use the interchangeable formats that
  we will base our future developments on. This helps us to collect feedback and you could bring your favourite tool
  into the DESTinY ecosystem.

## Proposed projects

**Handbook for AI accuracy**    
We know that automtion in digital evidence synthesis tools with the help of AI may not lead to perfect results. Hence we need to fomulate tangible guidelines for accuracy requirements for different use-cases to inform the development of such tools. In this project, we will use the results of our survey sent to users and producers of evidence. How good is good enough? Are there ethical concerns? No programming skills required. 

**Effective user interfaces for synthesised evidence**    
We are currently building a powerful repository of scientific and non-scientific publications and the infrastructure around it to support enhancement processes to add knowledge to existing records. The key challenge will be to enable users to effectively explore this wealth of information. In this project, we will collect existing interfaces and evaluate the efficacy for different use-cases, such as identifying research gaps, finding relevant literature for a review, or information to support policy-makers. We also want to set up and conduct user studies to see if using such tools is actually faster or leads to more complete information. No programming skills required. 

**The stopping game**     
We all know that staring at an incomplete plot of the cumulative number of included abstracts over the number of screened abstracts is not a good way to determine when to stop screening when using prioritisation. Stopping methods are here to help, but are not perfect either. Max Callaghan started to work on a simulation game that slowly plots such a gain curve and users have to decide when to stop. He’d like to develop this further and collect data from this fun experiment. Programming skills required if you want to develop something, no programming skills required for testing and feedback. 

**Knowledge transfer**    
Research, particularly case-studies, are unfortunately not well distributed across all the world regions. However, there might still be learning potential by identifying which evidence-sparse areas are comparable to areas with more research and transfer knowledge from there to evidence-based decision-making. Can we add confidence scores on “how well” the available evidence fits another case? Reviewing the eBASE transferability toolkit. Some programming skills required for data wrangling, no programming skills required to steer and inform the project. 

**Screening with large language models**    
Evaluation of using LLMs in automating screening updates of living reviews, and ways of ensembling binary LLM predictions within active learning processes; stopping rules for llm-based priority screening; ways to make methods based on LLMs more reliable or to make it easier to spot mistakes made by the machine  

**Data sharing circle**    
We all need data for development and evaluation of automations. We critically need for form a working group to foster data sharing and standardising the formats with respect to which meta-data is needed (e.g. structured inclusion criteria / codebooks), licences for re-sharing, data structures, … Everyone can participate here, also part-time to just drop in and share what data they know of or have available. 

**Build your DESTinY robot**    
The new DESTinY repository will use modular processes to enhance the data in the knowledge base which we currently call “robots”. We invite everyone to check out our early demonstrator and the SDK to add their favourite data mining or information extraction tools. Programming skills required. 

**Produce synthetic abstracts**    
Current systematic syntheses are struggling: Abstracts are increasingly hard to get and the ones we have vastly differ in their usefulness (for example short 130 word abstracts). To mitigate this, we would like to use synthetic summaries that follow a standardised format. This helps downstream automations and should improve human screening efforts. In this project, we want to run early experiments to figure out how those summaries should look like (no programming required, information specialists very welcome) and how to get there (potentially some programming required). 

**Build a living evidence dashboard**    
Eventually, the DESTinY repository will be an open community resource of living evidence. This means, that the available knowledge should always be up-to-date. People in the field might want to stay informed of the latest trends, so we’d like to build dashboards or helpful newsletters that feature shifts and other news. Help to design (no programming) and prototype (programming needed) such tools. 

**Capability testing**    
There are a bunch of concrete project ideas to test the capabilities of AI. They may or may not take place, interest groups and form spontaneously. Some examples: 
* Testing and evaluating digital tools for literature screening and data extraction on ex-post effectiveness of carbon pricing studies  
* Knowledge graphs from entities in publications (e.g. PICO by experiment) and relationship between entities and the strength of 	these relationships. 
* Causality mining from text 
* Who can build the best classifiers using gold standard data? 
