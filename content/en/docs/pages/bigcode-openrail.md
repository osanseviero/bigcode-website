---
title: "BigCode OpenRAIL-M - FAQ"
description: ""
lead: ""
date: 2020-11-12T15:22:20+01:00
lastmod: 2020-11-12T15:22:20+01:00
draft: false
images: []
menu: 
  docs:
    parent: "pages"
weight: 620
toc: true
---
We are releasing StarCoder, which is licensed under the BigCode OpenRAIL-M license agreement, as we initially stated here and in our membership form. 

## What is an OpenRAIL license agreement?
Open Responsible AI Licenses (OpenRAIL) are licenses designed to permit free and open access, re-use, and downstream distribution of modifications of AI artifacts, for research, commercial or non-commercial purposes, as long as the use restrictions present in the license agreement always apply (including to modified material). For more information, please access the RAIL Initiative post.

## Why Open?
The term “Open” is to indicate that the license agreement enables royalty free access, downstream use and re-distribution of the licensed material, and distribution of any modifications of it.

You can use any type of legal agreement you want to share the model or modifications of it. This will be possible under the sole conditions of including in the legal agreement:
the license agreement paragraph related to the responsible use of the model (i.e., paragraph 4) or a similar provision that accomplishes the same purpose, and, 
the use restrictions (i.e., Attachment A) or a similar set of restrictions that accomplish the same purpose.

See FAQ below: “Do use restrictions apply to modificatins of the model?”.

## Responsible?
Responsible AI licensing is a mechanism that is part of -and interacting with- a broader system of AI governance instruments and processes, such as Model Cards and regulations.

The BigCode OpenRAIL-M license agreement is designed to promote responsible downstream use and sharing of the model by including a set of use restrictions for which the model cannot be used. In the case of the BigCode OpenRAIL-M, the restrictions are mainly inspired by BigScience’s approach to the licensing of LLMs, and also include specific use cases where we believe code generation models could be used as a harmful instrument due to either the intent of the user or the technical limitations of the model.

## ‍What does the “M” stand for?
“M” stands for “Model”, which is the artifact being licensed under this license agreement and subject to use restrictions. See the naming conventions for RAIL Licenses here.

## Is this an Open Source license?
This is not an open source license according to the Open Source Initiative definition, because it has some restrictions on the use of the model. 

## What are we sharing?
We are sharing a Large Language Model for code generation -StarCoder- developed under the BigCode project. Any source code relevant to the BigCode ML models is licensed under the Apache 2.0 license.

## Why should BigCode decide what is appropriate or not regarding the use of the model?
As creators of the model, we think about how our work could be used. We believe we should do as much as we can to prevent possible harms from our work while releasing it on an open basis, especially if there are possible use cases that are incompatible or inappropriate with the model performance and/or capabilities of it.

## What has been modified from the BigScience OpenRAIL-M license?
This license agreement is a new version of OpenRAIL evolving from the first set of OpenRAILs created with BigScience. There are several core modifications:

- Distinction between the IP licenses granted and use conditions from a contractual perspective
- Definitions: explanatory documentation; harm; modifications of the model; share.
- Paragraphs 4 and 5 have been considerably modified.
- Paragraph 7 of the license agreement no longer requires users to undertake reasonable efforts to use the last updated version of the Model, as is the case in the BigScience OpenRAIL-M license agreement. 
- Attachment A includes a new restriction:
Restriction (c) forbidding the use of the Model to generate and/or disseminate malware. 


## When defining “Data”, what do you mean by “information”?
“Information” can include - but is not limited to - natural language, code in any coding language, images, video, audio.

## When defining “Output”, what do you mean by the “results of operating the Model”?
The results of operating the model can be understood - but not limited to - as the data generated by the model in a specific format. For example, the code generated by the model given a specific prompt, or, the code suggestion generated by the model when embedded in a co-pilot UI. 
## Can you give examples of “Modifications of the Model”?
Modifications to the Model include - but are not limited to:
- Quantization, fine-tuning, prompt-tuning, using adaptors, and other related methods for updating a model.  This includes, use of intermediate data representations via distillation methods
- A model trained based on methods for the generation of synthetic data by the Model for training another model
- Finetuned version of the Model

