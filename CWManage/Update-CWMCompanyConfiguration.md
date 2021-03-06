# Update-CWMCompanyConfiguration
## SYNOPSIS
This will update a company configuration.
## SYNTAX
```powershell
Update-CWMCompanyConfiguration [-ID] <Object> [-Operation] <Object> [-Path] <String> [-Value] <Object> [<CommonParameters>]
```
## PARAMETERS
### -ID &lt;Object&gt;
The ID of the config that you are updating.
```
Required                    true
Position                    1
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Operation &lt;Object&gt;
What you are doing with the value. 

replace, add, remove
```
Required                    true
Position                    2
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Path &lt;String&gt;
The value that you want to perform the operation on.
```
Required                    true
Position                    3
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Value &lt;Object&gt;
The value of path.
```
Required                    true
Position                    4
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>$UpdateParam = @{

ID = 1
    Operation = 'replace'
    Path = 'name'
    Value = $NewName
}
Update-CWMCompanyConfiguration @UpdateParam
```

## NOTES
Author: Chris Taylor

Date: 6/11/2019 
## LINKS
http://labtechconsulting.com

https://marketplace.connectwise.com/docs/redoc/manage/company.html#tag/Configurations/paths/~1company~1configurations~1{id}/patch
