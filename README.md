# Microsoft Sentinel SIEM
## Project Description

This project showcases a comprehensive deployment of a Security Information and Event Management (SIEM) solution in Azure Cloud, providing hands-on experience in cybersecurity. Through this project, I have implemented advanced techniques and configurations to enhance threat detection capabilities and effectively monitor and analyze security events.

Key highlights of this project include:

- Practical Experience: Gained valuable experience in deploying and managing a SIEM solution in a cloud environment, crucial for modern cybersecurity practices.
- Threat Detection and Analysis: Implemented advanced configurations to boost the system’s ability to detect and analyze security threats.
- Incident Response: Demonstrated problem-solving skills by implementing remediation actions to mitigate and resolve identified cybersecurity incidents.
- Azure Cloud Proficiency: Enhanced proficiency in Azure Cloud services, a significant asset in the cybersecurity landscape.

## Technologies used

- Microsoft Azure: [Register](https://azure.microsoft.com/en-us/free/)
- Microsoft Sentinel All-in-one: [Download](https://github.com/Azure/Azure-Sentinel/tree/master/Tools/Sentinel-All-In-One)
- Brave: [Download](https://brave.com/)

## Walkthrough

The Sentinel All-in-One solution accelerates the deployment and configuration of Microsoft Sentinel, a robust Security Information and Event Management (SIEM) system. Released in April 2023, version two of this solution simplifies the initial setup, allowing users to quickly get started with Microsoft Sentinel.

Key features include:

- Quick Configuration: Speeds up initial setup tasks, enabling efficient deployment of Microsoft Sentinel.
- Advanced Threat Detection: Utilizes user and entity behavior analytics to detect and respond to advanced threats.
- Health Diagnostics: Ensures the proper functioning of Azure Sentinel through diagnostics for analytics rules, data connectors, and automation rules.
- Content Hub Solutions: Installs pre-configured packages containing analytics rules, dashboards, automation tasks, and more.
- Data Connectors: Enables data ingestion from various sources such as Azure Active Directory, Microsoft 365 Defender, and threat intelligence platforms.
- Flexible Deployment: Allows for the configuration of workspace retention, daily caps, and commitment tiers, with options to filter analytics rules by severity.
- Cost Efficiency: Offers 10GB of free data ingestion per day for the first month, allowing users to explore all features without incurring costs.

This solution ensures a seamless and efficient deployment process, making it easier for users to leverage the full capabilities of Microsoft Sentinel for enhanced security operations.
<p align="center"><img src="https://github.com/user-attachments/assets/9aa48c18-4f37-41e4-9201-fede82092ec0" alt="image"></p>
Selecting the location during the deployment of Microsoft Sentinel is crucial, especially for production environments, to comply with industry standards and regulations regarding user data storage. The location also affects the cost per gigabyte of data ingested. For this demonstration, I will choose a location closest to me, such as Norway East.

Key configuration steps include:

- Location Selection: Choose a location based on regulatory requirements and cost considerations.
- Resource Group and Workspace Name: Select meaningful names, such as "security monitoring."
- Daily Ingestion Limit: Set to 10GB, which is free for the first month.
- Data Retention: Microsoft provides free data retention for the first 90 days; charges apply afterward.
<p align="center"><img src="https://github.com/user-attachments/assets/8e2f5af8-ad03-409e-82db-65c82a8995b0" alt="image"></p>
Here I will enable only enable Sentinel Health diagnostics and I might turn on the artificial intelligence later.
<p align="center"><img src="https://github.com/user-attachments/assets/223c5b05-f7c4-45a8-8b45-0a63e3b34244" alt="image"></p>
For this demonstration I will enable all option in the next couple of steps, regardless if I have the license for them or not. 
<p align="center"><img src="https://github.com/user-attachments/assets/0e00b795-a953-4556-bd81-af81dae5c98a" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/8aab4fe1-be88-4108-9d85-a72756e7f51a" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/966e7006-7485-49fa-b8c4-73524aab97fc" alt="image"></p>
After the deployment, I see that there are crucial templates that have not been implemented properly in my system. After looking at the error messages it clearly shows that I have not turned on some subscriptions on my resource group. I will do this quickly and then do everything I have just done from scratch.
<p align="center"><img src="https://github.com/user-attachments/assets/74da3e8f-4d67-498f-874c-1e80351c315c" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/8dff30a2-5bb2-4725-8daf-1a1063983024" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/c2fe1339-dff3-49e0-8513-bdc4baceea50" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/3f004019-ec02-4119-9f4f-867a7eb947be" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/36bec134-1f39-4bf8-a669-db8c0e4d293b" alt="image"></p>
Now my resources are deploying and after 15-20 minutes all of the templates have installed correctly (except the one that I don't have a subscription for, but it is not a problem for this demonstration)
<p align="center"><img src="https://github.com/user-attachments/assets/161c2be7-5cc6-4bef-bb20-4673c1bc7ae9" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/c9e5803b-7907-4078-9805-a2ecd33a9bbc" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/5d2d5b20-1137-4a6e-a3ea-f28d7e5be2b5" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/a2f6d68d-24eb-43cc-9e5a-eeb7214b60a5" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/f0e572ba-c0be-4a41-9f87-d4c44b03055a" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/57ed114b-6714-4459-a5d5-856e2e038e22" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/f7a91e22-c914-40b8-a724-27e4b6a522ff" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/26e0d6cc-8c22-4314-b898-62c8cc9e55fc" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/e35a51a1-3dc8-4b2f-adc9-742b10814b31" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/a43ba24f-0e19-4def-92ec-2ad9deb750a0" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/50c1043c-584a-4931-b184-74b450a2b308" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/33ac5d18-08f9-4b1e-a745-7c3572c8d1bd" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/bd9eb7ca-f67b-4e06-97ef-ef4b1efff0b5" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/b926f558-ef40-4031-8c72-2c7248b1242b" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/4e3d2290-bdfc-4ad8-bc61-7d45d7329270" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/48357850-4ac2-4937-899f-c1c1c8445896" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/fcc5349f-0bd3-43ea-a34f-cae792b39bb5" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/f76d659d-af79-449c-940d-0b88c55f3d6c" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/490faf6f-550a-4250-b031-ff42c99c6c7d" alt="image"></p>


<p align="center"><img src="https://github.com/user-attachments/assets/ee067c9b-7cfa-4292-b31d-083a975843c2" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/791c7e5b-53e4-4189-9188-0b7fbb856f7e" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/8b231e43-0219-428e-b266-9656eb27907d" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/e2a78424-3ceb-46e2-bd6d-451c328b65af" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/059712fa-2d98-4fe9-be63-165b2f111f14" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/cfe48c8a-e5a8-41f7-9206-ffbdf0ef571a" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/9031e4c0-6636-4bfa-9f2a-a52fe528bf48" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/323fef57-9192-4181-8af6-90b0215d69b6" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/96d8a239-c4e7-4f64-94c6-9cb7bfe9ba23" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/14386eb8-4243-4e6c-84a7-2ded495d8eb8" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/26f19721-cbd7-4ef9-9078-4edf1f7efe15" alt="image"></p>

```
let torNodes = (_GetWatchlist('Tor-IP-Addresses') 
    | project TorIP = IpAddress);
SigninLogs
| where IPAddress in (torNodes)
| where ResultType != 50126
| project TimeGenerated, 
    Location, 
    IPAddress, 
    UserDisplayName, 
    UserPrincipalName, 
    UserId, 
    LocationDetails, 
    RiskState, 
    RiskLevelDuringSignIn, 
    AuthenticationRequirement, 
    ClientAppUsed, 
    ConditionalAccessPolicies
```

<p align="center"><img src="https://github.com/user-attachments/assets/10313b34-964b-4a19-a8b9-114af0a088e3" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/b81a719e-4626-49e4-8f80-cc20e426e5b5" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/b230cdc4-0d1a-4aac-8170-2a6c63c3f919" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/baddd4ba-a7d5-4ed8-b08e-e49820d20eb9" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/d84866f8-b26d-41cd-8869-0c9041757653" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/b69a8b90-5e61-4fd8-8f55-48731b13787f" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/3d706812-5bf1-4982-9f3c-232c15990320" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/aa295c4b-3f0b-463c-bc8e-99c9664b46d6" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/450b93d7-f92b-4b70-b5cd-98dd78aa7a08" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/8e31cd21-60fb-4c10-97ce-4a19ac16ba2e" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/94a2e538-1d6d-430f-80d4-33ad7206bf9b" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/dd5f6894-089a-4465-8ac7-0e3d63d043bf" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/9c7a4b9d-f837-4ac0-a29a-bfec1ffab138" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/1b10e07b-468e-4abc-9bdf-c6e698aa9f56" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/cb2c1807-b9e7-481d-bb0c-9f2a581849e1" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/320db19c-6874-4ee4-94da-ca6c35ba8959" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/c33ff3c4-cfe0-4754-a0a6-f1985b26f8ce" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/e00700dc-bafd-4a67-a77c-07d8aacc9a6e" alt="image"></p>
Here I will try `P@ssw0rd` as my new password to make it more realistic.
<p align="center"><img src="https://github.com/user-attachments/assets/fd20f923-0a16-4e90-b3f7-5e4d747e251d" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/429fe733-951b-48ad-acf3-8459461ead08" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/7ceeca8b-586d-4995-80c9-a9c33f2b64de" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/6704d00c-0b22-47c1-ae82-a90285df1b27" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/ea34f9b3-fe20-4e01-9112-7fe011c2814f" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/ac007fc7-c253-4710-99d5-f7fc9126e944" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/a32fb431-d1ce-4547-8550-3f7ac90ec127" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/1032b29f-5053-4a00-894f-10316e1b3d5e" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/ae08f3d0-0f78-46fe-ab47-06f6a41e2093" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/e0464e03-007a-48d8-b1b6-e6f6fc99ecec" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/f55fe6f0-8402-4c82-bf8c-291be4942263" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/e31fc91a-ff31-49cb-9e07-b685406d4be5" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/420c814e-12bb-4ca7-80fc-b10846a481f8" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/88f8de3e-0054-40a1-83a7-62c422695a8b" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/7d380627-847d-4d13-baea-4f84603a06e8" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/e8aa7db0-40ce-43fa-8652-0f199c31f6df" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/8538da83-852b-423b-96b7-fae8735fc9aa" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/e5b61e75-86cb-4b60-bffa-dd7e99dbc564" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/bd4b1542-6efb-42ca-b453-457098b08312" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/2ea4b421-3213-435e-8dce-b924ecc7b099" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/83a286b4-48af-42a9-8955-272f9bc1bf05" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/91c97bb1-7c05-4d8f-9c4c-d78d98bef176" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/f740b8f6-f7b2-4453-ac16-10f1e73c7297" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/e4d7fab9-fd6f-4f44-bee0-1d87f440751e" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/a2d9aa6c-d24b-496b-97c5-1a668207739b" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/a1a4aacb-ea7f-445a-bbb5-d7da91a18c0f" alt="image"></p>
Open a new window
<p align="center"><img src="https://github.com/user-attachments/assets/7aae2f66-8990-49b4-b831-9a0a5f72e58d" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/90bdba3e-c38e-40cf-bfcc-37ea5d5d4a10" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/b43336c1-85ea-4b89-886f-75fc128f7943" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/ee054e9b-6fa5-4791-b0d9-1d722c4376f9" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/87827150-4f12-46ea-8156-13474798e24e" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/12a92746-926a-473a-8f1a-2f7b831bf118" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/3f6dbf95-c664-41d5-90bc-b23a3113ba83" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/a21811e4-2892-4640-a150-bbe962ffb661" alt="image"></p>

<p align="center"><img src="https://github.com/user-attachments/assets/48c6bd4f-25fd-423b-99e3-0bfff88ec303" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/0f1b72e8-0c24-4e5f-b3d0-b1b39796ef7f" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/c5abcba8-1394-45cd-a9b1-29cb7fec4626" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/1e0eb092-9be7-4ae5-88e2-9ce193f1d0d0" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/601a62f9-bf39-46f3-8c3f-f3beea7d2601" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/e1d73f81-cc64-4ed6-9d3e-d05c5554aca6" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/02ec9f29-7808-4d5c-a831-90b5b6bf06a9" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/58e9b6f7-7a61-42b2-b4fe-a7d5fdd49a7a" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/6714d329-c645-434e-bb8f-93d7b0e5eec8" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/f492e3a9-485a-427c-b00f-6fb58f9bbc24" alt="image"></p>
Throughout the investigation it is important to add comment to the investigation. Other analysts will also be informed about the steps and the progress. It can also provide with important information in the future.
<p align="center"><img src="https://github.com/user-attachments/assets/7c42599a-9817-4f94-86f8-0da485e3393a" alt="image"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/36dd7092-c83b-4dd7-80d2-ac431ac574e9" alt="image"></p>












