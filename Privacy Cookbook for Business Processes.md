# Privacy Cookbook for Business Processes #

## As resource for IPEN ##


## (Internet Privacy Engineering Network) ##

Cooked boiling hot by Markus Alexander Grete 
– PLEASE participate and add your content!!!

Company Mail address: <Markus.Grete@gretEDV.de>
University Mail address: <grete@l3s.de>

#Disclaimer#
This cookbook is just a raw collection of things, ideas and resources. It is not a commercial product. It is not 100% correct or free of antagonisms (as the WWW is not "by design"). It is by now not suitable for any specific purpose than collecting information - but it shall be in future.


#Events#
<table>
<tr><th>Name</th><th>Date</th><th>Place<th>URL</th></tr>
<tr><td>W3C Workshop on Privacy and User–Centric Controls</td><td>20–21 November 2014</td><td>Berlin,Germany</td><td>http://www.w3.org/2014/privacyws/</td></tr>
<tr><td>Privacy as Innovation</td><td>27th Nov 2014</td><td>IT University of Copenhagen</td><td>http://privacyasinnovation.wordpress.com/2014/10/21/privacy-as-innovation-round-table-it-universitetet-i-kobenhavn-27-november-kl-15-00-17-00/</td></tr>
</table>
  
# Motivation #
If you are in Business Process Modelling (BPM), you need to care about the privacy topics. Let’s start with the basics.

## The 7 basic principles of privacy ##
1.  Proactive not Reactive; Preventative not Remedial
2.  Privacy as default setting
3.  Privacy embedded into design
4.  Full functionality – Positive-Sum not Zero-Sum
5.  End-to-End Security – Full Lifecycle Protection
6.  Visibility and Transparency – Keep it Open
7.  Respect for User Privacy – Keep it User-Centric

## Basic concepts of privacy ##
* the right to be forgotten
* the minimum acquisition of data
* the processing by consent
* anonymity
* purpose-specification
* […] help me to continue!

The OWASP project is doing expert surveys to evaluate the Top 10 Privacy Risks as to international security experts. Thanks to FS and his project for providing the information

Reminder: 
This has to be updated regularly using the link on
“Literature”

## Top 10 Privacy Risks (by OWASP / FS) ##
This list is an expert-based rating of the current top 10 IT privacy
risks.

* P1 Web Application Vulnerabilities
* P2 Operator-side Data Leakage
* P3 Insufficient Data Breach Response
* P4 Insufficient Deletion of personal data
* P5 Non-transparent Policies, Terms and Conditions
* P6 Collection of data not required for the user-consented purpose
* P7 Sharing of data with third party
* P8 Outdated personal data
* P9 Missing or Insufficient Session Expiration
* P10 Insecure Data Transfer

# Intro #
By now, this “scrapbook” is mainly motivation and literature references.
Not much content.\
The hope is that we find the way from the motivational part and through
the existing literature and websites to provide content as soon as we
have a strong idea about how it should look like. Furthermore we will
provide content collected on universities and from real-world projects.

As we consider privacy in IT systems, we have to deal with the basic
principles of privacy. As to (3.) we have to embed privacy into design.
As to (2) by default. That means that we have to consider privacy from
the first step on.

Very often in software development in Year 2014 the software development
process begins with an analysis of what is needed, an analysis of the
Business Process (BP) the software has to support.

So we are starting top-down here.

## Basic real-world problems making privacy more difficult ##
(Reasons for the need to preserve data)
* Requirements of completeness for audits
* Requirements for preparation against legal trails
* […] help me to continue!

## The real world outside ##
You can introduce privacy into business process modelling once at each project, or – if you are a consultant – once at each customer. And you can install a separate privacy guiding process in addition to the casual data protection guidelines or compliance guidelines almost every bigger company has. If you enter a fresh startup, you should try to install a
privacy guiding process as data protection guideline, combining everything.