## What’s the scope of “Explanatory Documentation”?
Explanatory Documentation refers to any type of documentation or technical specifications accompanying the Model or Modifications to the Model. For example, model cards are one of the most -if not the most- used documentation format when distributing a model. Model cards describe general and key characteristics of the model, such as performance, technical limitations, or data sources. Tools such as model cards (or data cards) are essential to foster AI documentation along the value chain and access to basic core information of ML artifacts, such as models or datasets.

Some users may not be familiar with model cards; thus other formats/ways to document the model key characteristics are also valid. For example, Meta has its AI system cards, while Microsoft has its Transparency Notes. Another type of technical specification that you would normally attach to your model when distributing and/or commercializing it also works (papers, tech specs, etc.).

## Can you give other examples on the “Use” of the Model?
“Use” of the Model is anything that has to do with operating the model, other examples besides the one given in the agreement can be: an end-use application such as a chatbot or code co-pilot UI.

## Do use restrictions apply to Modifications of the Model? 
Yes. The use restrictions in the license agreement have been designed to be applicable in downstream contractual terms of any modified versions of any of the BigCode models offered and/or released by a downstream user. The sharing and use of any Modifications of the Model (as defined in the agreement) should be governed by either the same use restrictions, or, a similar set of use restrictions accomplishing the same purpose.

## What do you mean by “a similar set of restrictions” in paragraph 5.1? 
Restrictions implemented with a different wording and/or format that accomplish the same purpose as the ones present in Attachment A. For example, it might happen that you would prefer a different wording because you already have commercial contracts with similar restrictions worded differently that accomplish the same purpose. 


When it comes to the format, it might also happen that placing the restrictions under an Attachment does not work for you, and you would prefer to place them with a different contractual format. One example of a different contractual format that would comply with the license is commercial contracts that require that a product incorporating the model is used in accordance with the product documentation and including the use restrictions in the product documentation.

## According to paragraph 5.1, do I have to place paragraph 4 in my contractual terms when sharing the Model or Modifications of the Model?
We understand that you might be sharing the Model or Modifications of the Model under a different contractual format (e.g. a commercial SaaS contract). In this case, according to paragraph 5.1.b, you may adapt paragraph 4 to your specific contractual format and wording; however, you must keep the intent of it: **Compliance with the restrictions in Attachment A is a condition to the use of the Model or Modification of the Model, and if the Model is used, your users must agree not to Use it for the specified restricted uses set forth in Attachment A or the similar set of restrictions provided by you under paragraph 5.1.**

## Can you give me an example for paragraph 5.1.? 
Imagine a company that wants to use a BigCode model in order to develop a version of a coding assistant. The company finetunes/modifies the model to be the technical backbone of the coding assistant app. 


Firstly, these actions will be governed by the RAIL license agreement. Secondly, according to the terms defined in our RAIL license agreement, this coding assistant app is considered a Modification of the Model. 


Thus, the use of the app will be governed by the use restrictions defined in the RAIL license agreement, and accordingly, when commercializing the new version of the Model, the company will have to place either the same use restrictions -or a similar set of use restrictions- on end users as part of the subsequent Terms of Service of the specific API-based coding assistant app.


The company uses similar restrictions in other contractual terms they have for their products and R&D agreements with partners. Depending on the agreement, they either place use restrictions as a contractual clause in the agreement with a different wording, or, they place them as part of the “Compliance Documentation” which is incorporated by reference in, or attached to, the agreement for its customers/partners. Thus, the company realizes it’s easier and more straightforward for them to choose option “b” of paragraph 5.1 in order to draft the use restrictions differently and choose the format they want within their own contractual setting (instead of having to heavily adapt their standard contractual forms to include Attachment A of the license agreement).

## What do you mean by Explanatory Documentation “of the same or better quality”?
Explanatory Documentation of the same or better quality means information that, at least, informs the public on the same characteristics as the original Model with a similar degree of accuracy of the information displayed. 

