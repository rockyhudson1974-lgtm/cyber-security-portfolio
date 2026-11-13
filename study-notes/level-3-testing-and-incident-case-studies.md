# Level 3 Cyber Security Practices: Testing and Incident Studies

**Study dates:** 12–13 November 2026  
**Status:** Coursework notes and comparison exercise. No real systems were scanned or tested.

## Introduction to cyber security testing

### Vulnerability scanning

A vulnerability scan uses automated checks to look for known weaknesses in systems, devices, or software. It can help an organisation identify and prioritise issues for remediation. Scan results need review: they can include false positives, and a scan does not prove that a weakness can be exploited.

## Comparing four testing approaches

| Approach | Main purpose | What it can show | Main limitation |
| --- | --- | --- | --- |
| **Vulnerability testing** | Identify and assess known weaknesses. | Potential exposure that should be investigated and prioritised. | A finding may not be exploitable; scans can miss context or produce false positives. |
| **Penetration testing** | Safely attempt to exploit weaknesses within an agreed scope. | Whether selected weaknesses could be used to gain access or affect systems. | It is a time-limited view and may not find every weakness. |
| **Red-team testing** | Simulate a realistic adversary against agreed objectives. | How people, processes, and technology respond to a planned attack scenario. | It is broader and more resource-intensive; scope and safeguards must be clear. |
| **Social-engineering testing** | Assess how people respond to simulated manipulation, such as a phishing scenario. | Awareness, reporting, and response to people-focused tactics. | It tests a particular human-focused scenario and must be authorised and handled carefully. |

These approaches have different scopes: vulnerability testing looks for weaknesses, penetration testing checks whether selected weaknesses can be exploited, red-team testing simulates a broader adversary objective, and social-engineering testing focuses on human responses. They can complement one another, but they are not interchangeable. Any real assessment requires clear written permission and agreed boundaries.

## Incident-study reflections

### British Library cyber incident

The lesson considered how to assess an incident account: identify its audience and purpose, compare detection with reporting, examine the attack and response, and draw lessons for cyber security practice. The case discussion highlighted MFA, legacy systems, backups, alert investigation, network segmentation, updates, and incident-response planning.

### NotPetya campaign

The lesson reviewed the campaign’s use of a malicious M.E.Doc update and its spread through stolen credentials and Windows vulnerabilities, causing widespread disruption. The study highlighted the importance of patching, network segmentation, limiting privileges, supplier security, isolated backups, and incident-response planning.

## Reflection

Comparing testing approaches helps match a method to the question an organisation needs to answer. Incident studies add context by showing how weaknesses, attack paths, and response arrangements can combine to affect an organisation. These notes record learning from course activities; they do not describe independent testing or claim findings about systems I assessed.
