# Cyber Defense Framework

Originating from the military, a “Kill Chain” is a term used to explain the various stages of an attack.
In the realm of cybersecurity, a “Kill Chain” is used to describe the methodology/path attackers such as hackers or APTs use to approach and intrude a target.

## Cyber Kill Chain
Developed by Lockheed Martin, the Cyber Kill Chain framework is part of the Intelligence Driven Defense model for identification and prevention of cyber intrusions activity. The model identifies what the adversaries must complete in order to achieve their objective.

 **Here's a brief overview of each phase:**
  1. **Reconnaissance:** Attackers gather information about the target using public sources or social engineering. This phase involves identifying potential entry points and vulnerabilities, and collecting data that can be exploited later.
	
  2. **Weaponization:** In this phase, attackers create malicious payloads by combining exploit code with a backdoor or a remote access trojan (RAT). This package is often designed to exploit the vulnerabilities identified during reconnaissance.
	
  3. **Delivery:** The attacker transmits the weaponized payload to the target via various methods, such as phishing emails, malicious attachments, drive-by downloads, or compromised websites. The goal is to ensure the payload reaches the victim's system.
	
  4. **Exploitation:** Once delivered, the payload exploits a vulnerability on the target system. This can involve running malicious code, elevating privileges, or bypassing security controls to execute the attacker's code.
	
  5. **Installation:** In this phase, the attacker establishes a foothold by installing malware on the compromised system. This malware can create backdoors or install additional tools, ensuring persistent access to the system.
	
  6. **Command and Control (C2):** The attacker establishes a communication channel with the compromised system, enabling remote control. This phase involves using C2 servers to send commands and receive data, facilitating further actions on the target system.
	
  7. **Actions on Objectives:** The final phase involves the attacker achieving their goals, such as data exfiltration, system destruction, or further propagation within the network. This phase can vary widely depending on the attacker's motives, whether they are espionage, financial gain, or sabotage.


## Unified Kill Chain

The Unified Kill Chain (UKC) is an extended version of the traditional cyber kill chain, which was developed to provide a more comprehensive understanding of the stages involved in a cyberattack. It encompasses a broader range of activities, including pre- and post-compromise phases. Here's an overview of each of the 18 phases:
	
  1. Preparation: Attackers conduct extensive planning, including target selection, reconnaissance, and gathering of resources such as tools, infrastructure, and personnel.
	
  2. Research and Planning: Detailed reconnaissance is carried out to gather information about the target's infrastructure, vulnerabilities, and security posture. Attackers identify potential attack vectors and develop a tailored strategy.
	
  3. Initial Compromise: The attacker gains an initial foothold in the target environment through methods such as phishing, exploiting vulnerabilities, or social engineering. This phase marks the entry point of the attack.
	
  4. Weaponization: Malicious payloads are crafted or acquired to exploit vulnerabilities in the target system. These payloads may include malware, exploits, or other attack tools designed to achieve the attacker's objectives.
	
  5. Delivery: The weaponized payloads are delivered to the target environment through various channels such as email, web, removable media, or network exploitation. Delivery methods aim to bypass security defenses and reach vulnerable systems.
	
  6. Exploitation: Vulnerabilities in the target system are exploited to gain unauthorized access or control. This phase involves executing the malicious code or commands embedded in the payload to compromise the target.
	
  7. Installation: Malware or other malicious components are installed on the compromised system to establish persistence and maintain access. This may involve creating backdoors, modifying system settings, or dropping additional payloads.
	
  8. Command and Control (C2): The attacker establishes a communication channel with the compromised system to remotely control and manage the attack. C2 infrastructure allows the attacker to issue commands, exfiltrate data, and receive updates.
	
  9. Lateral Movement: Once inside the target network, the attacker explores and traverses across systems and networks to escalate privileges and expand their foothold. This phase aims to maximize the impact and scope of the attack.
	
  10. Persistence: Techniques are employed to maintain long-term access to the compromised environment, even after detection or remediation attempts. This may involve hiding malicious artifacts, creating scheduled tasks, or leveraging legitimate services.
	
  11. Data Collection: The attacker gathers sensitive information from compromised systems, networks, or users. This phase may involve exfiltrating intellectual property, credentials, financial data, or other valuable assets.
	
  12. Exfiltration: Stolen data is transferred from the target environment to an external location controlled by the attacker. Various methods, such as encrypted tunnels, covert channels, or legitimate protocols, are used to evade detection.
	
  13. Command and Control (C2) Channel Redundancy: Multiple communication channels are established between the attacker and the compromised systems to ensure resilience and redundancy. This enhances the attacker's ability to maintain control and evade detection.
	
  14. Credential Access: User credentials, such as usernames and passwords, are obtained through techniques like password guessing, credential dumping, or intercepting authentication tokens. These credentials are then used to escalate privileges and access sensitive resources.
	
  15. Defense Evasion: Tactics are employed to bypass or disable security controls, detection mechanisms, and forensic analysis. This includes techniques like obfuscation, encryption, anti-virus evasion, and disabling security services.
	
  16. Discovery: The attacker identifies and maps out the target environment, including systems, networks, services, and user accounts. This phase helps the attacker understand the layout and potential value of the compromised infrastructure.
	
  17. Execution: Malicious code or commands are executed on the compromised systems to achieve specific objectives, such as data theft, system manipulation, or disruption of operations. This phase involves carrying out the primary goals of the attack.
	
  18. Impact: The culmination of the attack, where the intended impact is realized. This may include financial loss, reputational damage, operational disruption, or regulatory penalties. The impact phase reflects the success of the attacker's objectives.



