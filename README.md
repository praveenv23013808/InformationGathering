# InformationGathering

Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

![expt 2 1](https://github.com/22008686/InformationGathering/assets/118916413/d6f4c03e-cb95-43a2-9c0b-3c72062aa1ad)

## Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```ping saveetha.ac.in```

## output:

![expt 2 2](https://github.com/22008686/InformationGathering/assets/118916413/1bda91d4-2665-4a74-a1de-6f3a2ef72217)

## Finding Hosting Company:

get further detail by using ip2location.com website.

## output:

![expt 2 3](https://github.com/22008686/InformationGathering/assets/118916413/b7df355a-f748-49a6-9e13-69a08eb875c0)

## History of the website:

## Output:

![expt 2 4](https://github.com/22008686/InformationGathering/assets/118916413/c5ece508-14ce-44f9-a95e-ba5c89b130b5)

## Webserver Fingerprinting:

## Netcat:

```nc 172.17.52.118 80```

## OUTPUT:

![expt 2 5](https://github.com/22008686/InformationGathering/assets/118916413/8290a196-f3c6-4331-88a7-67988cdfde7f)

## nmap:

```nmap -p 21 -sV --script=banner ftp.vim.org```

## OUTPUT:

![expt 2 6](https://github.com/22008686/InformationGathering/assets/118916413/7435f1f3-ce6a-485e-a42c-78117a0c8a8c)

## Whatweb:

```whatweb infosys.com```

```whatweb zoho.com```

```whatweb -v -a 3 172.17.52.201```

## OUTPUT:

![expt 2 7](https://github.com/22008686/InformationGathering/assets/118916413/4f181af1-6b12-4f66-bd4b-daeac72a8873)

## httprint:

```httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more```

## OUTPUT:

![expt 2 8](https://github.com/22008686/InformationGathering/assets/118916413/c4d53420-e700-4b2d-a8a6-01af513ed4bb)

## Tracing the Location

## TCP Traceroute:

```sudo traceroute -T www.saveetha.ac.in```

## OUTPUT:

![expt 2 9](https://github.com/22008686/InformationGathering/assets/118916413/8a268fec-7cdd-49f9-acff-4b8124a5d14b)

## UDP Traceroute:

```sudo traceroute -U www.saveetha.ac.in```

## OUTPUT:

![expt 2 10](https://github.com/22008686/InformationGathering/assets/118916413/07e71bc6-9bd2-4b5b-b288-338bba7a2fd2)

## ICMP Traceroute:

```sudo traceroute  www.saveetha.ac.in```

## OUTPUT:

![EXPT 2 11](https://github.com/22008686/InformationGathering/assets/118916413/f4fb3123-4a3b-499c-b7af-16780a7a130c)


## RESULT:

The information gathering techniques tools/procedure were  identified successfully
