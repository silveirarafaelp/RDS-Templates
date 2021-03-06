---
external help file: Microsoft.RDInfra.RdPowershell.dll-Help.xml
Module Name: Microsoft.RDInfra.RdPowershell
online version:
schema: 2.0.0
---

# Set-RdsTenant

## SYNOPSIS
Sets properties for an existing RD tenant.

## SYNTAX

```
Set-RdsTenant [-Name] <String> [-FriendlyName <String>] [-Description <String>]
 [-SsoAdfsAuthority <String>] [-SsoClientId <String>] [-SsoClientSecret <String>] [<CommonParameters>]
```

## DESCRIPTION
Sets properties for an existing RD tenant.

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

## PARAMETERS

### -Description
A 512 character string that describes the Tenant to help administrators. Any character is allowed. 

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

### -FriendlyName
A 256 character string that is intended for display to end users. Any character is allowed.

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

### -Name
Name of Tenant.

```yaml
Type: String
Parameter Sets: (All)
Aliases: TenantName

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -SsoAdfsAuthority


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

### -SsoClientId
Specifies the client ID for the WVD application. Example: https://desktopinn.com

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

### -SsoClientSecret
Specifies the client secret generated by running Add-AdfsClient to add the WVD client ID to the ADFS in the customer‘s RD tenant environment. Example: zw26ykuGzIs4sG_wSJntJvBsvgnH5J_NfakWuQJQ 

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
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String

## OUTPUTS

### Microsoft.RDInfra.RDManagementData.RdMgmtTenant

## NOTES

## RELATED LINKS
