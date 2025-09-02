# Remove Apps Policy Editor for 25H2+

This simple script allows you to use the RemoveDefaultMicrosoftStorePackages policy introduced in Windows 11 25H2 on non-supported Windows editions. The script will detect your current edition, 
if this edition is not Enterprise or Education it will convert the OS to Enterprise. After restarting, the selected apps will be removed and the Windows edition will be reset. [**Read More**](https://support.microsoft.com/en-us/topic/policy-based-removal-of-pre-installed-microsoft-store-apps-e1d41a92-b658-4511-95a6-0fbcc02b4e9c)

## How to Run

**Run PowerShell as Admin**

```PowerShell
 iwr 'https://raw.githubusercontent.com/zoicware/RemoveAppsPolicyEditor/main/RemoveAppsPolicyEditor.ps1' | iex 
```

## Preview
<img width="386" height="393" alt="image" src="https://github.com/user-attachments/assets/8bf186f4-4476-4345-81b6-2352a5915636" />



> [!NOTE]
> You should be able to select additional packages outside of the default list in Group Policy however, these do not get removed at least in the initial build of 25H2
> 
