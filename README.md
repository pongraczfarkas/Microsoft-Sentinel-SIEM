# Microsoft Sentinel SIEM

![image](https://github.com/user-attachments/assets/9aa48c18-4f37-41e4-9201-fede82092ec0)
![image](https://github.com/user-attachments/assets/8e2f5af8-ad03-409e-82db-65c82a8995b0)
![image](https://github.com/user-attachments/assets/223c5b05-f7c4-45a8-8b45-0a63e3b34244)
![image](https://github.com/user-attachments/assets/0e00b795-a953-4556-bd81-af81dae5c98a)
![image](https://github.com/user-attachments/assets/8aab4fe1-be88-4108-9d85-a72756e7f51a)
![image](https://github.com/user-attachments/assets/966e7006-7485-49fa-b8c4-73524aab97fc)
![image](https://github.com/user-attachments/assets/74da3e8f-4d67-498f-874c-1e80351c315c)
![image](https://github.com/user-attachments/assets/8dff30a2-5bb2-4725-8daf-1a1063983024)
![image](https://github.com/user-attachments/assets/c2fe1339-dff3-49e0-8513-bdc4baceea50)

![image](https://github.com/user-attachments/assets/3f004019-ec02-4119-9f4f-867a7eb947be)
![image](https://github.com/user-attachments/assets/36bec134-1f39-4bf8-a669-db8c0e4d293b)
![image](https://github.com/user-attachments/assets/161c2be7-5cc6-4bef-bb20-4673c1bc7ae9)
![image](https://github.com/user-attachments/assets/c9e5803b-7907-4078-9805-a2ecd33a9bbc)

![image](https://github.com/user-attachments/assets/5d2d5b20-1137-4a6e-a3ea-f28d7e5be2b5)

![image](https://github.com/user-attachments/assets/a2f6d68d-24eb-43cc-9e5a-eeb7214b60a5)
![image](https://github.com/user-attachments/assets/f0e572ba-c0be-4a41-9f87-d4c44b03055a)
![image](https://github.com/user-attachments/assets/57ed114b-6714-4459-a5d5-856e2e038e22)
![image](https://github.com/user-attachments/assets/f7a91e22-c914-40b8-a724-27e4b6a522ff)

![image](https://github.com/user-attachments/assets/26e0d6cc-8c22-4314-b898-62c8cc9e55fc)
![image](https://github.com/user-attachments/assets/e35a51a1-3dc8-4b2f-adc9-742b10814b31)
![image](https://github.com/user-attachments/assets/a43ba24f-0e19-4def-92ec-2ad9deb750a0)
![image](https://github.com/user-attachments/assets/50c1043c-584a-4931-b184-74b450a2b308)
![image](https://github.com/user-attachments/assets/33ac5d18-08f9-4b1e-a745-7c3572c8d1bd)
![image](https://github.com/user-attachments/assets/bd9eb7ca-f67b-4e06-97ef-ef4b1efff0b5)
![image](https://github.com/user-attachments/assets/b926f558-ef40-4031-8c72-2c7248b1242b)
![image](https://github.com/user-attachments/assets/4e3d2290-bdfc-4ad8-bc61-7d45d7329270)

![image](https://github.com/user-attachments/assets/48357850-4ac2-4937-899f-c1c1c8445896)
![image](https://github.com/user-attachments/assets/fcc5349f-0bd3-43ea-a34f-cae792b39bb5)
![image](https://github.com/user-attachments/assets/f76d659d-af79-449c-940d-0b88c55f3d6c)
![image](https://github.com/user-attachments/assets/490faf6f-550a-4250-b031-ff42c99c6c7d)


![image](https://github.com/user-attachments/assets/ee067c9b-7cfa-4292-b31d-083a975843c2)
![image](https://github.com/user-attachments/assets/791c7e5b-53e4-4189-9188-0b7fbb856f7e)
![image](https://github.com/user-attachments/assets/8b231e43-0219-428e-b266-9656eb27907d)
![image](https://github.com/user-attachments/assets/e2a78424-3ceb-46e2-bd6d-451c328b65af)
![image](https://github.com/user-attachments/assets/059712fa-2d98-4fe9-be63-165b2f111f14)
![image](https://github.com/user-attachments/assets/cfe48c8a-e5a8-41f7-9206-ffbdf0ef571a)
![image](https://github.com/user-attachments/assets/9031e4c0-6636-4bfa-9f2a-a52fe528bf48)

![image](https://github.com/user-attachments/assets/323fef57-9192-4181-8af6-90b0215d69b6)
![image](https://github.com/user-attachments/assets/96d8a239-c4e7-4f64-94c6-9cb7bfe9ba23)
![image](https://github.com/user-attachments/assets/14386eb8-4243-4e6c-84a7-2ded495d8eb8)

![image](https://github.com/user-attachments/assets/26f19721-cbd7-4ef9-9078-4edf1f7efe15)

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

![image](https://github.com/user-attachments/assets/10313b34-964b-4a19-a8b9-114af0a088e3)
![image](https://github.com/user-attachments/assets/b81a719e-4626-49e4-8f80-cc20e426e5b5)
![image](https://github.com/user-attachments/assets/b230cdc4-0d1a-4aac-8170-2a6c63c3f919)
![image](https://github.com/user-attachments/assets/baddd4ba-a7d5-4ed8-b08e-e49820d20eb9)
![image](https://github.com/user-attachments/assets/d84866f8-b26d-41cd-8869-0c9041757653)
![image](https://github.com/user-attachments/assets/b69a8b90-5e61-4fd8-8f55-48731b13787f)

![image](https://github.com/user-attachments/assets/3d706812-5bf1-4982-9f3c-232c15990320)
![image](https://github.com/user-attachments/assets/aa295c4b-3f0b-463c-bc8e-99c9664b46d6)
![image](https://github.com/user-attachments/assets/450b93d7-f92b-4b70-b5cd-98dd78aa7a08)
![image](https://github.com/user-attachments/assets/8e31cd21-60fb-4c10-97ce-4a19ac16ba2e)
![image](https://github.com/user-attachments/assets/94a2e538-1d6d-430f-80d4-33ad7206bf9b)
![image](https://github.com/user-attachments/assets/dd5f6894-089a-4465-8ac7-0e3d63d043bf)
![image](https://github.com/user-attachments/assets/9c7a4b9d-f837-4ac0-a29a-bfec1ffab138)
![image](https://github.com/user-attachments/assets/1b10e07b-468e-4abc-9bdf-c6e698aa9f56)
![image](https://github.com/user-attachments/assets/cb2c1807-b9e7-481d-bb0c-9f2a581849e1)
![image](https://github.com/user-attachments/assets/320db19c-6874-4ee4-94da-ca6c35ba8959)
![image](https://github.com/user-attachments/assets/c33ff3c4-cfe0-4754-a0a6-f1985b26f8ce)
![image](https://github.com/user-attachments/assets/e00700dc-bafd-4a67-a77c-07d8aacc9a6e)
Here I will try `P@ssw0rd` as my new password to make it more realistic.
![image](https://github.com/user-attachments/assets/fd20f923-0a16-4e90-b3f7-5e4d747e251d)
![image](https://github.com/user-attachments/assets/429fe733-951b-48ad-acf3-8459461ead08)
![image](https://github.com/user-attachments/assets/7ceeca8b-586d-4995-80c9-a9c33f2b64de)

![image](https://github.com/user-attachments/assets/6704d00c-0b22-47c1-ae82-a90285df1b27)
![image](https://github.com/user-attachments/assets/ea34f9b3-fe20-4e01-9112-7fe011c2814f)
![image](https://github.com/user-attachments/assets/ac007fc7-c253-4710-99d5-f7fc9126e944)
![image](https://github.com/user-attachments/assets/a32fb431-d1ce-4547-8550-3f7ac90ec127)
![image](https://github.com/user-attachments/assets/1032b29f-5053-4a00-894f-10316e1b3d5e)
![image](https://github.com/user-attachments/assets/ae08f3d0-0f78-46fe-ab47-06f6a41e2093)
![image](https://github.com/user-attachments/assets/e0464e03-007a-48d8-b1b6-e6f6fc99ecec)
![image](https://github.com/user-attachments/assets/f55fe6f0-8402-4c82-bf8c-291be4942263)
![image](https://github.com/user-attachments/assets/e31fc91a-ff31-49cb-9e07-b685406d4be5)
![image](https://github.com/user-attachments/assets/420c814e-12bb-4ca7-80fc-b10846a481f8)

