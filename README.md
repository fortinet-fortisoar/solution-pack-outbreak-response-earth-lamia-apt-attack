# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard’s global sensor network report consistently high levels of attack attempts targeting vulnerabilities associated with Earth Lamia APT campaigns. According to Trend Research, the hacking group known as Earth Lamia has been actively targeting a range of sectors- including finance, government, IT, logistics, retail, and education- shifting its focus based on evolving objectives and time periods. The group is known for its high level of activity and primarily exploits known vulnerabilities in public-facing systems and web applications to gain access. 

 The **Outbreak Response - Earth Lamia APT Attack ** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/earth-lamia-apt-attack) contains information about the outbreak alert **Outbreak Response - Earth Lamia APT Attack **. 

## Background: 

APT threat actor named Earth Lamia group is a China based Threat Actor that primarily targets organizations located in countries including Brazil, India, and Southeast Asia. 

Some of the key vulnerabilities they have exploited include CVE-2017-9805 (Apache Struts), CVE-2021-22205 (GitLab), CVE-2024-9047 (WordPress), CVE-2024-27198 and CVE-2024-27199 (TeamCity), CVE-2024-51378 and CVE-2024-51567 (CyberPanel), CVE-2024-56145 (Craft CMS), and the recently observed CVE-2025-31324 (SAP NetWeaver).

According to the recent report by Trend™ Research, after initial access, the hacking group has been observed deploying a modular .NET backdoor that can load plugins from its command-and-control (C&C) server when needed.
 

## Announced: 

Fortinet Customers remain protected by the FortiGuard IPS (Intrusion Prevention System) Security Service that can detect and block exploit attempts targeting all the vulnerabilities mentioned and has protections against known malware and IOCs used in the related campaigns. Please see the Solution Tab for full list of available protections for prevention, detection, and response capabilities againts the threat.

FortiGuard recommends users to apply the latest security updates for any vulnerable affected product/software for complete mitigation.  

## Latest Developments: 

May 29, 2025: Trend Research identified Earth Lamia campaign and published the report.
https://www.trendmicro.com/en_us/research/25/e/earth-lamia.html

May 9, 2025: FortiGuard Labs released SAP Netweaver Zero-Day Attack Threat Signal Report.
https://www.fortiguard.com/threat-signal-report/6089/sap-netweaver-zero-day-attack

March 12, 2024: FortiGuard Labs published JetBrains TeamCity Authentication Bypass Threat Signal. 
https://www.fortiguard.com/threat-signal-report/5400/jetbrains-teamcity-authentication-bypass-vulnerabilities-cve-2024-27198-cve-2024-27199 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|