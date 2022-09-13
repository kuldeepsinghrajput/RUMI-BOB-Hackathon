## Add your idea files to this directory. Please don't rename this directory.
# Automatic-Cheque-Processing-System

# Problem Statement

Bank of Baroda is one of the largest banks in India with over a hundred years of tradition of banking excellence. We have our customers in every corner of India and key markets globally and we have been constantly striving to deliver the best Banking services to them. In this age of technology-led disruption, the bank has been investing in market-leading technologies to improve and often disrupt the traditional banking paradigms. With Bank of Baroda Hackathon 2022, we are looking for the brightest technical minds in India to come up with new age, technology-led innovative ideas which can shape how we deliver banking services at our Bank. The best prototypes, bringing to life technology-led innovations for Bank of Baroda, will not only win handsome awards but may also see their ideas come to life with pan India and global implementations at Bank.

# Why did you decide to solve this Problem statement?

I am a problem solver. No problem is big or small for me.
As soon as I encountered this problem I read about the bank cheques clearing process and there I came to know that as described in the problem clearing cheque is a tedious problem and it take lots of human efforts to do so. 
So to deal with the problem I have decided to solve this problem.

# User Segment & Pain Point

#Which user /advertiser segment would be early adopter of your product & why?
Bank(s) will be the early adopter of the the entire solution as far as the automatic cheque processing system is concerned beause it saves the huge amount of time of employee on clearing the checks. 
Moreover the user who are part of the system will also be the adopter of the sysytem . In order handle the fraudlent transaction user have to or is asked to give his concent for proceeding the check cleaing process. This will save user form any fraudelent transaction. 
Which user /advertiser segment would be early adopter of your product & why?
Bank(s) will be the early adopter of the the entire solution as far as the automatic cheque processing system is concerned beause it saves the huge amount of time of employee on clearing the checks. 
Moreover the user who are part of the system will also be the adopter of the sysytem . In order handle the fraudlent transaction user have to or is asked to give his concent for proceeding the check cleaing process. This will save user form any fraudelent transaction. 

# What are the alternatives/competitive products for the problem you are solving?
There are several semi-automatic cheque processing system that are capable of substitution this proble as a solution. But most of them are just prototype and are not used commercially. The existing productions lacks automation as  well as the security features moreover they involves many human steps to make the system completely functional. 

# Azure tools or resources!
The chepest Tools and the Resources I could find are listed below.
Resources:
Azure- Linux Container (cost memory: $3.8909 per GB and vCPU:$35.4780 per vCPU  )
Azure-PostgreSQL: Burstable(vcore:1 ,2GB Memory ,costs $12.41/month, storage:$0.115/Gib/Month)
Tools:
Azure-Computer Vison (s2  $1/1000 transaction)


# Actual Idea
This solution will work on two parts:
1) The CTS system:
     For the verification at the drawee bank:
         -> Input will be a grey scale 100 DPI ( 8bit depth)  JPEG image ( As recommended by RBI)
         -> It will be divided into several essential parts for identification purpose.
         -> On extracting the details it will verify the details of the customers and all the security features.
         -> It will verify the user and the balance of drawer and then will ask the consent of drawer to initiate the transaction.
         ![image](https://user-images.githubusercontent.com/67801046/189877856-ece1d244-130f-44e2-97e3-f6f1c31647bd.png)

     For submission for checking at drawee Bank
         -> Scan the cheque in the required form. 
         -> Extract the all essential information from the cheque.
         -> Send the cheque Image to the Drawee bank based on the extracted information using the CTS system and que for approval. 

2) Provide the user interface for the submission of issued cheque for pre-checking or providing the consent for the initiation of the cheque process.

# Why the suggested solution is better than other
My suggested solution stands out of all the alternative because it use simple and fundamental processes of the automation . IT uses OCR, that will extract the communication and identifiable details out of the image. 
It also stands on the RBI  standards for the proceedings and will mould according in future also.  
It posses all the security features for verification  and data transmission (As specified in the RBI guidelines).
To avoid fraudulent Transaction  Positive Pay and Reverse Positive Pay System is also included in the system.
For handling of  unexpected situation manual input is also included to ease the process. For example, the payee name is  not recognised , the system is unable to is unable to identify the details, in such cases the cheques will be handled manually. 
For the cross verification purpose SAMPLING is also included.  Nearly 20% of the cheques are selected randomly for the human verification to monitor the accuracy of the system. 

# References
For the verification of the RBI guidelines and Recommended standards Please refer following PDFs:
CTS System Standards: https://rbidocs.rbi.org.in/rdocs/content/pdfs/74751.pdf
CTS For Standards : https://rbidocs.rbi.org.in/rdocs/content/PDFs/SCFR220210.pdf



