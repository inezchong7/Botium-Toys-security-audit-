<h1>🪀Botium Toys Security Audit</h1>

<h2>Stakeholder memorandum</h2>
<p>Dear Colleagues,
please review the following information regarding the Botium Toys internal audit scope,
goals, critical findings, summary, and recommendations.</p>

<p><b>Scope:</b></p>
<ul>
  <li>The following systems are in scope: accounting, end point detection, firewalls,
intrusion detection system, SIEM tool. The systems will be evaluated for:</li>
  <ul>
    <li>Current user permissions</li>
    <li>Current implemented controls</li>
    <li>Current procedures and protocols</li>
  </ul>
  <li>Ensure current user permissions, controls, procedures, and protocols in place
align with PCI DSS and GDPR compliance requirements.</li>
  <li>Ensure current technology is accounted for both hardware and system access.</li>
</ul>

<p><b>Goals:</b></p>
<ul>
  <li>Adhere to the NIST CSF.</li>
  <li>Establish a better process for their systems to ensure they are compliant.</li>
  <li>Fortify system controls.</li>
  <li>Adapt to the concept of least permissions when it comes to user credential
management.</li>
  <li>Establish their policies and procedures, which includes their playbooks.</li>
  <li>Ensure they are meeting compliance requirements.</li>
</ul>

<p><b>Critical findings:</b></p>
<ul>
  <li>Multiple controls need to be developed and implemented to meet the audit
goals, including:</li>
  <ul>
    <li>Control of Least Privilege and Separation of Duties</li>
    <li>Disaster recovery plans</li>
    <li>Password, access control, and account management policies, including
the implementation of a password management system</li>
    <li>Encryption (for secure website transactions)</li>
    <li>IDS</li>
    <li>Backups</li>
    <li>AV software</li>
    <li>CCTV</li>
    <li>Locks</li>
    <li>Manual monitoring, maintenance, and intervention for legacy systems</li>
    <li>Fire detection and prevention systems</li>
  </ul>
  <li>Policies need to be developed and implemented to meet PCI DSS and GDPR
compliance requirements.</li>
  <li>Policies need to be developed and implemented to align to SOC1 and SOC2
guidance related to user access policies and overall data safety.</li>
</ul>

<p><b>Other findings:</b></p>
<ul>
  <li>The following controls should be implemented when possible:
    <ul>
      <li>Time-controlled safe</li>
      <li>Adequate lighting</li>
      <li>Locking cabinets</li>
      <li>Signage indicating alarm service provider</li>
    </ul>
  </li>
</ul>

<p><b>Summary/Recommendations:</b></p>
<p>Botium Toys should address the critical findings relating to compliance with PCI DSS and GDPR, as the company accepts online payments from global customers, including those in the E.U. The company should also use SOC1 and SOC2 guidance related to user access policies and overall data safety to develop appropriate policies and procedures. Having disaster recovery plans and backups is also critical because they support business continuity in the event of an incident. Integrating an IDS and AV software into the current systems will support our ability to identify and mitigate potential risks, and could help with intrusion detection, since existing legacy systems require manual monitoring and intervention. To further secure assets housed at Botium Toys’ single physical location, locks and CCTV should be used to secure physical assets (including equipment) and to monitor and investigate potential threats. While not necessary immediately, using encryption and having a time-controlled safe, adequate lighting, locking cabinets, fire detection and prevention systems, and signage indicating alarm service provider will further improve Botium Toys’ security posture.</p>

<h2>WALKTHROUGH</h2>
<h2>Current assets</h2>
<p>Assets managed by the IT Department include:</p>
<ul>
  <li>On-premises equipment for in-office business needs </li>
  <li>Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.</li>
  <li>Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management</li>
  <li>Internet access</li>
  <li>Internal network</li>
  <li>Vendor access management</li>
  <li>Data center hosting services</li>
  <li>Data retention and storage</li>
  <li>Badge readers</li>
  <li>Legacy system maintenance: end-of-life systems that require human monitoring</li>
</ul>