For example, a finetuned version of StarCoder (i.e. a modification of the model) will have to include in its model card or documentation the same sections and accuracy of information as in the StarCoder original model card, and in addition, document the modifications made to the model.

## Can the output generated by the Model be subject to 3rd party rights?
Yes. The Output You generate using the Model may be subject to third party rights or licenses, including open source licenses. This is why we developed the StarCoder: Dataset Search, in order for users to check whether the code generated by the model belongs to an existing open source repository, and if so, check the license and comply with it.

## Do I have to disclaim that the outputtted code snippets were generated by a model?
According to restriction (f) you cannot use the model to generate code or distribute code without intelligibly disclaiming that the code was generated by the model. What does this mean in practice? If you finetune a BigCode model, embed it into an app designed to be a code assistant, and plan to distribute the app as a SaaS, you shall make it clear for users of your app that the code generated by it is generated by a model. It might sound obvious for you, but not for others. It is important to be transparent with your users. 


## Is it possible for the licensor to remotely restrict the use of the models? If so, what does it mean? 
The model itself has no built-in mechanism for it to be restricted. However, if the model is hosted via an API, restricting access remotely can be possible as the API access key can be revoked. 

## Is this solely a copyright license?
No. This is a contractual agreement that includes a copyright license, a patent license, and conditions on the use of the model.
## What do you mean by “model failure or malfunction” in paragraph 11?
Model failure or malfunction may mean -but is not limited to- offensive generations, toxic outputs, inaccurate outputs, or biased outputs.
## Restrictions in Attachment A:
Restrictions explained or for which examples are given below are those which can be directly applied to a code generation model. The other restrictions are present as we are releasing the model on an open basis, and thus, it can be modified and re-trained to accomplish a different set of general tasks. 

## Restriction (a) 
*“In any way that violates any applicable national, federal, state, local or international law or regulation”*

You cannot use the model or modifications of the model against the law. BigCode is going to be used all over the world and some jurisdictions might not have legal frameworks protecting individuals against some of the restrictions in the license agreement. Therefore, whereas national legal frameworks may vary, the use restrictions from a contractual perspective are going to be the same.
## Restriction (c) 
*“To generate and/or disseminate malware (e.g. ransomware) or any other content to be used for the purpose of Harming electronic systems”*

We understand that “malware”, according to the NIST definition, already includes the intent of harm. For example, using a dataset composed of  source code, signature, or Indicators of Compromise (IOC) that are known to be malicious and finetune a BigCode model with it in order to enable the automated generation and/or distribution of malware or related code.

## Restriction (d) 
*“To generate or disseminate verifiably false information and/or content with the purpose of Harming others”*

The model or modifications of the model cannot be used to generate code and attribute authorship to an individual who did not develop the code and is not aware of this misrepresentation. 

## Restriction (f) 
*“generate or disseminate information (e.g. images, code, posts, articles), and place the information in any public context (e.g. bot generating tweets) without expressly and intelligibly disclaiming that the information and/or content is machine generated”*

For example, if you finetune the model, embed it into an app designed to be a code assistant, and plan to distribute the app as a SaaS, you shall make it clear for users of your app that the code generated by it is generated by a model. It might sound obvious for you, but not for others.It is important to be transparent with your users. 

## Restriction (h) 
*“Impersonate or attempt to impersonate human beings for purposes of deception”*

For example, the model or modifications of the model cannot be used to generate code and attribute authorship to an individual who did not develop the code and is not aware of this misrepresentation. 
Restriction (i) 
“For fully automated decision making that adversely impacts an individual’s legal rights or otherwise creates or modifies a binding, enforceable obligation without expressly and intelligibly disclaiming that the creation or modification of the obligation is machine generated”

For example, you cannot use the model to automatically generate and action a smart contract without disclaiming that the contract was generated and activated by a model.

## Does the license agreement cover every harmful use case? 
No. We recognize that the list of use restrictions does not conceivably represent “everything” one could possibly do with our work. We focus on use cases that can be a source of concern.

## Do I have to click “I accept” to accept the license agreement?
Yes, you must accept the license agreement before you can access the model.

## What if I do not understand some of the restrictions in Attachment A of the license agreement?
Community feedback is essential for us. We are grateful to receive it and answer any questions related to the license agreement. Drafting use restrictions that everyone agrees on and understands for ML models is a challenge. There is a balance to be struck between restrictions being too generic, on the one hand, and restrictions being too narrow and not covering potentially harmful scenarios, on the other hand. We are open to your comments.

## What other RAILs are out there?
Since the release of the BLOOM RAIL license in May 2022, there has been a proliferation of RAILs based on either the structure and content of the latter or just the aim of promoting responsible use of ML models, as OpenAI does with its Usage Policies or Meta does with its licenses for OPT-175, BB3, SEER, LLaMA. Other RAIL licenses based on the BLOOM RAIL have been released, such as BigScience OpenRAIL-M, CreativeML OpenRAIL-M, SIL RAIL-M 1.0, and OpenRAIL++M. 

## Is there more information?
Yes! Please have a look at the RAIL Initiative content.
Co-authors of the BigCode OpenRAIL-M license agreement:
Carlos Muñoz Ferrandis, Jennifer Robinson, Luis Villa, Danish Contractor, Jenny Lee, Thierry Paul, Sean Hugues, Leandro de Werra, Harm de Vries, Huu Nguyen, Yacine Jernite, David Lansky, Chris Akiki. 

## Can I use the license agreement for my own models?
Yes. The BigCode OpenRAIL-M (i.e. the document itself) is licensed under a CC-BY-4.0. You can use it for your models or modify it for your own needs.

# Other governance considerations related to the use of the model

## What if the model outputs code snippets belonging to an already existing repository under a permissive license? What about providing attribution and license notice?

Besides the opt out tool and process we developed for the community (“Am I in the Stack?”), we developed StarCoder: Dataset Search, a tool enabling users to identify whether the code generated by the model belongs to a code repository, in order for the user to be able to inspect licensing requirements and comply with them when using and distributing the code.

## What if the data used to train the model includes malicious code that was not previously detected in the dataset?
It is important that researchers and developers can trust the source of data used to train a model. Please, only use models and datasets from sources that you trust. The model cards should specify which dataset(s) or subsets of it were used. The data card of the dataset used to train the models should be reviewed so that the developer understands the limitations and social impact of using the dataset - at the time of writing, 142 parquet files in The Stack had been detected (using ClamAV) and marked as harmful, and developers are cautioned about using these files. Since new malware signatures for data contained in the dataset may only become known after the dataset was released, users should consider doing their own scan of the dataset using the most current anti-virus malware software before using the model. Users could also consider using a tool other than ClamAV to provide a second layer of scanning. If new malware is detected, please report these findings to contact@bigcode-project.org.

Furthermore, code generated using the model should be scanned by the developer to check for malware before it is used (as the malware could impact the users' own machines) and/or distributed, as the dissemination of malware could be considered a criminal activity, and users are responsible for the inputs (prompts) and outputs (generated text/code) from using the model or an application powered by the model. 

Developers should include this kind of code review and risk assessment throughout their software development lifecycle. Developers are ultimately responsible for adhering to practices for secure coding when building downstream applications or working with generated code. There are likely additional considerations not covered in this FAQ, and users should consult a security expert to review the unique aspects of their own projects.

Lastly, developers should inform end-users of their applications that there is a risk of malware, and take the necessary precautions such as using up-to-date anti-virus malware software. End-users of code generated by a downstream application from the developer should also be aware of their responsibilities to scan the code before using it and/or before they publish their own downstream applications. 

## What if the model hallucinates sensitive data in its output?
It is possible that a large language model can hallucinate and output sensitive data such as Personally Identifiable Information (PII). This is clearly an unintended output, but it is a real risk that should be managed deliberately and with care. While the dataset may already have been screened for PII, some PII may not have been completely or accurately detected, annotated, or anonymized. As with malware, users of the model are responsible for adhering to laws and best practices pertaining to the handling and processing of PII in their own use of the model.

Contact details: contact@bigcode-project.org