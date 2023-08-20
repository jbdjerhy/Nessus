# Nessus
# Project Title: Vulnerability Assessment and Exploitation with Nessus

## Project Description
This project involves setting up Nessus on Linux virtual machines, conducting vulnerability scans on target systems, and exploring vulnerabilities in a controlled lab environment.

## Project Scope
- Install and configure Nessus on Linux virtual machines.
- Perform discovery and network vulnerability scans.
- Investigate and resolve any encountered errors.
- Deploy Metasploitable, a vulnerable intentionally-made system, for testing.
- Configure Nessus on Kali Linux for vulnerability scanning.

## Objectives
1. **Install Nessus on Linux VM:** Successfully set up Nessus on a Linux virtual machine in your VirtualBox lab.
2. **Discovery Scan:** Conduct a discovery scan to identify active hosts and open ports on the network.
3. **Basic Network Vulnerability Scan:** Perform a basic network vulnerability scan to identify common vulnerabilities.
4. **Error Investigation:** Investigate and resolve any errors encountered during the setup and scanning process.
5. **Metasploitable Testing:** Install and configure Metasploitable to provide a target with known vulnerabilities.
6. **Advanced Host Scan:** Run an advanced host scan on Metasploitable to identify vulnerabilities.
7. **Alternative Nessus Setup in Kali:** Set up Nessus in Kali Linux using an alternative method.
8. **Successful Vulnerability Scans:** Successfully log in and perform vulnerability scans using Nessus in Kali Linux.

## Resources
- VirtualBox lab environment.
- Linux virtual machines.
- Nessus software.
- Metasploitable VM.

## Deliverables
- Nessus installed and configured on Linux VMs.
- Discovery scan results.
- Basic network vulnerability scan results.
- Error investigation documentation.
- Metasploitable configured for testing.
- Advanced host scan results.
- Nessus set up in Kali Linux using an alternative method.
- Successful vulnerability scan results in Kali Linux.


# Nessus Setup and Scans

- Installed Nessus on Linux VM in my Virtualbox lab

- Did a discovery scan with the following result

![Picture1](https://github.com/jbdjerhy/Nessus/assets/142699688/15a6b9c6-f937-42ae-ae30-86ccd4fadbe6)

- Performed a basic network vulnerability scan

![Picture2](https://github.com/jbdjerhy/Nessus/assets/142699688/9ca367d4-609c-4c84-8831-e8bb90cc84b1)

- I have opened and researched the following vulnerability

![Picture3](https://github.com/jbdjerhy/Nessus/assets/142699688/e37da641-3e9e-4db4-8425-394ba84f4684)

- I have installed Metasploitable which is intentionally made with a lot of vulnerabilities and ran the advanced host scan

- Second Method of Setting up Nessus in Kali
![Picture4](https://github.com/jbdjerhy/Nessus/assets/142699688/278a3614-adb6-41bc-9445-c0ca931f0053)

![Picture5](https://github.com/jbdjerhy/Nessus/assets/142699688/d3d00a45-3b08-4e7b-ab0a-4a1b4ac0716d)

```bash
└─$ curl --request GET \
  --url 'https://www.tenable.com/downloads/api/v2/pages/nessus/files/Nessus-10.5.4-debian10_amd64.deb' \
  --output 'Nessus-10.5.4-debian10_amd64.deb'
dpkg -i Nessus-<version number>-debian6_amd64.deb
systemctl start nessusd

Successfully logged in using the localhost address on my Kali Linux machine





