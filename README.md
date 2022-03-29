# Ejercicio3-Primitive-Datatype
---
![image](https://user-images.githubusercontent.com/72273897/160652680-cb5306e6-bffc-445f-9f95-258147142c8e.png)

1. Use “Get-Help” to find out more information about 5 cmdlets.
- ![image](https://user-images.githubusercontent.com/72273897/160653418-1c36b3c4-1113-4d1f-97c3-4ed947d783e9.png)

2. Get-Help New-Item.
- ![image](https://user-images.githubusercontent.com/72273897/160653687-8d5da810-02ce-4295-932a-068b985f63a4.png)

3. Get-Help Get-Alias.
- ![image](https://user-images.githubusercontent.com/72273897/160653946-733f4dac-20df-4fd2-ad76-3b32a352176a.png)

4. Get-Help Get-AuthenticodeSignature.
- ![image](https://user-images.githubusercontent.com/72273897/160654091-47f80007-a235-4ed1-8fc6-ec0ccbb54b02.png)

5. Get-Help Get-ControlPanelItem.
- ![image](https://user-images.githubusercontent.com/72273897/160654309-3ed452b6-56b7-4f04-8007-13401f71c899.png)
**Although any 5 cmdlets will do**
---

# Task 2 Use “Get-Help” with the “–Example” parameter for the 5 cmdlets you discovered more about in task 1. Notes:
---
1. Get-Help Get-Help -Examples.
- ![image](https://user-images.githubusercontent.com/72273897/160654821-53ce49b1-f8da-4785-a697-28d05d402bba.png)

2. Get-Help New-Item -Examples.
- ![image](https://user-images.githubusercontent.com/72273897/160655185-5de95da6-4bc5-4835-8555-3b61b3e361db.png)

3. Get-Help Get-Alias -Examples.
- ![image](https://user-images.githubusercontent.com/72273897/160655326-969aa2c9-c237-4ea8-a30b-2b3aaabf0b1f.png)

4. Get-Help Get-AuthenticodeSignature -Examples.
- ![image](https://user-images.githubusercontent.com/72273897/160655501-740530bd-5d4c-45e9-8733-81fe42e8458e.png)

5. Get-Help Get-ControlPanelItem -Examples.
- ![image](https://user-images.githubusercontent.com/72273897/160655638-c1b70101-ec9c-4fce-9cc6-13321399d05f.png)
---
# Ask 3 Create a new text file named “TestFile.txt” under C:Maximo\PowerShell\Workshop1%USERNAME% The cmdlet to make a file and a new directory starts with “New” Notes:
---

1. New-Item -Path C:\ -Name Expo -ItemType Directory.
- ![image](https://user-images.githubusercontent.com/72273897/160655950-2fbb7535-ff7c-4e4c-a8fc-8abfd49c6c17.png)

2. New-Item -Path C:\Sudoblark -Name PowerShell -ItemType Directory.
- ![image](https://user-images.githubusercontent.com/72273897/160656089-d2ee39e5-8f43-462f-8b55-d4087632875d.png)

3. New-Item -Path C:\Sudoblark\PowerShell -Name Workshop1 -ItemType Directory.
- ![image](https://user-images.githubusercontent.com/72273897/160656294-614be8d5-45ba-49b2-83e6-af48404f9f34.png)

4. New-Item -Path C:\Sudoblark\PowerShell\Workshop1 -Name bclark -ItemType Directory.
- ![image](https://user-images.githubusercontent.com/72273897/160656460-f3a0c66d-462a-42bd-88dc-8f9c96d7cf9e.png)

5. New-Item -Path C:\Sudoblark\PowerShell\Workshop1\bclark\ -Name Testfile.txt -ItemType File
- ![image](https://user-images.githubusercontent.com/72273897/160656539-e9f4d3c2-a375-4e21-a572-cef6488da707.png)

---
# Task 4 Populate the text file you created in task 3 with all three datatypes we’ve covered: “Boolean”, “String” and “Int” The cmdlet you need starts with “Add” Notes:
---
1. Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value True.
- ![image](https://user-images.githubusercontent.com/72273897/160665948-f0f45f02-72a5-44d9-ab19-80ced7f32402.png)

2. Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value "Hello".
- ![image](https://user-images.githubusercontent.com/72273897/160666030-f4fd7de1-71b9-48be-8347-39091ed23455.png)

3. Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value 42.
- ![image](https://user-images.githubusercontent.com/72273897/160666117-549c7f2a-2e96-426f-a4f6-22a8f51c7d5d.png)
---
# Task 5 Read from the text file and use “Get-Member” to find the datatype returned The cmdlet you need to read data from the text file begins to “Get” Notes:
---
1. Get-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt | Get-Member.
- ![image](https://user-images.githubusercontent.com/72273897/160665571-069d4ab8-7cb0-450e-9ef8-3e7c3f26d612.png)
  ![image](https://user-images.githubusercontent.com/72273897/160665391-faa27429-4c0c-4eb1-9e96-46d30e5fd3c7.png)
---
# Task 6 Overwrite all data within the text file that you created in task 3. The cmdlet you need starts with “Set” Notes: Set-Content -Path
---

1. C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value "BUBU".
- ![image](https://user-images.githubusercontent.com/72273897/160666254-19ed8ad1-6a9a-4fe4-af46-859e8c3317ac.png)

---
# Task 7 Format the data returned by a cmdlet into a list You will need to pipe the original cmdlet then use the “Format-List” cmdlet Notes: Get-Service | Format-List
---
1.  Get-Service | Format-List.
- ![image](https://user-images.githubusercontent.com/72273897/160666441-ac298f66-d309-471f-a9d2-d2f13e8ac957.png)

---
# Task 8 Pipe “Get-Command” into “Out-GridView” Notes: Get-Command | Out-GridView
---
1. Get-Command | Out-GridView
- ![image](https://user-images.githubusercontent.com/72273897/160666675-e874ffd7-b8fb-455e-9291-d81f44964b57.png)
---
# Task 9 Pipe the 5 cmdlets you discovered in task 1 into “Out- GridView”
---
1. Get-Help | Out-GridView.
- ![image](https://user-images.githubusercontent.com/72273897/160666923-08193a34-41f0-48c9-be3e-f6779520307a.png)

2. New-Item | Out-GridView.
- ![image](https://user-images.githubusercontent.com/72273897/160667056-83d9bcc5-afef-4995-ab8c-e2980c7f59f7.png)
- ![image](https://user-images.githubusercontent.com/72273897/160667560-695a632b-6adc-4171-92b0-0c9fc5c702c0.png)

3. Get-Alias | Out-GridView.
- ![image](https://user-images.githubusercontent.com/72273897/160667258-6ff3a14d-655d-47bc-860b-89f681881d39.png)

4. Get-AuthenticodeSignature | Out-GridView.
- ![image](https://user-images.githubusercontent.com/72273897/160667441-fd8aaada-e304-4439-a604-68a3296ba34f.png)
- ![image](https://user-images.githubusercontent.com/72273897/160667492-37aff152-f029-496d-817f-59a36430cb5b.png)

5. Get-ControlPanelItem | Out-GridView.
- ![image](https://user-images.githubusercontent.com/72273897/160667725-0c81361d-1395-4fcc-bb64-be4bdb57a784.png)

---
# Task 10 Find the official PowerShell documentation library from Microsoft Google MSDN PowerShell. The URL starts with “https://docs.microsoft.com”
---
1. Find the official PowerShell documentation library from Microsoft Google MSDN PowerShell.
- ![image](https://user-images.githubusercontent.com/72273897/160667940-516b4af5-fe92-4e2c-b1e6-bc238e9eb92a.png)




