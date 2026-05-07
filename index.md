

Welcome. I am Noah Ats. 

This is my Cybersecurity blog. Here, you can find all the work I have been dedicating my time to, including courses, projects, certifications, and more. This will serve as a personal portfolio for pertinent work curated to develop skills and experience within the realm of Cybersecurity.

Focus: | Security Operations | Threat Detection | Incident Response | 

###### Currently utilizing a lean, one-page format before optimizing.

---

* [Proxmox Home Server](#proxmox-home-server)

* [Pi-Hole DNS Home Server](#pi-hole-dns-server)

* TryHackMe Security Engineer Learning Path(Pending)

* Active Directory Project(Pending)

* [EDR Response Lab](#edr-response-lab)

* [CompTIA Security+ Certification](#CompTIA-Security+-Certification)

* [TryHackMe SOC Level 1 Learning Path](#tryhackme-soc-level-1-learning-path)

* [ELK Stack Simulation](#elk-stack-simulation)

* [Azure Sentinel Honeypot](#azure-sentinel-honeypot)

* [TryHackMe Cybersecurity 101 Path](#tryhackme-cybersecurity-101-path)

* [Cisco Security Operations Specialization](#Cisco-Cybersecurity-Operations-Fundamentals-Specialization-Certificate)

* [Google Cybersecurity Certificate](#google-cybersecurity-professional-certificate)

---

## Proxmox Home Server
###### Pushing boundaries to more accurately simulate live environments.
<br>

Built a Proxmox-based home server environment to support virtualization, lab isolation, and long-term security experimentation across multiple VMs and services. This server became the foundation for broader SOC/DFIR lab work, including Linux infrastructure, intentionally vulnerable services, SIEM tooling, honeypots, and an evolving narrative-driven environment meant to simulate operational failure, attacker activity, and incident response in a realistic way.

TBC

---

## Pi-Hole DNS Server
###### Exploring networking in real time and concerns with uptime/reliability.
<br>

Deployed a Raspberry Pi 5 home DNS stack using Pi-hole with Unbound as a recursive resolver to provide network-wide ad and tracker blocking with local DNS resolution. The setup includes router-level integration, DNSSEC validation, production-like stability goals, and planned enhancements such as Tailscale for secure remote access, Grafana for metrics, and selective whitelisting for application compatibility.

TBC

---

## EDR Response Lab
###### A different SecOps simulation with new tools.
<br>

Built an endpoint detection and response lab using LimaCharlie for telemetry and detection visibility alongside Sliver C2 to emulate adversary behavior and generate realistic endpoint activity. The lab was designed to better understand how attacker actions appear from the defender’s side, with emphasis on detection opportunities, response workflows using YARA rules, and the relationship between offensive tradecraft and defensive responsibilities.

TBC

---

## CompTIA Security+ Certification
###### Putting security knowledge to the test.
<br>

### **The First Security Checkpoint**

I have recently passed the Security+ 701 examination. This certification is a well-recognized industry standard for individuals entering the cybersecurity field. It serves to signal a comprehensive understanding of security fundamentals across endpoints, networks, and policies. CompTIA is a well-respected certification provider in the industry, offering a variety of exams for both prospective and established professionals. Notably, these include A+, Network+, and Security+, which are considered a triplet of valuable certs for individuals in my situation. I felt comfortable with the A+ exam topics after attempting practice exams and did not feel it was worth the investment, given my knowledge and study regimen. As for Network+, that may still be in the cards down the road. Security+ matters because it acts as a de facto entry ticket for SOC analysts (which, at the time of writing am striving toward) by validating conceptual security knowledge. It is also recognized by DoD 8570/8140 as a required baseline for governmental and military cybersecurity roles. The exam covers a broad survey of topics, enabling participants to be confident they understand security language to a valuable extent, which signals well with hiring managers.

### **What Sec+ Covers**

There are 5 domains on the exam.
1. **General security concepts** - CIA triad, cryptographic solutions, security controls.
1. **Threats, vulnerabilities, and mitigations** - malware, threat actors, threat vectors, exploits, mitigation techniques.
1. **Security architecture** - systems architectural models, enterprise infrastructure, resilience and recovery, data protection.
1. **Security operations** - asset and vulnerability management, SIEMs, incident response, monitoring, automation and orchestration, forensics basics.
1. **Security program management and oversight** - governance, risk management, compliance, security awareness, audits and assessments.

The exam is 90 minutes, with a passing score being 750 out of 900 total. Students also get 100 points just for writing their name. Since the scale starts with a floor of 100, students need 650 out of the remaining 800 points to pass, which equates to 81.25%. Mentioning this comes with a major caveat: the test is not entirely multiple choice. Usually, administered exams have 70-80 or so multiple-choice questions, while having around 5 performance-based questions. The more PBQs, the fewer multiple-choice and vice versa seems to be the structure many test-takers have experienced. The PBQs can include configuring a firewall's rules, identifying multiple malware types and their best remediation techniques, or designing a network architecture and selecting proper protocols and cryptography algorithms, but many other possible questions should be considered. It's unclear what the weight of each question is relative to the scoring.

### **How I prepared**

Before I was ready to study for the exam itself, I would sometimes watch what YouTube creators had to say about the exam. This gave me the confidence that with proper preparation, I would be able to pass this exam, even as someone with weak corporate IT experience. The first step was to check out ExamCompass, a website that hosts many practice tests for certifications like this and many more, to gain an understanding of my knowledge gap. After doing this for about a week or two, I realized that ExamCompass's tests and quizzes were often beyond the scope of the actual Security+ exam. This didn't seem like an efficient way to spend my time, which led me to decide to watch Professor Messer's Security+ 701 course on YouTube. Upon completion, I turned to more practice exams to gauge my probability of passing CompTIA's exam. Here is when I used CertPrep, an online website hosting free and paid-for practice exams for many certifications, similar to ExamCompass. I didn't particularly like the quality of these tests and received below satisfactory grades, leaving me yearning for better material. This is when I decided to enroll in Jason Dion's Security+ course and take some of his company's practice tests under a Udemy free trial while also booking my exam date for the day after this trial would expire. By that point, either I knew it or I didn't. Dion's practice exams were well-made, and I thought they should prepare me well enough that I wouldn't need more material. Dion's tests mimicked the Security+ well enough, even slightly beyond in difficulty and towards the end of the Udemy free trial, I was cruising through high 80%-90% scores on these practice tests. Throughout the last two weeks of this month-or-so of studying, I was also viewing some sample PBQ questions from a variety of YouTube creators, pausing to work on the question and reviewing my answer later in the video. Luckily, this study plan worked out, and I was able to pass, given a month or so of study time.

### **Takeaways**

I can honestly say Security+ gave me a bit of a run for my money. There were some multiple-choice questions that I felt very comfortable answering, but others I struggled to define the best answer, trying hard to avoid distractor options. I am usually a confident test taker, but with the variety of material covered, it was hard to be convinced of my answer choices. There's plenty of nuance to think about within each question. I was surprised by the complexity of the PBQ questions I received, and this was a gap in my studying. I felt the least confident answering those questions, taking plenty of time to think my choices thoroughly.

Security+ is less about depth and more about breadth. Exam takers are expected to know a little about everything, from AES encryption to compliance frameworks like PCI DSS to what a logic bomb is. This certification also gave me a framework to understand my past and future projects. When working through SIEM labs, it made sense to link each task to the bigger picture outlined by Security+. Although this certificate doesn't make anyone a SOC or GRC analyst, it provides proof of a baseline to start training like one if you haven't already. A crucial part of this exam is that it helps resumes get through initial HR filters, at least in 2025. With the completion of Security+, there is even more momentum gained to become an even better cybersecurity professional. Passing this milestone was a sigh of relief and gave me more motivation to keep studying every day.

##### _Completion Date: July 30th, 2025_

---

## TryHackMe SOC Level 1 Learning Path
###### Preparing for a variety of SOC threats.
<br>

Completed the TryHackMe SOC Level 1 learning path to build practical familiarity with core SOC workflows, including alert triage, log investigation, threat detection concepts, and incident analysis. The path provided experience with various platforms and developing analyst skills by exposing me to common blue-team tasks and security operations thinking used in real-world monitoring environments. Between digesting packet captures, a variety of SIEM/IDS/EDR tools, and forensics tools, this path provided plenty of exposure to how core SOC work is done, while also amply diving into OS fundamentals in Windows and Linux and how they are important for cybersecurity.

TBC

---

## ELK Stack Simulation
###### Diving deep into a practical SIEM environment.
<br>

Used Vultr to host a VPC and then built an ELK Stack lab environment to simulate security monitoring and investigation workflows using Elasticsearch, Logstash, and Kibana. This project gave hands-on experience with log collection, search and visualization, and basic detection-oriented analysis, while reinforcing transferable SIEM concepts outside of a single vendor ecosystem. Used Mythic C2 to deploy Apollo payload and compromise victim machines. Implemented osTicket to create a mock SOC analyst environment, documenting the closure or escalation of tickets, consulting dashboards, and refining ES|QL queries to trace process correlation.

TBC

---

## Azure Sentinel Honeypot
###### Using bait to catch fish in the wild.
<br>

## **Overview**

I built a SOC data pipeline in Azure, inspired by Josh Madakor's Cyber Home Lab walkthrough as a hands-on introduction to Microsoft Sentinel. A deliberately exposed Windows 10 VM serves as a honeypot. An Azure Monitor Agent forwards Windows Security Events to a Log Analytics Workspace. Sentinel ingests and queries this telemetry with KQL. A geolocation watchlist enriches each event with attacker country, city, and coordinates, and a Sentinel Workbook plots failed-logon traffic onto a live world map.

The purpose of this lab was to use a SOC data pipeline to record real brute force attempts, identify such events using a dashboard, and consider taking action with this type of alert.

## **Architecture**

```
Public Internet (attackers)
  |
  V
[Azure NSG] ── inbound: ANY/ANY/ANY (custom DANGER_ rule, priority 100)
    |
    V
[Windows 10 VM "corpnet-east-1"]
   * Local Windows Firewall disabled (Domain/Private/Public)
   * Azure Monitor Agent (AMA) extension installed
   * Security Events forwarded via Data Collection Rule
      |
      V
[Log Analytics Workspace] ──── SecurityEvent table
        |
        V
[Microsoft Sentinel]
   * KQL queries against SecurityEvent
   * geoip Watchlist joined on IP → city / country / lat / long
   * Workbook: world map of failed-logon volume by source country
```

## **Implementation**

### 1. Azure infrastructure

Provisioned the lab inside a single Resource Group (rg-soc-lab, East US 2):

   * Virtual network and default subnet
   * Windows 10 VM named with an innocuous label (corpnet-east-1) rather than something like (honeypot-01) 
   * Standard SKU disk, NIC, public IP, and NSG auto-created with the VM

### 2. Turning the VM into a honeypot

Two deliberate exposures:

   * Network Security Group: deleted the default rule that only permitted RDP and replaced it with a single custom inbound rule (prefixed DANGER_ for clarity) written as such: 
     - Source: Any, Source port: Any, Destination: Any, Destination port: Any, Protocol: Any, Priority: 100. Every Azure warning this rule throws is what we are looking for.
   * Host firewall: RDP'd into the VM and disabled Windows Defender Firewall across Domain, Private, and Public profiles via wf.msc.
     
Verified end-to-end exposure by ping-ing the VM's public IP from a local terminal and confirming ICMP replies, proof that the network path was wide open before any logging was wired up.

### 3. Centralized log pipeline
   * Created a Log Analytics Workspace (law-soc-lab) in the same region and Resource Group.
   * Deployed Microsoft Sentinel on top of the workspace.
   * From Sentinel's Content Hub, installed the Windows Security Events via AMA connector.
   * Created a Data Collection Rule (DCR-Windows) targeting the honeypot VM and configured it to collect all security events rather than only the "common" subset, so failed-logon and account-management activity wouldn't be filtered out at ingest.
   * Verified the Azure Monitor Agent extension installed on the VM (Settings -> Extensions -> status: Provisioning succeeded) and confirmed log flow into the SecurityEvent table after a short delay.
  
### 4. Hunting failed logons with KQL

Once the SecurityEvent table was populated, I narrowed the noise to failed authentications and projected only the fields that mattered:

KQL
```KQL
SecurityEvent
| where EventID == 4625 // "An account failed to log on"
| where TimeGenerated > ago(1h)
| project TimeGenerated, Computer, Account, IpAddress, Activity
```
      
Within hours of the VM being exposed, this query was returning thousands of failed-logon attempts per hour from across the public internet. Spot checking source IPs through manual geo-IP lookups confirmed the traffic was real and coming from all over the world.

### 5. Geo-enrichment via Sentinel Watchlist

Raw SecurityEvent rows contain an IP address but no geographic context. To enrich them inside the SIEM rather than externally, I did a few things:
     * Imported a SCV mapping IP network blocks (CIDR) to city, country, latitude, and longitude as a Sentinel Watchlist (geoip, search key: network).
     * Verified it landed correctly with _GetWatchlist("geoip").
     * Joined SecurityEvent against the watchlist using KQL's IPv4_lookup evaluator to resolve each attacker IP to its containing CIDR block:

KQL
```KQL
let GeoIPDB = _GetWatchlist("geoip");
SecurityEvent
| where EventID == 4625
| where IpAddress != "-"
| extend AttackerIP = IpAddress
| evaluate ipv4_lookup(GeoIPDB, AttackerIP, network)
| project TimeGenerated, Computer, AttackerIP, cityname, Countryname, latitude, longitude
```
         
Each failed logon now carried geographic context inline, exactly the kind of enrichment a real SOC analyst expects when triaging brute-force activity.

### 6. Attack map visualization

Built a Sentinel Workbook (Windows VM Attack Map) that:

   - Aggregates failed-logon events by unique combination of attacker IP, latitude, longitude, city, and country (treating each combination as a single attacking entity).
   - Plots them on a world map with marker size scaled to attempt volume.
   - Uses a custom FriendlyLocation field (city + country concatenation) for readable labels.
   - Color palette turned green to red to show high volume sources with deeper contrast.
     
The resulting workbook surfaces the dominant source countries at a glance, useful to quickly show where brute force attempts are coming from and where they are most prevalent.

## **Findings**

* Time to first attack was short. Within minutes of opening the NSG, the honeypot was being actively scanned and brute-forced.
* Attempt volume was of a high magnitude that I was not expecting. My obscure endpoint received thousands of logon attempts per hour.
* Source geography was well distributed. Some countries made more attempts than others, but eventually, traffic was coming from nearly every continent.
* Attempted usernames matched common brute-force dictionaries. This is a clear argument for renaming default admin accounts and enforcing MFA.

## **Skills demonstrated**

* Azure infrastructure provisioning and network security configuration (VNet, subnets, NSG rules, NICs, public IPs).
* SIEM deployment and content connector configuration (Sentinel + AMA + DCR).
* Log pipeline design from endpoint -> workspace -> SIEM.
* KQL: filtering, projection, time-range scoping, watchlist joins via ipv4_lookup, field renaming
* Threat-intelligence enrichment workflows via Sentinel Watchlists.
* Security data visualization with Sentinel Workbooks.
* Reading Windows Security even schemas (Event IDs, logon types, account fields).

## **Limitations & next steps**

This lab covers the detection and visibility side of a SOC. It did not include:
  * Sentinel Analytic Rules to fire alerts on threshold breaches (e.g., >n failed logons from one IP in 5 minutes).
  * Incident creation, assignment, and lifecycle management.
  * Playbooks / SOAR automation (e.g., auto-block source IPs via Logic Apps)
  * Detections beyond EventID 4625 or successful logons after brute force EventID 4624.
In future labs, incorporating a larger scope to involve these above points is the next logical step. This lab served as a great opportunity to familiarize what the Azure and Sentinel environments are like and how they may be used in a real enterprise SOC.

Built a Microsoft Sentinel lab centered on log ingestion, alerting, and investigation workflows, using a honeypot-style setup to generate security-relevant events for analysis. The project focused on learning how to onboard telemetry, query data, create detections, and use Sentinel as a cloud-native SIEM for practical SOC-style investigations. Also imported data to create a live visual dashboard for login attempts.

TBC

---

## TryHackMe Cybersecurity 101 Path
###### Strengthening foundations to patch a leaky lifeboat.
<br>

Completed the TryHackMe Cybersecurity 101 path to strengthen foundational knowledge across core security concepts, attack surfaces, defensive controls, and common operational terminology. This served as an entry-level hands-on foundation that supported later work in SOC analysis, detection engineering, and lab-based security projects.

TBC

---

## Cisco Cybersecurity Operations Fundamentals Specialization Certificate
###### Discovering the depth of the Security Operations domain.
<br>

Completed Cisco’s Cybersecurity Operations Fundamentals Specialization on Coursera to build a more structured understanding of security operations, network defense, and analyst responsibilities in enterprise environments. The coursework reinforced key blue-team concepts such as monitoring, incident response, and security operations processes in a more formal, vendor-backed learning track.

TBC

---


## Google Cybersecurity Professional Certificate
###### The tip of the iceberg.
<br>

### **Overview**

This program provided hands-on exposure to both the mindset and mechanics necessary for entry-level cybersecurity professionals. It comprises eight courses, each building upon the last to form a cohesive foundation, teaching not just what to expect but how to think in this field. Delivered through Coursera, the program offers a cost-effective, self-paced learning experience. Each course includes instructional videos, readings, interactive labs, quizzes, and exams, with numerous external resources linked for deeper exploration. As a bonus, completion of the program includes a 30% discount on the CompTIA Security+ certification—an industry-recognized credential for those pursuing a professional career in cybersecurity.

### 1. **Foundations of Cybersecurity**

This first course introduces the core concept of cybersecurity and what it means to be a cybersecurity professional. It outlines the various career paths available, emphasizes key soft skills, and defines essential terminology such as the CIA triad, SIEM tools, and packet sniffers. A strong point of the course is its emphasis on soft skills—communication, in particular, is highlighted as just as important as technical ability. Testimonials from Google employees help reinforce the idea that a background in IT is not a prerequisite for success in cybersecurity. The course is designed to engage students and promote actionable progress while correcting common misconceptions about the industry.

### 2. **Play It Safe: Manage Security Risks**

Cybersecurity professionals are constantly assessing how to identify, manage, and reduce risk. This course presents many foundational ideas through the lens of risk management. Topics include vulnerabilities, threats, impacts, assessments, regulatory frameworks, compliance, business continuity, OWASP, the NIST Cybersecurity Framework, defense-in-depth, least privilege, and SIEM tools like Splunk. It also explores human-centered risks such as social engineering and insider threats. Industry terminology is introduced and consistently reinforced throughout, helping students become comfortable with the language of cybersecurity as they progress through the program and beyond in the various cyber domains.

### 3. **Connect & Protect: Networks**

Networking is one of the most fundamental aspects of cybersecurity. Understanding how computers communicate and exchange data is critical to identifying and mitigating threats. This course introduces key protocols as TCP, UDP, IP, HTTP, and DNS, as well as the roles of ports and packets. Tools like Wireshark and IDS/IPS are used to inspect network traffic. The OSI model is presented as a conceptual framework for understanding how network communication works across layers, and security risks at each layer—such as DDoS attacks, spoofing, and sniffing—are discussed. While networking can often feel dense or technical, Google presents the material in a digestible and engaging way.

### 4. **Tools of the Trade: Linux & SQL**

I genuinely enjoyed this part of the certificate; it was one of the most engaging sections. Linux, a critical operating system in the cybersecurity world, is introduced here with an emphasis on what makes it unique and the various distributions in use. Students begin working in the Linux command-line interface (CLI), learning basic commands for navigating directories and interacting with the file system. File permissions, a vital security concept, are also covered. SQL is introduced alongside Linux to create hands-on lab scenarios where students query databases, filter tables, and extract key information—skills directly relevant to threat hunting and incident investigation. Though advanced threat detection is beyond the scope of this course, these labs offer a realistic glimpse into the daily tools of a cybersecurity professional.

### 5. **Assets, Threats & Vulnerabilities**

This course focuses on a key responsibility of cybersecurity professionals: identifying and protecting valuable assets while understanding the threats and vulnerabilities that could compromise them. The material covers how to classify assets as physical, digital, or human, and assess their importance to the organization while considering associated risks. Threats such as malware, phishing, ransomware, and insider threats all have the potential to disrupt business operations. Vulnerabilities like unpatched software, misconfiguration, and weak credentials can expose critical systems to exploitation by these threats. This course builds on this reality by introducing threat modeling techniques, such as PASTA, TRIKE, and VAST, along with risk analysis strategies that help students think critically about prioritizing risks. A hands-on lab guides students through a vulnerability assessment to put this into practice. The Common Vulnerability Scoring System (CVSS) is also touched upon to make sense of valuing vulnerabilities in the real world.

### 6. **Sound the Alarm: Detection & Response**

Moving on to course 6, where the security operations principles of threat detection and incident response come into play. This course spoke towards working in a SOC, with the reintroduction of Security Information and Event Management (SIEM) tools, now given the proper daylight to showcase their relevance. The material covers log files from various systems being aggregated into a single platform, which can generate alerts for finding indicators of compromise (IOCs). SIEMs enable analysts to find suspicious activity in real-time and are involved in the phases of the incident response lifecycle: preparation, detection, analysis, containment, eradication, recovery, and post-incident review. This course emphasizes documentation throughout the lifecycle and communication during incidents, reiterating that cybersecurity is not only a technical but also prodecural discipline. By the end, students gain a clear comprehension of how cyber defenders process daily workflows during this course.

### 7. **Automate Cyber Tasks with Python**

Course 7 began to shake things up a bit by introducing automation through Python and its growing role in modern cybersecurity workflows. This portion proved useful for covering fundamental programming concepts, including variables, data types, conditionals, booleans, loops, and functions. It applied these concepts to the goal of automating useful tasks, such as parsing logs, extracting data, manipulating files, and interacting with APIs. Perhaps the best part of this course was the inclusion of in-lesson plugins using Jupyter Notebooks to effectively give students a way to develop and refine these programming and scripting skills. By sequentially building upon first principles, students can use and understand Python by taking each task step by step, finding a cohesive experience. Learners end up walking away with hands-on experience writing Python scripts to streamline tasks, leaving them wondering what the potential could be with further development.

### 8. **Put It to Work: Prepare for Cybersecurity Jobs**

This is the final course of the certificate, focusing on career preparation and the next steps. It is somewhat obvious that there is much more to learn about the cybersecurity field, and this course does a good job of keeping the student curious about what else there is to learn. The material is much less technical, primarily engaging with what individuals should do to become a professional after acquiring the required skills. This is done by guiding the students on building professional resumes, establishing an online presence through platforms like LinkedIn, and preparing for interviews. It is also noted that communicating transferable skills from other industries and experience will help career progression, along with personal projects, other coursework, building portfolios, and engaging in cybersecurity communities, whether online or in-person. The certificate wraps up by exploring potential entry-level roles such as SOC Analyst, IT Support Specialist, or Security Technician. By utilizing job-hunting strategies and soft skill development, aspirational individuals can confidently take the next step toward breaking into the field.

### **Conclusion**

This certificate is an easy choice for self-starters curious about the cybersecurity field. Throughout the program, instructors share their journeys into the profession and their current roles at Google, helping to fuel each student's desire to become a professional, regardless of background.

What makes this course stand out is its clear delivery of foundational concepts and essential terminology. From the CIA triad and defense-in-depth to risk assessment and common attack types, students are introduced to the day-to-day thinking of security professionals. Terms like threat vectors, encryption, firewalls, and IDS/IPS are demystified, laying the groundwork for future technical mastery. The program also covers networking basics, operating system fundamentals (Windows and Linux), common threat types and vulnerabilities, and the phases of incident response—core pillars that span multiple cybersecurity domains. Exposure to scripting and automation using Python hints at how professionals can streamline repetitive but necessary workflows.

This program serves as a strong launchpad for those exploring cybersecurity and discovering opportunities they may not have considered before. From here, students are encouraged to take initiative: build a portfolio, pursue hands-on labs, earn certifications like CompTIA Security+, and connect with professionals in the industry—online or within their communities. With discipline, curiosity, and deliberate action, a real career in cybersecurity is well within reach.

##### _Completion Date: October 1, 2024_

<!--

---
layout: default
---

The following is the default text that came with this page.

Text can be **bold**, _italic_, ~~strikethrough~~ or `keyword`.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```

-->
