# New-CWMTicketNote
## SYNOPSIS
Add a note to a CW Manage ticket.
## SYNTAX
```powershell
New-CWMTicketNote [[-id] <Int32>] [[-ticketId] <Int32>] [[-text] <String>] [[-detailDescriptionFlag] <Boolean>] [[-internalAnalysisFlag] <Boolean>] [[-resolutionFlag] <Boolean>] [[-member] <Object>] [[-contact] <Object>] [[-customerUpdatedFlag] <Boolean>] [[-processNotifications] <Boolean>] [[-dateCreated] <String>] [[-createdBy] <String>] [[-internalFlag] <Boolean>] [[-externalFlag] <Boolean>] [[-_info] <Object>] [<CommonParameters>]
```
## PARAMETERS
### -id &lt;Int32&gt;

```
Required                    false
Position                    1
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -ticketId &lt;Int32&gt;

```
Required                    false
Position                    2
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -text &lt;String&gt;

```
Required                    false
Position                    3
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -detailDescriptionFlag &lt;Boolean&gt;

```
Required                    false
Position                    4
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -internalAnalysisFlag &lt;Boolean&gt;

```
Required                    false
Position                    5
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -resolutionFlag &lt;Boolean&gt;

```
Required                    false
Position                    6
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -member &lt;Object&gt;

```
Required                    false
Position                    7
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -contact &lt;Object&gt;

```
Required                    false
Position                    8
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -customerUpdatedFlag &lt;Boolean&gt;

```
Required                    false
Position                    9
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -processNotifications &lt;Boolean&gt;

```
Required                    false
Position                    10
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -dateCreated &lt;String&gt;

```
Required                    false
Position                    11
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -createdBy &lt;String&gt;

```
Required                    false
Position                    12
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -internalFlag &lt;Boolean&gt;

```
Required                    false
Position                    13
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -externalFlag &lt;Boolean&gt;

```
Required                    false
Position                    14
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -_info &lt;Object&gt;

```
Required                    false
Position                    15
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>New-CWMTicketNote -ticketId $Ticket.id -text 'New note'

Create a new note.
```

## NOTES
Author: Chris Taylor

Date: 1/21/2019 
## LINKS
http://labtechconsulting.com

https://developer.connectwise.com/products/manage/rest?a=Service&e=TicketNotes&o=CREATE
