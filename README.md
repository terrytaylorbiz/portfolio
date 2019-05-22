# Portfolio description

These are a few of the docs I have written over the years. The target audience was technical and the focus was on useful, accurate content with a minimum of text and diagrams.


### 11_AD_GS_20160803_0925 partial.pdf (half of the doc deleted to make it smaller) 

The product --- AD (Automation Designer) was a PLM product that basically connected NX, EPLAN (electrical schematics) and TIA (PLC programming).

The task --- I was to write installation guides and user guides for AD. 

The challenges ---
1. As a contractor, I could not use client computers, access the client internal network, or sit near client employees. I was supposed to access the product via a very slow remote connection. From a practical perspective, this made the job impossible.
2. The client tech writers had little interest in how AD actually worked. The existing user guide was just a rehashed version of a software spec. The client tech writers were in the office only one day a week. 
3. The program and product managers were at a different location. I was supposed to work with developers who had little understanding of the big picture or how to create end user applications.
4. The Siemens documentation system (similar to Schema ST4) was great for managing large numbers of huge documents, but was not easy to use.

My activities ---
1. After several months I got permission to use a client computer, the internal network, and sit beside the developers (as long as I kept a low profile).
2. I installed (with a lot of assistance) AD, EPLAN and TIA on my own PC. I spent months learning how to use them and how to use AD to link them together. I also did a lot of hands on examples. I had very little assistance.
3. I created internal documents using MS Word that described very accurately and in detail how to get started with AD. The AD_GS_partial.pdf shown in this portfolio is a "distilled" version created with the client's doc system. Note that this system limited my abilities to create diagrams and control formatting.

The results --- The docs I created provide a lot of very useful info. Not only concepts, but critical details that you could only appreciate when actually trying to use a complex system like AD that was still under development. For example, in one dialog, if you left a space after an entry, the system would crash and your project that took 3-4 hours to build would be lost. 

Why I left --- The client office was in a beautiful building on the banks of the Rhein river, and I lived 5 minutes by bike in a converted monastery. The office atmosphere was very socialable and friendly. It was one of the most pleasant places I have ever worked. And my employer Goetz und Weise was the best.  But AD was still in development and was quite a challenge to use. It would be years before the product would be ready for beta release. I asked many times to move to the office where the program/product managers were located, but this was not going to happen. There were several new writers who took the traditional approach to documenting such a system (lots of text and no examples), and it seemed that the client was quite satisfied with that approach. It was time to move on. One thing is for sure, any new writer who wanted to learn how AD actually worked would have saved months of effort by reading the docs I wrote.
   
     
### 21_FGX_UG_20140307.pdf

The product --- The product was a firewall/router that was sold under several brand names. The documentation was released in English, Japanese and Chinese.

The task --- I was the documentation manager for a group of seven. 

The challenges ---
1. The existing docs were all very large and provided little useful info. Much of the content had been copied from books (the person responsible for this seemed to doubt that the absence of the typical English grammar errors made by Chinese writers was a clear indication that the text had been plagiarized). 
2. The doc and help sources were separate files. The files were scattered throughout the file system. There were many copies and no version tracking.
3. The program/product managers were located in a different city.
4. The working atmosphere within the team was rather unpleasant.

My activities ---
1. I created a very friendly American-style work atmosphere. The doc manager that I replaced was not the most effective manager or pleasant person to work with (the other colleagues were afraid of him). He resigned a few months after my arrival.
2. I deleted 40% of the existing user guide. The deleted text was useless text used to fill up the doc to give the impression that the writers were productive. They had plagiarized text from textbooks and other sources (I could tell from the perfect English). I cleaned up and reorganized the remaining text, added all the screenshots and diagrams, and then added most of the existing text (the team members were primarily busy maintaining the Chinese and Japanese versions of the doc).
3. I totally reorganized the existing user guide, deleted almost half the content, and then worked with the team to double the size of the doc (with useful content). Most of the examples and screenshots are from my PC. 
I installed the router-firewall in a VM on my laptop and started hands-on self study. I had limited experience with industrial grade router-firewalls. I spent a lot of time studying competitors' products and documentation (Juniper, etc.) and reading RFC's.
4. I drastically increased team productivity. I simplified my colleagues' work (especially by single-sourcing everything). I converted the existing documentation to single-source. Originally the PDF sources were Framemaker and the HELP sources were MS Word. There was a separate set of .fm and .doc files for different customer versions (the example you can download is branded for FGX, an Asian customer). I configured the FM files (using imported formats and variables) to create the required PDF, HELP, and customer versions from a single set of source files. This worked flawlessly (I still have the source files).
The results
1. The team spent most of their time creating original content (creating the single-source content was easy).
2. Several team members could manage the Framemaker single-source projects. There were very few problems (it was a clean design). 

Why I left --- It was a great experience. In particular my Chinese manager and the team were very friendly and helpful. But I left because of the following reasons.
1. After a year and half, one of the project/product managers from Beijing actually came by to talk to me. I was so 
happy that I might finally be included in their team discussions. He just wanted to ask me if I could teach his kid English.
2. The company would not confirm if they would offer me a new contract until two months before my existing contract expired. 
3. We had a small earthquake. Such an event made me think twice about spending so much time in a very large office building of obviously low construction quality.
As with every job experience in China I put together a few more pieces of the puzzle that is China. 
   
   
### 01_cit_doc_processes.pdf     
### 02_scqc_install_config_RELEASE.pdf         
### 03_scqc_install_config_TRAINING.pdf        

The task --- At HP Shanghai one of my tasks was to document a "synchronizer". The synchronizer was a program that would synchronize  database updates in systems A and B. My task was to document in detail how to configure a synchronizer between Service Center (SC) and Quality Center  (QC). 

My activities --- I found a developer who helped me setup SC, QC, and the synchronizer in a VM on my own laptop. I then created  an example synchronization configurations and documented in detail. I tagged Framemaker text so that I could create a release and internal version of the document from the same source files. I like simple text processes that allow multiple versions of a file to be created from a single source file.

The results --- The release version is 02_scqc_install_config_RELEASE.pdf. I used the internal version to demonstrate synchronizer installation/configuration at HP: 03_scqc_install_config_TRAINING.pdf. The screenshots are all from my personal PC (I installed all software on my PC and created the simple examples myself).

One of the other docs I wrote was 01_cit_doc_processes.pdf. I inherited a very complex doc project that was run on a VM in Paris, and converted to work on a local machine. I then wrote this doc to describe how to switch to a new doc system.

Why I left --- My first job in China was with a Taiwanese company, and then I worked for HP. I had the idea that I could find more interesting work with a "real" Chinese company, not realizing that the Taiwanese company and HP were some of the best employers you could find in China. My mistake.


### 31_fw_v50_gs_v15_RELEASE_000719_0954.pdf     
### 32_afw_v50_ug_v24_RELEASE_000719_1040.pdf        
### 33_pfw_v50_ug_v17_RELEASE_000719_1024.pdf         
### 34_obf_v50_ug_v11_RELEASE_000719_0940.pdf      
### 35_fwj_r34v11_gs_v02_DRAFTRELEASE_990908_1615.pdf         

The product --- Mynd was developing frameworks for Java and Smalltalk.

The task --- My job was to write the original docs.

The challenges --- There were few challenges, except for learning the software. Mynd was probably the best company I ever worked for.

Why I left --- Mynd USA bought PMS Micado Germany which became Mynd Germany. Mynd's fortunes took a turn for the worse, the projects were drying up, so I moved on.

--------------------------------------------------------------
