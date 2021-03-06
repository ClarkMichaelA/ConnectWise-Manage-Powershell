# Update-CWMAgreementAddition
## SYNOPSIS
This will update an addition to an agreement.
## SYNTAX
```powershell
Update-CWMAgreementAddition [-AgreementID] <Int32> [-AdditionID] <Int32> [-Operation] <Object> [-Path] <String> [-Value] <String> [<CommonParameters>]
```
## PARAMETERS
### -AgreementID &lt;Int32&gt;
The ID of the agreement that you are updating. Get-CWMAgreement
```
Required                    true
Position                    1
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -AdditionID &lt;Int32&gt;
The ID of the addition that you are updating. Get-CWMAddition
```
Required                    true
Position                    2
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -Operation &lt;Object&gt;
What you are doing with the value. 

add, replace, remove
```
Required                    true
Position                    3
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Path &lt;String&gt;
The value that you want to perform the operation on.
```
Required                    true
Position                    4
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Value &lt;String&gt;
The value of that operation.
```
Required                    true
Position                    5
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>$UpdateParam = @{

AgreementID = $Agreement.id
    AdditionID = $Addition.id
    Operation = 'replace'
    Path = 'quantity'
    Value = $UmbrellaCount
}
Update-CWMAgreementAddition @UpdateParam
```

## NOTES
Author: Chris Taylor

Date: 10/10/2018 
## LINKS
http://labtechconsulting.com

https://developer.connectwise.com/manage/rest?a=Finance&e=AgreementAdditions&o=UPDATE
