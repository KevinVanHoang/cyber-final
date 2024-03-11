# ops-201d10 The Terminators Project Requirements

## Team Members
- Andrew Carroll - [GitHub](https://github.com/iAmAndrewCarroll)
- Eveangalina Campos - [GitHub](https://github.com/Eveangalina)
- Tommy Taylor - [GitHub](https://github.com/taylortommy23)
- Breanna Taylor - [GitHub](https://github.com/Btaylor007)
- Nick Watson - [GitHub](https://github.com/GODKINGDEATHLORD)
- Kevin Hoang - [GitHub](https://github.com/KevinVanHoang)

## Project Scope and MVP

**Minimum Viable Product (MVP):**

1. **Network Vulnerability Assessment**: Using Nmap to identify active hosts, open ports, and services.
2. **Web Application Security Testing**: Employing Burp Suite for vulnerability discovery and exploitation.
3. **Exploitation and Reporting**: Documenting the exploitation process of identified vulnerabilities using Kali Linux tools.
4. **Stealth and Monitoring Avoidance**: Demonstrating techniques to evade detection by Splunk.
5. **Final Presentation Preparation**: A presentation detailing findings, exploited vulnerabilities, and remediation recommendations.

## Stretch Goals

1. **Advanced Exploitation Techniques**: Implementing sophisticated exploitation methods.
2. **Automation Scripts**: Developing scripts for automating testing processes.
3. **In-depth Web Application Testing**: Extensive testing with advanced manual techniques.

## Project Management in GitHub Projects

- **Deliverables Grouped by Milestone**: Initial Network Scanning, Vulnerability Analysis, Exploitation, Reporting and Presentation Preparation.
- **Tasks with Due Dates and Assignments**: Defined tasks assigned to team members.
- **Stretch Goals**: Listed as separate tasks.

## System Diagrams

- **Network Topology**: Diagram outlining the target network.
- **Process Flowcharts**: For scanning, exploitation, and reporting phases.

## Standard Operating Procedures (SOPs)

### SOP 1: Network Scanning Procedure

**Objective**: To conduct an initial scan of the target network to identify active hosts, services, and open ports using Nmap.

**Steps**:
1. **Preparation**: Ensure Kali Linux environment is set up with the latest version of Nmap.
2. **Execution**: Run `nmap -sV -T4 target_ip_range` to scan for services and versions.
3. **Documentation**: Log the output of the scan, highlighting interesting ports and services.

### SOP 2: Exploitation Techniques

**Objective**: To exploit identified vulnerabilities within the target network using tools available in Kali Linux.

**Steps**:
1. **Vulnerability Analysis**: Review network scan results to identify potential vulnerabilities.
2. **Tool Selection**: Choose the appropriate tool (e.g., Metasploit) for the vulnerability.
3. **Exploitation**: Execute the exploit while carefully monitoring the system's response.
4. **Evidence Collection**: Document the exploitation process, including any obtained access or data.

### SOP 3: Stealth Testing Guidelines

**Objective**: To conduct penetration testing activities without triggering alerts in the client's Splunk monitoring system.

**Steps**:
1. **Understanding Splunk**: Research how Splunk detects penetration testing activities.
2. **Technique Selection**: Choose methods that minimize network noise and are less likely to be detected.
3. **Execution**: Carefully carry out testing activities, continuously monitoring for potential alerts.
4. **Adjustment**: If detection is suspected, adjust tactics to remain undetected.

## Linking to GitHub Documentation Repo

- SOPs, system diagrams, and project planning materials are available in the [GitHub Documentation Repo](https://github.com/TheTerminators/CyberSecProject).
