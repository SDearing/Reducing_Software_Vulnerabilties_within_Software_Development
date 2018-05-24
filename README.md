# Reducing Software Vulnerabilties within Software Development
## Introduction
In this report I will investigate the possible vulnerabilities in software during development, how these vulnerabilities affect businesses and how these vulnerabilities can be reduced. Software development is the process of creating software to fulfil certain criteria or solve a problem, in a basic sense software is developed by first creating a design and a development plan, then the actual coding of the software and finally testing and further maintenance on the software even when it is released to the public, however the order stages of development and how software is developed is determined by the software lifecycle chosen by the development team. A software vulnerability is a weakness or error in a system that can be exploited by an attacker with the aim of changing how the system works. To investigate this report, I will document secondary data in the form of case studies, in these case studies I will analyse the vulnerabilities they were affected by, how those vulnerabilities were exploited and how they mitigated the vulnerabilities. Then I will be outlining my own primary research answering the following questions: Are software development students competent at describing software vulnerabilities and does that understanding grow with experience? Does the average individual take actions to reduce vulnerabilities with their accounts online? And Do individuals understand software vulnerabilities as well as they think? 
## Software Vulnerabilities within Software Development
While software is in development, multiple parts of the system will be vulnerable. These vulnerabilities can be exploited which could lead to data within the system being lost of corrupted or even stolen.

One vulnerability during software development is the use of re-usable code. Re-usable code refers to code created by a third-party which a developer uses in their software. Re-usable code can be beneficial to a developer as it can save them time in the development process, especially if they are unfamiliar with the section of software they are coding, however using third party code can lead to significant problems in software. For instance, if multiple developers use the same ‘reliable’ code in their software and later the code is found to have a vulnerability, it would lead to all the software with that code implemented to be at risk from the same type of exploit, leading to the software being much more likely to be maliciously attacked.

Another possible vulnerability is the coding language that is used by the developer. Coding languages are usually created to create certain types of software, for example the language JavaScript is used to make web pages whereas C++ is more suited to make applications and games. However, some coding languages have idiosyncrasies, which are unusual behaviours of the code, which could be exploited by hackers. For example, web page languages are more vulnerable to attacks such as SQL injections.

## Case Studies
To fully understand the different software vulnerabilities, we must look at real-life examples of when software vulnerabilities have been exploited and the consequences associated with those vulnerabilities. These examples are referred to as case studies and are important to analyse to make sure that future developers learn from the mistakes made by other companies.
### Case Study 1: Equifax Hack 2017
In 2017, 143 million Americans had their personal information stolen by hackers due to a major vulnerability in the company Equifax’s software, putting millions at risk of identity theft.  Equifax is a credit reporting agency based in America, which calculate credit scores for consumers. When a consumer applies for a bank loan, the bank requests credit history and credit score information from companies like Equifax. This means that Equifax holds a lot of personal information of consumers such as: the consumer’s name, social security number, birth date, addresses and even their driver’s license numbers. 

On July 29th Equifax discovered a data breach, Equifax then waited until it “observed additional suspicious activity” a day later to take the affected web application offline. Then on August 2nd Equifax contacted Mandiant, a professional cybersecurity firm, to assist Equifax in discovering the magnitude of the breach. Mandiant determined that a series of breaches had occurred from May 13th to July 30th, giving hackers more than enough time to steal huge amounts of personal data.

According to Equifax, the attack occurred due to a security flaw in a tool the company used to make web applications called Apache Struts. Apache Struts is used by many large businesses and government organisations and Equifax used it to create a website where customers could go to log issues with their credit reports. The flaw allowed hackers to take control of the website. However, the flaw was found back in March by the cybersecurity arm of the US department of Homeland Security. Equifax even admitted that they were “aware of this vulnerability at that time and took efforts to identify and to patch any vulnerable systems” and yet the flaw was still exploited months later. 

After the attack Equifax was heavily criticized by security experts for not moving fast enough. So, what can be learned about this case study is that if a developer is using third party software they need to be aware of the risks and test the third-party software for vulnerabilities to assure its robustness. 

## Primary Research
To understand the vulnerabilities in software during development, I have conducted a questionnaire that I have given to students within the college that study software development and some that do not, to test their knowledge on software vulnerabilities. The main aim of the questionnaire was to answer 3 questions:
1.	Are software development students competent at describing software vulnerabilities and does that understanding grow with experience?

It is vital that upcoming developers have a good understanding of software vulnerabilities so that they can reduce vulnerabilities in their code. To answer this question, I have included in the questionnaire questions regarding different software vulnerability terms, this is so I can determine the participants knowledge on software vulnerabilities. I have also added a question to the questionnaire that asks them their experience in coding this is so I can determine who are the programmers and who are the students with no experience.

2.	Does the average individual take actions to reduce vulnerabilities with their accounts online?

In an increasing digital world, it is vital that people with accounts online take necessary precautions to ensure that their data on those accounts remains safe. To test this, I have tested how secure they make their passwords by asking, whether they use the same password for multiple accounts and whether they include any personal information in their passwords. 