<h2>Risk</h2>
<p>Assets are being inadequately managed. There are no proper controls in place. May not be compliant with U.S. international regulations and standards. Risk score is 8. Medium potential impact from asset loss (IT dept does not know which assets would be lost. High likelihood of a lost asset or fines from governing bodies (no necessary controls in place; not adhering to required regulations and standards related to keeping customer data private.)</p> 

<h2>Goals</h2>
<p>The goals for Botium Toys’ internal IT audit are:</p>
<ul>
  <li>To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF) 
</li>
  <li>Establish a better process for their systems to ensure they are compliant</li>
  <li>Fortify system controls</li>
  <li>Implement the concept of least permissions when it comes to user credential management</li>
  <li>Establish their policies and procedures, which includes their playbooks</li>
  <li>Ensure they are meeting compliance requirements</li>
</ul>

<h2>Control categories</h2>
<p>The 3 main categories:</p>
<ul>
  <li><b>Administrative/Managerial controls:</b> policies and procedures (how an organization manages data; employee responsibilities) </li>
  <img src="https://github.com/inezchong7/Botium-Toys-security-audit-/assets/106855786/ab008cb9-1074-4920-adcb-14de442bad9e">

  <li><b>Technical controls:</b> firewalls, intrusion detection systems (IDS), intrusion prevention systems (IPS), audio visual (AV) products, encryption</li>
  <img src="https://github.com/inezchong7/Botium-Toys-security-audit-/assets/106855786/9d4a3ea4-19a4-4f92-8671-f1744c6ad2f6">
  
  <li><b>Physical controls:</b> door locks, cabinet locks, surveillance cameras, badge readers</li>
  <img src="https://github.com/inezchong7/Botium-Toys-security-audit-/assets/106855786/d01f053b-9e91-490d-b37c-319821c1dec2">
</ul>

<p>The 5 types:</p>
<ul>
  <li><b>Preventative:</b> prevent an incident from occurring</li>
  <li><b>Corrective:</b> restore an asset after an incident</li>
  <li><b>Detective:</b> whether an incident has occurred or is in progress</li>
  <li><b>Deterrent:</b> discourage attacks</li>
  <li><b>Compensating:</b> fortify the security of an asset</li>
</ul>

<h2>Controls Assessment</h2>
<img src="https://github.com/inezchong7/Botium-Toys-security-audit-/assets/106855786/3d60962a-cb95-401c-96da-e27ae4a870ef">
<img src="https://github.com/inezchong7/Botium-Toys-security-audit-/assets/106855786/629d011f-6aa6-403f-860b-1c55d49df8e5">
<img src="https://github.com/inezchong7/Botium-Toys-security-audit-/assets/106855786/f91654a7-419d-4f11-a2f6-00ea789fdc20">
<img src="https://github.com/inezchong7/Botium-Toys-security-audit-/assets/106855786/a1d58568-0fda-440d-813c-7d7c13de62d7">

<h2>Compliance</h2>
<p><b>General Data Protection Regulation (GDPR)</b></p>
<p>GDPR is a European Union (E.U.) general data regulation that protects the
processing of E.U. citizens’ data and their right to privacy in and out of E.U.
territory. Additionally, if a breach occurs and a E.U. citizen’s data is
compromised, they must be informed within 72 hours of the incident.</p>
<p>Why?: Botium Toys conduct business and collect personal information from people worldwide, including the
E.U.</p>

<p><b>Payment Card Industry Data Security Standard (PCI DSS)</b></p>
<p>PCI DSS is an international security standard meant to ensure that organizations
storing, accepting, processing, and transmitting credit card information do so in
a secure environment.</p>
<p>Why?: Botium Toys store, accept, process, and transmit credit card information in person and online.</p>

<p><b>System and Organizations Controls (SOC type 1, SOC type 2)</b></p>
<p>The SOC1 and SOC2 are a series of reports that focus on an organization's user
access policies at different organizational levels. They are used to assess an
organization’s financial compliance and levels of risk. They also cover
confidentiality, privacy, integrity, availability, security, and overall data safety.
Control failures in these areas can lead to fraud.</p>
<p>Why?: Botium Toys needs to establish and enforce appropriate user access for internal and external (third-party vendor) personnel to mitigate risk and ensure data safety.</p>
