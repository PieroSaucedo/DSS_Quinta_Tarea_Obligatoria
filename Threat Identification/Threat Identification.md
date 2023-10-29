
# STRIDE

Tabla **STRIDE** del Diagrama de Flujo de Datos (**DFD**)

![components_stride](components_stride.png)

### Data Flow STRIDE enumeration:

<u><strong>Tampering</strong></u>:

- Buffer Manipulation
- Protocol Manipulation
- Traffic Injection

<u><strong>Information Disclosure</strong></u>:

- Protocol Analysis
- Interception
- Footprinting
- Communication Channel Manipulation
 
<u><strong>Denial of Service</strong></u>:

- Flooding
- Excessive Allocation
- Data Interference or Obstruction


### Data Store STRIDE enumeration:

<u><strong>Tampering</strong></u>:

- Data Modification -> Data Corruption 

<u><strong>Information Disclosure</strong></u>:

- Data Theft
- Insecure Communication

<u><strong>Denial of Service</strong></u>:

- Resource Exhaustion
- Data Store Overload


### Process STRIDE enumeration:

<u><strong>Spoofing</strong></u>: 

- Process Spoofing
- Resource Location Spoofing
- Action Spoofing -> Task Impersonation

<u><strong>Tampering</strong></u>:

- Pointer Manipulation
- Buffer Manipulation
- Malicious Logic Insertion
- Contaminate Resources

<u><strong>Repudiation</strong></u>:

- Audit Log Manipulation
- Lack of System Logs

<u><strong>Information Disclosure</strong></u>:

- Interception
- Inter-process Communication (IPC) Interception
- Functionality Misuse
- Fingerprinting
- Pointer Manipulation
- Functionality Bypass

<u><strong>Denial of Service</strong></u>:

- Inducing Account Lockout
- Forced Deadlock
- Process Termination

<u><strong>Elevation of Privilege</strong></u>:

- Privilege Abuse
- Privilege Escalation
- Functionality Bypass
- Local Code Execution
- Authentication Bypass
- Authentication Abuse
- Resource Injection
- Exploiting Trust in Client

### Interactor STRIDE enumeration: 

<u><strong>Spoofing</strong></u>: 

- Identity Spoofing / User Impersonation
- Action Spoofing
- Manipulating Human Behavior
- Interface Spoofing (Defacement)

<u><strong>Repudiation</strong></u>:

- Transaction Forgery
- Action Alteration
- Lack of System Logs
