# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?  
pkg:pypi/pillow@9.4.0

2. Which CVE is linked to this vulnerability?  
CVE-2023-50447

3. What remediation steps do you suggest?  
Upgrade to a newer version of Pillow (one where this vulnerability has been patched [i.e., >= 10.2.0])  
You could use pip to install it: `pip install --upgrade Pillow`

### Vulnerability 2:
1. Which vulnerability are you addressing?  
pkg:pypi/pyyaml@5.1

2. Which CVE is linked to this vulnerability?  
CVE-2020-14343

3. What remediation steps do you suggest?  
Use `yaml.safe_load` or the SafeLoader loader when you parse untrusted input.