## Pyramid of Pain

It categorizes different types of indicators of compromise (IoCs) based on their effectiveness for defenders and the difficulty for attackers to change or evade them. The pyramid consists of multiple layers, each representing a different type of IoC, arranged in ascending order of effectiveness and difficulty for attackers to modify or conceal.	
	
  i. Hash Value (Trivial)

  ii. IP Address (Easy)

  iii. Domain Names (Simple)

  iv. Network/Host Artifiacts (Annoying)

  v. Tools (Challenging)

  vi. TTPs (Tough)

![image](https://github.com/Cyber-Security-Club-GIETU/CyberSecurity/assets/126961828/7e9ea02f-5ded-4c05-a51b-ac3ea76b685e)


## Diamond Model

The Diamond Model for Intrusion Analysis is a conceptual framework used in cybersecurity to understand and analyze cyber threats and intrusions.

**How Does the Diamond Model Work?**

  As mentioned above, there are four main components of the Diamond Model of Intrusion:
	
  • Adversary: The attacker or group responsible for a cyber incident.
	
  • Infrastructure: The technical resources or assets the adversary uses during the attack (e.g., servers, domains, and IP addresses).
	
  • Capability: A method, tool, or technique the adversary uses during the attack (e.g., malware or exploits).
	
  • Victim: The individual or organization the adversary targets during the attack.


**There are also various relationships between these components, including:**

 
  • Adversary-victim: The interaction between the attacker and target. This relationship concerns questions such as why the attacker selected this target and the attacker’s motivations and objectives.
	
  • Adversary infrastructure: The attacker uses various technical resources and assets. This relationship concerns how the attacker establishes and maintains its cyber operations.
	
  • Victim-infrastructure: The target’s connection to the attacker’s technical resources. This relationship concerns the attacker’s use of various channels, methods, and vectors against the target.
	
  • Victim-capability: The target’s connection to the attacker’s tools and techniques. This relationship concerns specific tactics and attack signatures used against the target.
	
	
## MITRE ATT&CK 
TTPs -
	
 **Tactics**- Technical goals of the attacker
	
 **Techniques**- Methods used to achieve the goal
	
 **Procedure**- Step by step implementation of the technique

**For more information:** https://attack.mitre.org/
