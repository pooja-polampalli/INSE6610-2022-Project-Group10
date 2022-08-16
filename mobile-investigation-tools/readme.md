<h1>Mobile Investigation Tools </h1>
Today, the usage of smartphones have become more efficient and popular due to the reduced cost of manufacturing and developing hardware technologies (sensors / processors, etc.) and software systems (Android, IOS, etc.).  For mobile forensic investigators, the chief evidence of interest can be subscriber identification module (SIM), mobile memory, external memory card and Network Service Providers (NSP) [1]. Mobile phones are now used as a digital tool for committing various crimes. In particular, it can be used as a means of communication to support traditional crimes [2]. In all cases, the phone contains evidence. For example, a typical smartphone contains evidence data, including user-generated information such as contacts, audio, video, and files. Internet-related information such as email messages and web browser history; and installed third-party applications [3].

<h2>Techniques for Android Forensic:</h2>

<ol>
<li><h4>Manual Acquisition:</h4> In this technique, a forensic investigator or analyst uses the mobile device's user interface  to examine available content. When browsing the device, the inspector will take pictures of each screen containing the necessary data. The advantage of this technique is that no tools are required to collect the data. At the same time, the drawback of this technique is that it can only restore user-visible data  on  devices  which is time consuming [3].</li>

<li><h4>Physical Acquisition:</h4> This technique involves cloning  the data available on the phone device. This process duplicates deleted data and unallocated space. After replication, the replicated data is analysed using a variety of tools [3].</li>

<li><h4>Logical Acquisition:</h4> This technique requires less manual intervention or cloning. It collects data/information available on your phone (generally) using automated tools to sync your phone and PC. Most free tools available  perform logical investigations [3].</li>

</ol>

<h2>Forensic Tools:</h2>
<ul>
<li><h4>Oxygen Forensic Suite</h4>
With the help of the Oxygen forensic suite tool, you can read data from phones such as basic phone information, SIM card information, contact list, caller groups, log reports (missed calls, outgoing calls, and incoming calls), SMS, MMS, emails, scheduled calendar events, to-do list, text notes, pictures, video files, audio files, Java files, and other files saved in the phone memory or on the memory card, as well as audio recordings, etc. This application supports more than 500 different mobile phone models. And the list keeps expanding quickly. Oxygen Forensics includes A straightforward approach for examining social relationships between the owners of a phone and their contacts, or between several devices [1]. The following screenshot shows call log analysis for an android device.
</li>
  
<li><h4>Autopsy</h4>
Autopsy tool is used to analyse and extract data from Android image files. An Android image that has been physically extracted can be loaded and examined using Autopsy. The full /data / data block can be imaged using Android data extraction techniques, as well as any particular frame that is relevant to the investigation. Once the image has been obtained, the investigator can manually browse through the contents and make use of the resources at their disposal to parse through the contents. Call logs, contacts, messages, PS from the browser, and Google Maps data may all be analysed by it. Case management tools, image integrity checks, keyword searches, and other automated processes are all available in Autopsy[1]. By analysing this tool on our android image data source, we were able to extract files such as images, audios, videos, archives, and databases.  
</li>
 
<li><h4>MOBILedit</h4>
MOBILedit is a well-liked programme with a full variety of tools to extract and analyse smartphone data and information. It is a logical data acquisition tool for gathering evidence. Once the connection has been made, it will display and provide you with all the pertinent details on the connected phone, including the serial number, IMEI, IMSI, ICCID, root status, and the operator's actual phone number, as shown in the accompanying figure. Mobiledit has the ability to gather all phone numbers, whether they come from Facebook or Google email. Additionally, it saves the last 500 missed calls so you can examine them all and know who called you, when they called, and from what number[1].
  </li>

 <li><h4>Andriller</h4>
Andriller is a software tool which contains a selection of forensic capabilities for cell phones. It performs non-destructive, read-only acquisition from Android devices that is forensically sound. Other capabilities include strong Pattern, PIN code, or Password Lock Screen cracking, as well as bespoke decoders for Apps data from Android (and some Apple iOS) databases for communications decoding. Reports are generated by extraction and decoders in HTML and Excel (.xlsx) formats[4].

  </li>

</ul>



<h2>References</h2>
<ol>
<li>Romanian Journal of Information Technology and Automatic Control, Vol. 31, No. 3, 81-96, 2021 - Mobile device forensics.</li>
  
<li>Umale M N, Deshmukh A B, and Tambhakhe M D. Mobile Phone Forensics Challenges and Tools Classification: A Review. International Journal on Recent and Innovation Trends in Computing and Communication, 2014, 2(3), 622 – 626. </li>
  
<li>I.J. Information Technology and Computer Science, 2016, 01, 74-83 Published Online January 2016 in MECS (http://www.mecs-press.org/) DOI: 10.5815/ijitcs.2016.01.09 - Comparative Evaluation of Mobile Forensic Tools </li>
  
<li>https://www.hackingarticles.in/forensics-investigation-of-android-phone-using-andriller/</li>
  
<li>International Conference on Computing, Communication and Automation (ICCCA2016) - Android Phone Forensic: Tools and Techniques</li>

</ol>
