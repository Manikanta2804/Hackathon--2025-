# Hackathon--2025-
# Team: T040

Question:Description: Background: Critical Sector organisations uses a number of
IT and OT equipment (e.g. Networking and hardware device, Operating
Systems, Applications, Firmware etc.). These devices/application come
with vulnerabilities from time to time. There should be timely
information sharing mechanism by which the concerned equipment
users at critical sector orgs should be altered regarding any critical /
high severity vulnerabilities in their equipment within the shortest
possible time. Detailed description: The ICT components (HW/SW)
being used by Critical Sector Organisations become vulnerable from
time to time. These vulnerabilities can be categorised as Critical, High,
Medium and Low. Any exploitation of these vulnerabilities can cause
havoc in multiple Critical Sector Organisations where such vulnerable
equipment are being used. Keeping in view of the above, there is a need
to monitor all such vulnerability information published at the
equipment’s OEM websites and also other relevant websites. Once a
critical or high severity vulnerability information is published at OEM
website or any other relevant website, the ‘to be developed scrapper’
will immediately take that vulnerability input along with possible
mitigating strategy published in the website and send the information to
predefined email id(s). Note: The NVD website publishes such OEM
vulnerable information. But the same comes with a time lag. It is

therefore needed to get such information directly from OEM websites
and /or from other relevant websites where such vulnerable
information is published almost in real time. Expected Outcome: An
automatic script using open source tools to be developed for the OEM
vulnerability information scrapping and reporting. Tool should know
various vulnerability information published data formats/syntax at
OEM websites (both for IT and OT hardware and application) and come
up with optimum solution for monitoring and reporting of such
vulnerability information. The output of the tool that will be emailed to
pre-designated email id(s) is as per following (shared with example; all
fields may not be available at the time of reporting): * Product Name:
Chrome * Product Version: - NA * OEM name: Google * Severity Level
(Critical/High): High * Vulnerability: The N-able PassPortal extension
before 3.29.2 for Chrome inserts sensitive information into a log file. *
Mitigation Strategy: Install patch from https://me.n-
able.com/s/security-advisory/aArHs000000M8CCKA0/cve202347131-
passportal-browser-extension-logs-sensitive-data * Published Date: Jan
2024 * Unique ID: CVE-2023-47131