3.	Do individuals understand software vulnerabilities as well as they think?

In the questionnaire I ask the participant what, in their opinion, is their understanding of software vulnerabilities. There answer to this question will be compared to the questions about software vulnerabilities to see if they are correct in their opinion or if their understanding is not as well as they think.
### Table of Results
Below are the results from my questionnaire, the excel file can be found [here.](https://github.com/SDearing/Reducing_Software_Vulnerabilties_within_Software_Development/blob/master/PrimaryResearchResults.xlsx)

![ResultsPt1](https://github.com/SDearing/Reducing_Software_Vulnerabilties_within_Software_Development/blob/master/TableofResultsPt1.PNG)

![ResultsPt2](https://github.com/SDearing/Reducing_Software_Vulnerabilties_within_Software_Development/blob/master/TableofResultsPt2.PNG)

![ResultsPt3](https://github.com/SDearing/Reducing_Software_Vulnerabilties_within_Software_Development/blob/master/TableofResultsPt3.PNG)

![ResultsPt4](https://github.com/SDearing/Reducing_Software_Vulnerabilties_within_Software_Development/blob/master/TableofResultsPt4.PNG)

### Data Analysis
To analyse my results I will be using multiple tools and techniques to create meaningful conclusions. I will be using excel as a tool to create my diagrams to present results.
#### Cross Referenced Questions
The first technique I will be using, will be to use the data from my questionnaire to answer my previously mentioned questions.
##### Are software development students competent at describing software vulnerabilities and does that understanding grow with experience?
To answer this question I will be looking at the questions 1, 2, 3, 7 and 8. Questions 1 and 2 show me the participant's experience with coding and finding software vulnerabilties. Questions 3, 7 and 8 test the participants knowledge of software vulnerabilties, these questions were: What types of software vulnerabilties are you aware of? Have you head of buffer overflows and unvalidated inputs? and If yes, could you please describe the terms to the best of your ability. The first thing I need to establish is how many of my participants have experience in coding below is pie chart showing the distribution of participant's coding experience.

![Q2Chart](https://github.com/SDearing/Reducing_Software_Vulnerabilties_within_Software_Development/blob/master/How%20much%20time%20have%20you%20spent%20practising%20studying%20software%20development%20Pie%20Chart..PNG)

As you can see just over half of the participants had no experience in programming and those with experience mostly had only 1 year of experience. To answer this question I am now going to focus on the participants qualitative results from question 3, 7 and 8. As qualitative results can be hard to analyse I am going to count the frequency of participants that got all answers right, 2/3 answers right, 1/3 answers right and no answers right and display these results in a bar graph.

![correctanswersgraph](https://github.com/SDearing/Reducing_Software_Vulnerabilties_within_Software_Development/blob/master/frequencyofcorrectanswers.PNG)

From these results, we can see that students with no experience in coding were most likely to get all questions to do with software vulnerabilties wrong. However, an interesting result from this analysis is that participants with the most experience in programming had the second highest frequency to get all questions wrong and only participants with 1 year coding experience were able to answer all questions correctly.

So from these results we can infer that software development students are mostly competent at answering questions about software vulnerabilties. However, from these results there is no evidence that a students understanding of software vulnerabilities increases with experience in programming.
##### Does the average individual take actions to reduce vulnerabilities with their accounts online?
To answer this question I will focus on questions 4 and 5. Question 4 asks if the participant uses the same password for multiple accounts and question 5 asks if their passwords contains any personal information. If a participant was taking actions to reduce their vulnerabilities online, they should answer both questions with no. I will analyse the results by making a bar graph for both questions.

Question 6:

![Q6](https://github.com/SDearing/Reducing_Software_Vulnerabilties_within_Software_Development/blob/master/Do%20you%20use%20the%20same%20password%20for%20multiple%20accounts%20graph.PNG)

Question 7:

![Q7](https://github.com/SDearing/Reducing_Software_Vulnerabilties_within_Software_Development/blob/master/Do%20your%20passwords%20contain%20personal%20information%20graph.PNG)

The results from question 6 show that the same amount of participants use the same password for accounts than participants that don't. This suggets that using the same password for multiple accounts is still a common practise with students. The results from question 7 differ slightly from the results of question 6 as a higher frequency of participants picked the more secure option, which is to not have personal information in their passwords. From these result I can infer that most students take action in reducing vulnerabilties in their accounts by making sure they have secure passwords, however there is still a large minority that do not have secure passwords.

##### Do individuals understand software vulnerabilities as well as they think?
In the final question of my survey I asked the participant to rank from 1-10 how well they thought they understood software vulnerabilities
### Valid and Meaningful Conclusions
From the analysis of the first aim of my investigation I can conclude that having experience in coding is beneficial in understanding software vulnerabilities. However, from the lack of more experienced programmers answering all questions correctly, I would suggest that courses studying software development do not focus on software vulnerabilties enough, as more advanced students are forgetting key details to do with software vulnerabilties.
## Reflection of The Value of Undertaking This Research
