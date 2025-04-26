# csi-4139-ceg-4399-design-of-secure-computer-systems-laboratory-3-solved
**TO GET THIS SOLUTION VISIT:** [CSI 4139/CEG 4399 Design of Secure Computer Systems Laboratory #3 Solved](https://www.ankitcodinghub.com/product/csi-4139-ceg-4399-design-of-secure-computer-systems-laboratory-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;55743&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSI 4139\/CEG 4399  Design of Secure Computer Systems  Laboratory #3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
<h1>PART (a)</h1>
<strong>&nbsp;</strong>

<strong>Goal:&nbsp; </strong>This lab is intended to give you experience with the Snort program.&nbsp; Snort is a simple and powerful network monitoring agent.&nbsp; In this lab you will install and configure Snort, as well as write Snort rules to identify various attacks and test the applied rules.

<strong>&nbsp;</strong>

<strong>Requirements:&nbsp; </strong>3 machines (VM or Real) (Target, attacker, and Snort IDS) + Network Equipment

<strong>&nbsp;</strong>

<strong>Pre-lab Background:&nbsp; </strong>The Snort homepage is located at the following address: <a href="http://www.snort.org/">&nbsp;</a><a href="http://www.snort.org/">www.snort.org</a><a href="http://www.snort.org/">.</a>&nbsp; On the website there are documents that may assist you in understanding Snort (in particular, you may wish to consult the Snort User’s Manual, available at <a href="https://www.snort.org/documents">https://www.snort.org/documents</a><a href="https://www.snort.org/documents">)</a>.&nbsp; The section on writing Snort rules will be a helpful reference for writing the rules needed for this lab.

&nbsp;

&nbsp;

<strong>Deliverables</strong>:&nbsp; You are expected to write a document and demonstrate your results.

&nbsp;

For this lab you need to run several different attacks (see below).&nbsp; Test the attacks with the Snort IDS and show how you detect and prevent these attacks using the rules that you have written.

&nbsp;

The primary intent of this lab is for students to learn how to write effective rules.&nbsp; For example, it would be easy to write rules that match all IP datagrams regardless of content, but this would be ineffective for detecting anomalous malicious activity.

&nbsp;

Include in your report the rules you have created as well as the /var/log/snort/alert output.&nbsp; (The alert file is appended each time Snort produces an output, so you should erase the alert file before each Snort run while experimenting with different rules.)&nbsp; Be sure to include a descriptive message (“msg”) with each alert.&nbsp; Support your report by analyzing the results, including snapshots and graphics as appropriate.

&nbsp;

&nbsp;

<strong>Attacks:</strong>&nbsp; For this lab, students will conduct 3 different attacks.&nbsp; (To simplify the “guess” of information required for an attack, such as TCP sequence numbers and source port numbers, assume that attackers are on the same physical network as the victims.&nbsp; Therefore, sniffers can be used to get that information.)

&nbsp;

The specific attacks to be implemented can be freely chosen, but must fall into the following 3 categories (see <a href="https://www.snort.org/rules_explanation">https://www.snort.org/rules_explanation</a><a href="https://www.snort.org/rules_explanation">)</a>:

&nbsp;

<ul>
<li>ICMP-based attack</li>
<li>SNMP-based attack</li>
<li>Attack from a blacklisted source <em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em></li>
</ul>
<h1>PART (b)</h1>
&nbsp;

<strong>Goal</strong>:&nbsp; Implement a rudimentary antivirus program.

&nbsp;

<strong>Details:&nbsp; </strong>Your program must successfully perform the following tasks:

<strong>&nbsp;</strong>

<ul>
<li>Read the latest virus definition file to find that a new virus has a particular signature (that is, the virus contains a specific sequence of bytes). Furthermore, assume that the virus may use a Caesar-cipher-type of encryption to make itself polymorphic.</li>
<li>Check every file in a specific folder and in all of its subdirectories to find any that are infected.</li>
<li>For any infected file found, render the virus inactive (set the first 8 bytes of the signature sequence to “<em>xxxxxxxx</em>”) and quarantine the file (move it to a specified folder).</li>
<li>Keep the user informed (through the UI) about what the program is doing, what infected files it has found, whether inoculation was done, and whether the dangerous file was quarantined.</li>
</ul>
<strong>&nbsp;</strong>

During the lab demonstration of your program, the TA will supply a virus definition file and a folder containing multiple files of various types (some of which may be infected).&nbsp; The virus definition file will consist of one or more lines, with each line containing a virus signature (a specific sequence of bytes up to 96 characters in length).&nbsp; Your program must read each line and look for any viruses in the given files.&nbsp; The TA will observe the operation of your program.

&nbsp;

&nbsp;

<strong>Deliverables</strong>:&nbsp; you are expected to write a document and demonstrate your program.

&nbsp;

Document:&nbsp; write a brief description (no more than three pages) of your program and the relevant choices you have made.&nbsp; In particular, you should describe your environment and programming language, and you should explain how your program uses the virus definition file and checks for the presence of the virus.&nbsp; Any underlying assumptions that must be true in order for your program to work should also be discussed.&nbsp; Provide a section describing what functionality would need to be added to your program to make it useful for a production environment.

&nbsp;

Software: you must implement the antivirus software.&nbsp; This will consist of working code, as well as a UI sufficient to allow the TA to observe what your program is doing.

<strong><em>&nbsp;</em></strong>

&nbsp;

&nbsp;

&nbsp;

<strong><em>Laboratory #3, Parts (a) and (b), can be done in groups of up to 3 people. </em></strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;</strong>

<strong>Additional note for Lab #3, Part (b): </strong>

&nbsp;

You may find it useful to look at the link&nbsp; <a href="http://www.eicar.org/anti_virus_test_file.htm">http://www.eicar.org/anti_virus_test_file.htm</a>

&nbsp;

EICAR is essentially a “safe” file that was designed to test anti-virus and anti-malware programs.&nbsp; It does not do any damage, but looks like a real virus to such programs and thus allows people to confirm that their anti-virus programs are working properly.&nbsp; The file eicar.com has a 68-byte signature.&nbsp; This file, and its associated signature, may serve as a useful test for your laboratory code (you can see if your code will properly read the signature from a virus definition file, find the eicar.com file, inoculate it, and quarantine it).

&nbsp;

Note, however, that the computers in the lab all have anti-virus software installed already.&nbsp; Consequently, they are likely to find eicar.com and quarantine it as soon as you try to download it (i.e., before you can get a chance to try your own program on it).&nbsp; To get around this, you may need to Caesar-cipher-encrypt the file eicar.com and have your program work with this instead of the original file.

&nbsp;

&nbsp;

<em>Working with the EICAR file is not required for this lab; it is simply one interesting and realworld way to test the functionality of your implementation. </em>

&nbsp;