But to be honest, to me this is the boring part of the work and should be automated via standardized documentation (cookbooks) and tools. That’s why I suppose we need a cookbook for that.

The interesting part is to analyze the existing (sometimes older and “established”) business processes and data dictionaries, the business requirements and the current legal prerequisites. Moreover you have to look at the Databases and flat files, the Queues and Enterprise Service Buses and whether all of them are covered in the BP documentation. And –
not for last – the Online- and Offline applications and their BP coverage.

Consider: If a business process (BP) is running untouched for more than 5 years, it will most probably not be up to date in all respects. And each time you pick up a BP you have to ask all the experts and sometimes use a lot of time to get all things done.

# Borderlines #
## Topic borderline ##
In this cookbook we do not want to care much about the engineering or solely cryptographic perspective of privacy within applications. That will be topic of another cookbook. Nevertheless we will take every hint we get and assimilate it as good as we can.

## Cost and security borderline ##
I don’t know why, but I learned that companies usually do not want to show that they care about security or privacy, and want to keep their privacy enforcing projects secret. They do not even want the company name on any scientific slide about the “next generation” things we installed.

The only thing I can estimate about that is that a company’s customer would think: “Hey, they have to improve their privacy ruleset, there must be something wrong about it!”. The opposite is correct. [Kaizen](http://en.wikipedia.org/wiki/Kaizen) rules.

But – therefore – I cannot supply customer’s project documentation and can only start from now on to tell the customers that everything we do could but needn’t lead to a passage in the cookbook. If you have something you could pseudonymize and supply, you’re welcome.

(Sorry, in Germany we must make a difference between anonymized and pseudonymized as to “BDSG” law.)

# Main document #

- STARTING -

## Lifecycles ##
### Customer Lifecycle ###
If the data of a customer is no longer needed, it can and should be deleted. If a separate part of customer data is no longer needed, it should be disposed.

### Business Process Lifecycle ###
If a Business Process is finished, the data which was collected for this business process only should be deleted. The speed of this removal depends mostly on “Basic real-world problems making privacy more difficult”.

### Data retention in common ###
[…] help me to continue!

## Ideas ##
* Installation of “next generation” access control mechanism as Attribute Based Access Control.
* Installation of “Power to the person described by the data” (sometimes “more power to the user”, which would only sound correct in systems where the user is entering the data on his own).

## Toolsets ##
If you can support tables etc. which can be used with e.g. Open Office or similar, please support.
If you are from a software vendor for BPM, please support.

# Literature ##
Danger: The comment “Useable here for\*” in the tables below is very from subjective points of view and towards what the writer thinks on his/her own. Please feel free to get me informed, if something is completely wrong.

<table>
<tr><th>Title</th>                   <th>Attribute Based Access Control</th></tr>
<tr><td>Information supplied by</td> <td>MG</td></tr>
<tr><td>Useable here for</td>        <td>Restricting rights with state-of-the-art Access Systems</td></tr>
<tr><td>Download-Page</td>           <td><http://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.sp.800-162.pdf></td></tr>
<tr><td>Further Information</td>     <td>For further information: Prof. Ravi Sandhu</td></tr>
<tr><td>Added</td>                   <td>16.10.2014</td></tr>
</table>

<table>
<tr><th>Title</th>                   <th>Android Application Secure Design/Secure Coding Guidebook</th></tr>
<tr><td>Information supplied by</td> <td>JSSEC.ORG / via FD</td></tr>
<tr><td>Useable here for</td>        <td>Heading towards Round-Trip engineering privacy</td></tr>
<tr><td>Download-Page</td>           <td>http://www.jssec.org/English</td></tr>
<tr><td>Further Information</td>     <td>Seems to [MAG] as a technical and technological Guidebook</td></tr>
<tr><td>Added</td>                   <td>04.10.2014</td></tr>
</table>

<table>
<tr><th>Title</th>                   <th>Enable secure product delivery</th></tr>
<tr><td>Information supplied by</td> <td>[FD]</td></tr>
<tr><td>Useable here for</td>        <td>Thinking about basic processes as already established to secure coding</td></tr>
<tr><td>Download-Page</td>           <td>http://www8.hp.com/h20195/v2/GetPDF.aspx/4AA5-3485ENW.pdf</td></tr>
<tr><td>Further Information</td>     <td>Please add</td></tr>
<tr><td>Added</td>                   <td>04.10.2014</td></tr>
</table>

<table>
<tr><th>Title</th>                   <th>Engineering privacy requirements</th></tr>
<tr><td>Information supplied by</td> <td>JMdA</td></tr>
<tr><td>Useable here for</td>        <td>More for the engineering cookbook</td></tr>
<tr><td>Download-Page</td>           <td>The document is available in IEEE Xplore Digital Library at http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=6890523.</td></tr>
<tr><td>Further Information</td>     <td>Martin, Y.S., Del Álamo, J.M., Yelmo, J.C., Privacy Requirements Engineering: Valuable Lessons from Another Realm, In 1st International Workshop on Evolving Security and Privacy Requirements Engineering - ESPRE2014, pp. 19-24, Karlskrona (Sweden), 25 Aug 2014. doi: 10.1109/ESPRE.2014.6890523</td></tr>
<tr><td>Added</td>                   <td>04.10.2014</td></tr>
</table>

<table>
<tr><th>Title</th>                   <th>Linking security with Economics</th></tr>
<tr><td>Information supplied by</td> <td>SJE</td></tr>
<tr><td>Useable here for</td>        <td>Finding the business and economic value of privacy</td></tr>
<tr><td>Download-Page</td>           <td>https://ec.europa.eu/digital-agenda/sites/digital-agenda/files/Stephan.pdf</td></tr>
<tr><td>Further Information</td>     <td>SJE supplied more links which seem not very important for this document because they are more technological related. Just picked one which could help to understand his point of view:  http://blog.privacytrust.eu/public/Slides/au_conf670306_engberg_en.pdf</td></tr>
<tr><td>Added</td>                   <td>04.10.2014</td></tr>
</table>

<table>
<tr><th>Title</th>                   <th>Model-driven security (MDS)</th></tr>
<tr><td>Information supplied by</td> <td>UL</td></tr>
<tr><td>Useable here for</td>        <td>Evaluation of Model driven security</td></tr>
<tr><td>Download-Page</td>           <td>http://en.wikipedia.org/wiki/Model-driven\_security</td></tr>
<tr><td>Further Information</td>     <td>[...] Please supply!</td></tr>
<tr><td>Added</td>                   <td>16.10.2014</td></tr>
</table>

<table>
<tr><th>Title</th>                   <th>New Digital Security Models</th></tr>
<tr><td>Information supplied by</td> <td>SJE</td></tr>
<tr><td>Useable here for</td>        <td>Telco / ITK privacy issues</td></tr>
<tr><td>Download-Page</td>           <td>http://blog.privacytrust.eu/public/Reports/NewDigitalSecurityModels.pdf</td></tr>
<tr><td>Further Information</td>     <td></td></tr>
<tr><td>Added</td>                   <td>04.10.2014</td></tr>
</table>

<table>
<tr><th>Title</th>                   <th>OWASP Top 10 Privacy Risks Project</td></th>
<tr><td>Information supplied by</td> <td>FS</td></tr>
<tr><td>Useable here for</td>        <td>Addition of information</td></tr>
<tr><td>Download-Page</td>           <td>https://www.owasp.org/index.php/OWASP_Top_10_Privacy_Risks_Project</td></tr>
<tr><td>Further Information</td>     <td>Will provide us with information about the Top 10 Privacy Risks according to expert surveys.</td></tr>
<tr><td>Added</td>                   <td>16.10.2014</td></tr>
</table>

<table>
<tr><th>Title</th>                   <th>Privacy Engineering – A dataflow and ontological approach</th></tr>
<tr><td>Information supplied by</td> <td>FS</td></tr>
<tr><td>Useable here for</td>        <td>“it is about applying a structured approach to classification and modelling at data, storage, process, user, and environmental level, illustrated with a few use-cases. It has a proposed (or "sample") vocabulary/taxonomy with the aim of engendering PbD from requirements gathering through to end-of-life, and a means to communicate in the organisation, engineering and legal teams. So its not a "cookbook" in my mind, and is one approach to PbD in the engineering lifecycle. As an example of the depth that data modelling for privacy can go to it is good, I think, but it may not be suitable for all organisations.” as to [UXOC]
“I’ve got a copy of the book – have read the initial chapters.  I really like the modelling approach he takes – which encourages drilling down from high level data flows that anyone can understand, to the technical levels where privacy controls can actually get built in.” as to [RB]</td></tr>
<tr><td>Download-Page</td>           <td>http://www.privacyengineeringbook.net (only overview, Amazon book)</td></tr>
<tr><td>Further Information</td>     <td>Book by Ian Oliver</td></tr>
<tr><td>Added</td>                   <td>16.10.2014</td></tr>
</table>

<table>
<tr><th>Title</th>                   <th>“Salt” spelled: NaCl</th></tr>
<tr><td>Information supplied by</td> <td>CvL</td></tr>
<tr><td>Useable here for</td>        <td>More for the engineering cookbook – About a network comm. library</td></tr>
<tr><td>Download-Page</td>           <td>http://cdn.media.ccc.de/congress/2013/workshops/30c3-WS-en-YBTI_OS-Bernstein_Lange_Schwabe-NaCl_and_TweetNaCl.webm</td></tr>
<tr><td>Further Information</td>     <td>http://cdn.media.ccc.de/congress/2013/workshops/30c3-WS-en-YBTI_OS-Jon_Solworth-Ethos_Operating_System.webm</td></tr>
<tr><td>Added</td>                   <td>04.10.2014</td></tr>
</table>


# Companies and Projects #
<table>
<tr><th>Homepage</th>                              <th>Suggested by</th><th>Info</th></tr>
<tr><td>http://governor.co.uk</td>                 <td>[MAG]</td>       <td>PLEASE SUPPLY INFORMATION</td></tr>
<tr><td>http://objectsecurity.com/en-home.html</td><td>[MAG]</td>       <td>ObjectSecurity is an information security specialist company with an innovative technology portfolio and strong consulting, R&D, services track record. OpenPMF Model-Driven Security Policy Automation turns human-manageable security policies automatically into the matching technical implementation, and generates accreditation/compliance evidence automatically. It reduces cost, improves security, and speeds up accreditation/compliance. OpenPMF supports agile, complex IT landscapes (SOA, IoT, PaaS...) and policies; it’s based on model-driven security (MDS) and standards (Ecore/MOF, XMI, XACML, ABAC ...)</td></tr>
<tr><td>http://pripareproject.eu/</td>             <td>[CJ]</td>        <td>“PReparing Industry to Privacy-by-design by supporting its Application in Research. Seems a good attempt. Interested ones should read.” http://pripareproject.eu/wp-content/uploads/2014/06/PRIPARE-Position-Paper-v1-WP1.pdf</td></tr>
<tr><td>https://cryptech.is/</td>                  <td>[EJ]</td>       <td>They are doing crypto stuff for secured communication. Seem to have some guidelines for HW-design and -evaluation.</td></tr>
</table>               
               
# Persons #
If you want **your Name added**, just send me an email from the email account I have to add.\
If you want **your Name deleted** because you do not it in a book which is not 100% flavored as you like, or you do not want the information in display, please send me an email.

**But please understand: We cannot keep the discussion going on without
knowing who has which special knowledge or opinion. Just as community we
can correlate all the information.**

<table>
<tr>
<th>Name</th>
<th>"Real" Name</th>
<th>Task for IPEN</th>
</tr>
<tr><td>[AB]  </td><td>Aral Balkan</td><td>=> Engineers cookbook, Nice project</td></tr>
<tr><td>[CJ]  </td><td>Christophe Jouvray</td><td>Supplies project information</td></tr>
<tr><td>[CvL] </td><td>Carlo von Lynx</td><td>Supplies Info about end-to-end encryption, is IPEN lead for mobile solutions</td></tr>
<tr><td>[EJ]  </td><td>Erik JOSEFSSON</td><td>Supplies company Information</td></tr>
<tr><td>[FD]  </td><td>Frank Dawson  </td><td>Supplies literature and more info</td></tr>
<tr><td>[FS]  </td><td>Florian Stahl </td><td>Supplies information. OWASP might supply “counter-measures” (?)</td></tr>
<tr><td>[JMdA]</td><td>José M. del Álamo</td><td>Supplies research documentation</td></tr>
<tr><td>[MAG] </td><td>Markus Alexander Grete</td><td>Cook at the the Privacy Cookbook for Business Process</td></tr>
<tr><td>[MON] </td><td>Mike O'Neill</td><td>Cook at Engineers cookbook</td></tr>
<tr><td>[RB]  </td><td>Richard Beaumont</td><td>Supplies information, see governor.co.uk for company information</td></tr>
<tr><td>[SJE] </td><td>Stephan J. Engberg</td><td>Supplies slides and PDF</td></tr>
<tr><td>[UL]  </td><td>Ulrich Lang</td><td>Supplies information about MD-Security</td></tr>
<tr><td>[UXOC]</td><td>Ultan X. O’Carroll</td><td>Data protection of Ireland, Supplies information and knowledge</td></tr>
</table>
                
  
# Glossary #
<table>
<tr><th>Short</th><th>Element</th><th>Abstract</th></tr>
<tr><td>ABAC</td><td>Attribute Based Access Control</td><td>Idea: Prof. Ravi Sandhu @see “Literature” above / „Attribute Based Access Control“</td></tr>
<tr><td>Anon...</td><td>Anonymising intermediary</td><td>Example by [MON]: The User is presented with an iframe (other origin) with a form and a textbox, the email address is sent to the intermediary which posts a one-time ID to the containing site (this can be done with JavaScript). The new password along with the ID is sent to the intermediary who forwards it to the user’s email address. The ID is then deleted. The trick would be to make the system distributed i.e. over p2p, so you would not have to have a trusted intermediary. Addition: The intermediary would be trusted to delete the email after it was used. Even if it was co-opted it could only collect the email, not any other information e.g. the containing page url. If it was based on a distributed store then worst case only a subset of emails (without any associated data) could be syphoned off. </td></tr>
<tr><td>BDSG</td>   <td>Bundesdatenschutzgesetz </td><td>German federal law for data protection</td></tr>
<tr><td>BP</td>     <td>Business Process</td>        <td>Please refer to: <http://en.wikipedia.org/wiki/Business_process></td></tr>
<tr><td>BPM</td>    <td>Business Process Modelling</td><td>Constructing BP’s</td></tr>
<tr><td>contextual identity</td><td>by[SE]</td><td>So whatever data provide value can be exhanged as long as it does not violate contextual boundaries, ie. identity becomes identifiable (linkable). </td></tr>
<tr><td>MDS</td>    <td>Model Driven Security</td><td>http://en.wikipedia.org/wiki/Model-driven\_security</td></tr>
<tr><td>OPEN PMF</td><td>OPEN PMF</td><td>http://www.openpmf.com, http://www.objectsecurity.com/en-home-resources-publist.html, http://www.objectsecurity.com/doc/poster.pdf</td><tr>
<td>PbD</td>    <td>Privacy by Design</td><td>Please refer to: http://en.wikipedia.org/wiki/Privacy_by_Design</td></tr>
</table>
