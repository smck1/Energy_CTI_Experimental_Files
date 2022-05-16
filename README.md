# Purpose (Experimental Files)

This Github contains the MISP (https://github.com/MISP/MISP) report file for experiments in the paper: 
A. Paice and S. McKeown, “Practical Cyber Threat Intelligence in the UK Energy Sector” in 2022 International Conference on Cybersecurity, Situational Awareness and Social Media, 2022, 


The DOI and author's copy link will be provided here after the conference in June 2022.

## Paper Abstract 
The UK energy sector is a prime target for cyber-attacks by foreign states, criminals, "hacktivist" groups and terrorists. As Critical National Infrastructure (CNI), the industry needs to understand the threats it faces to mitigate risks and make efficient use of limited resources. Cyber Threat Intelligence (CTI) sharing is one means of achieving this, by leveraging sector wide knowledge to combat ongoing mutual threats. However, being unable to segregate intelligence or to control what is disseminated to which parties, and by which means, has impeded industry cooperation thus far.

The purpose of this study is to investigate the barriers to sharing and to add to the body of knowledge of CTI in the UK energy sector, while providing some level of assurance that existing tooling is fit for purpose. We achieve these aims by conducting a multivocal literature review and by experimentation using a simulated Malware Information Sharing Platform (MISP) community in a virtual environment.

This work demonstrates that trust can be placed in the open-source MISP platform, with the caveat that the sharing models and tooling limitations are understood, while also taking care to create appropriate deployment taxonomies and sharing rules. It is hoped that some of the identified barriers are partially alleviated, helping to lay the foundations for a UK Energy sector CTI sharing community.

# Files

## mispeventsall.json.ADMIN.json

This is a STIX (JSON) file containing the ingested reports used in the experiment. This can be imported into a MISP VM instance (https://vm.misp-project.org/), though note that items are assigned unique IDs and therefore repeat experiments would need to revert to a prior snapshot, rather than re-import the same items.
The sharing models and taxonomies used in the experiments are relatively small and can be easily created from the paper.



