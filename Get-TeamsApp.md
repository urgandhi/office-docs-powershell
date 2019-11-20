---
external help file: Microsoft.TeamsCmdlets.PowerShell.Custom.dll-Help.xml
Module Name: MicrosoftTeams
online version:
schema: 2.0.0
---

# Get-TeamsApp

## SYNOPSIS
Returns app information from the Teams tenant app store.

## SYNTAX

```
Get-TeamsApp [-Id <String>] [-ExternalId <String>] [-DisplayName <String>] [-DistributionMethod <String>]
 [<CommonParameters>]
```

## DESCRIPTION
Use any optional parameter to retrieve app information from the Teams tenant app store.

## EXAMPLES

### Example 1
```powershell
PS C:\> Get-TeamsApp -Id b9cc7986-dd56-4b57-ab7d-9c4e5288b775
```

### Example 2
```powershell
PS C:\> Get-TeamsApp -ExternalId b00080be-9b31-4927-9e3e-fa8024a7d98a -DisplayName <String>] [-DistributionMethod <String>]
```

### Example 3
```powershell
PS C:\> Get-TeamsApp -DisplayName SampleApp -DistributionMethod organization
```

## PARAMETERS

### -DisplayName
Name of the app visible to users

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DistributionMethod
The type of app in Teams: global or organization. For LOB apps, use "organization"

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExternalId
The external ID of the app, provided by the app developer and used by Azure Active Directory

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
The app's ID generated by Teams (different from the external ID)

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None


## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS