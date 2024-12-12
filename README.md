I wrote the documents in this portfolio. The concepts, design and content are my own. The target audiences were technical and the focus was on useful, accurate content with a minimum of text and diagrams. I also have internal versions of these documents with background info, tech notes, etc. 

### 11_AD_GS_partial.pdf 

Note: This doc was created in a Siemens doc tool. I had little control over the pic formats, so the resulting PDF was very large. Git complained, so I deleted half of the doc.

The product was Automation Designer, a PLM product that connected NX, EPLAN (electrical schematics) and TIA (PLC programming). I wrote the installation guides and user guides. 

#### The challenges
1. As a contractor, I could not use client computers, access the client internal network, or sit near client employees. I was supposed to access the product via a very slow remote connection. From a practical perspective, this made the job impossible.
2. The client tech writers had little interest in how AD actually worked. The existing user guide was just a rehashed version of a software spec. The client tech writers were in the office only one day a week. 
3. The program and product managers were at a different location. I was supposed to work with developers who had little understanding of the big picture or how to create end user applications.
4. The Siemens documentation system (similar to Schema ST4) was great for managing large numbers of large documents, but was not easy to use.

#### My activities
1. After several months I managed to get permission to use a client computer, the internal network, and sit beside the developers.
2. I installed AD, EPLAN and TIA on my own PC. I spent months learning how to use them and how to use AD to link them together. I also did a lot of hands on examples I had very little assistance with these example apps).
3. I created internal MS Word docs that described very accurately and in great detail how to get started with AD. The AD_GS_partial.pdf shown in this portfolio is a "distilled" version created with the client's documentation system (I have an internal version with a lot of extra details). The client documentation system limited my ability to create diagrams and control formatting.

#### The results 
The docs I created provide very useful info, including concepts and critical details that you could only appreciate when actually trying to use a complex system like AD that was still under development (for example, in one dialog if you left a space after an entry the system would crash and your project that took 3-4 hours to build would be lost). 

<!-- Why I left --- The client office was in a beautiful building on the banks of the Rhein river, and I lived 5 minutes by bike in a converted abbey. The office atmosphere was very socialable and friendly. It was one of the most pleasant places I have ever worked. And my employer Goetz und Weise was the best.  But AD was still in development and was quite a challenge to use. It would be years before the product was ready for beta release. And I had basically hit the wall with AD; it was so complicated to do the most basic things that without a lot of help from the PM's I did not see how I could make much more progress. I asked many times to move to the office where the program/product managers were located, but this was not going to happen. Finally, there were several new writers who took the traditional approach to documenting such a system (lots of text and no examples), and it seemed that the client was quite satisfied with that approach. It was time to move on, and G&W did not have a different project for me.  -->
   
     
### 21_FGX_UG.pdf

Note:
- 21_FGX_UG.pdf was created from single-source source Framemaker files. There were 15 different versions of this doc just for the English version (there were also Japanese and Chinese versions). Therefore there may be some diagrams or text with small formatting or alignment problems. 
- Diagrams and screenshots were modified to minimize the resulting PDF file size. T
- The mission was to create a lot of info with limited resources for very technical readers (mission accomplished).
- The other team members who sometimes modified English content were non-native speakers of English.

#### The product
The product was a firewall/router that was sold under several brand names. The documentation was released in English, Japanese and Chinese.

#### The task
I was the documentation manager for a group of seven. 

#### The challenges
1. The existing docs had a great deal of text but provided little useful info.  
2. The doc and help sources were separate files. The files were scattered throughout the file system. There were many copies and no version tracking.
3. The program/product managers were in Beijing (I was in Shenyang).

#### My activities
1. I created a very friendly American-style work atmosphere.
2. I create original content. I deleted 40% of the existing user guide. The deleted text was useless text used to fill up the doc to give the impression that the writers were productive. They had plagiarized text from textbooks and other sources (I could tell from the perfect English). I cleaned up and reorganized the remaining text, added all the screenshots and diagrams, and then added most of the existing text (the team members were primarily busy maintaining the Chinese and Japanese versions of the doc). I installed the router-firewall in a VM on my laptop and started hands-on self study. I had limited experience with industrial grade router-firewalls. I spent a lot of time studying competitors' products and documentation (Juniper, etc.) and reading RFC's.
3. I drastically increased team productivity. I simplified my team members' tasks by converting the existing documentation to single-source. Originally the PDF sources were Framemaker and the HELP sources were MS Word. There was a separate set of .fm/.doc files for different customer versions (the example you can download is branded for FGX, an Asian customer). I configured the FM files (using imported formats and variables) to create the required PDF, HELP, and customer versions from a single set of source files. This worked flawlessly (I still have the source files).

#### The results
1. The team spent most of their time creating content.
2. The team members were able to manage the Framemaker single-source system that I had configured.
   
<!-- Why I left --- It was a great experience. In particular my Chinese manager and the team were very friendly and helpful. But I left because of the following reasons.
1. After a year and half, one of the project/product managers from Beijing actually came by to talk to me (I had sent emails to 3 PM's for a year and never received a reply). I was so happy that I might finally be included in their team discussions. He just wanted to ask me if I could teach his kid English.
2. The company would not confirm if they would offer me a new contract until two months before my existing contract expired. My visa to stay in China was with this company, so if they did not offer a new contract, I probably would have had to return to the USA to get a new visa.
3. We had a small earthquake. Such an event made me think twice about spending so much time in a very large office building of obviously low construction quality.     -->
   
   
### 31_cit_doc_processes.pdf, 32/33_scqc_install_config_RELEASE/TRAINING.pdf         

#### The task
At HP Shanghai one of my tasks was to document a "synchronizer". The synchronizer was a program that would synchronize database updates between 2 systems. My task was to document in detail how to configure a synchronizer between Service Center (SC) and Quality Center (QC). 

#### My activities
I setup SC, QC, and the synchronizer in a VM on my own laptop. I then created example synchronization configurations and documented in detail. I tagged Framemaker text so that I could create a release and internal version of the document from the same source files. 

#### The results
- 01_cit_doc_processes.pdf describes how I converted a very complex doc project that was run on a VM in Paris to work on a local machine
- 02_scqc_install_config_RELEASE.pdf is a release version for end customers.
- 03_scqc_install_config_TRAINING.pdf was used to demonstrate synchronizer installation/configuration at HP.

### 41_fw.pdf, 42_afw.pdf, 43_pfw.pdf, 44_obf.pdf, 45_fwj.pdf         

#### The product
Mynd developed frameworks for Java and Smalltalk.

#### The task
I wrote the original docs.

#### The challenges
The product was technically quite challenging.

<!-- Why I left --- Mynd USA bought PMS Micado Germany which became Mynd Germany. Mynd's fortunes took a turn for the worse, the projects were drying up, so I moved on. -->

--------------------------------------------------------------
