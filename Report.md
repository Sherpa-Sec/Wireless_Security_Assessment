# Home Wi-Fi Security Assessment – Full Report

## Objective
The objective of this assessment was to evaluate the security of a home Wi-Fi network, compare it with public wireless networks, identify vulnerabilities, and apply security improvements aligned with industry best practices.

---

## Scope
This assessment included:
- Review of home wireless network security  
- Comparison with public Wi-Fi networks  
- Analysis of router configuration  
- Evaluation of authentication, encryption, and access controls  
- Implementation and validation of remediation actions  

---

## Network Discovery Summary

| Network        | Type    | Security         | Notes                                       |
|----------------|---------|------------------|---------------------------------------------|
| Home Network   | Private | WPA2 (initially) | Default SSID, WPS enabled, default password |
| Queens Library | Public  | Open             | No encryption                               |
| Starbucks      | Public  | Open             | No encryption                               |

---

## Security Findings

| Issue                  | Security Impact                                   |
|------------------------|---------------------------------------------------|
| WPA2 instead of WPA3   | Provided weaker encryption than the modern standard |
| WPS enabled            | Exposed the network to PIN brute-force attacks    |
| Default admin password | Increased risk of unauthorized router access     |
| Default SSID           | Revealed vendor or identifying information       |

---

## Remediation Actions

| Action                           | Purpose                                          |
|----------------------------------|--------------------------------------------------|
| WPS was disabled                 | Prevented PIN-based wireless attacks             |
| Admin password was changed       | Restricted unauthorized access to router settings|
| SSID was renamed                 | Reduced device and owner identification          |
| WPA3 was enabled (supported devices) | Improved wireless encryption and security    |

---

## Results
The home network was successfully hardened by disabling insecure features, strengthening authentication controls, and enabling modern encryption standards. These changes reduced the attack surface and improved the overall wireless security posture.

---

## Evidence
The evidence section contained screenshots verifying:
- Router login access  
- WPS disabled  
- SSID renamed  
- WPA3 enabled  
- Firmware version verification  
- Connected device inventory  
- Public Wi-Fi security observations  

---

## Conclusion
This assessment demonstrated effective wireless security hardening practices and validated improvements through configuration review and supporting evidence. The home network was brought in line with recommended security standards and showed increased resilience against common wireless attacks.
