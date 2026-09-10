# Penetration Testing – Orion

This project focuses on carrying out an ethical penetration testing process against **Orion**, a vulnerable-by-design machine provided by the **Hack The Box** platform.

The penetration testing process was divided into the following phases:

1. Information Gathering & Target Discovery
2. Target Enumeration & Port Scanning
3. Vulnerability Mapping
4. Exploitation
5. Post-Exploitation

The **Target Scoping** phase was omitted because the project was conducted in an educational environment without a client. Therefore, there was no need to define business objectives, testing requirements, or engagement boundaries with a client.

## Environment

* **Attacker machine:** Kali Linux `6.16.8+kali-arm64`, running in VMware Fusion
* **Target machine:** Orion, provided by Hack The Box
* **Connection:** Hack The Box VPN

The tests were performed from the Kali Linux virtual machine, which accessed the private Hack The Box network through the platform's VPN.
