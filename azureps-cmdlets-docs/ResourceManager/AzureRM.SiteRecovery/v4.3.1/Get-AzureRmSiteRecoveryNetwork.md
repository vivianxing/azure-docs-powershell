---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
ms.assetid: 4CC5E6A8-B51A-49ED-BB93-FE63F1500780
online version:
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/preview/src/ResourceManager/SiteRecovery/Commands.SiteRecovery/help/Get-AzureRmSiteRecoveryNetwork.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/preview/src/ResourceManager/SiteRecovery/Commands.SiteRecovery/help/Get-AzureRmSiteRecoveryNetwork.md
gitcommit: https://github.com/Azure/azure-powershell/blob/1fa63f743120d7a7cd6cbb28ee43cd0f4c654af9
---

# Get-AzureRmSiteRecoveryNetwork

## SYNOPSIS
Gets information about the networks managed by Site Recovery for the current vault.

## SYNTAX

### Default (Default)
```
Get-AzureRmSiteRecoveryNetwork [<CommonParameters>]
```

### ByServerObject
```
Get-AzureRmSiteRecoveryNetwork -Server <ASRServer> [<CommonParameters>]
```

### ByNameLegacy
```
Get-AzureRmSiteRecoveryNetwork -Server <ASRServer> -Name <String> [<CommonParameters>]
```

### ByFriendlyNameLegacy
```
Get-AzureRmSiteRecoveryNetwork -Server <ASRServer> -FriendlyName <String> [<CommonParameters>]
```

### ByFabricObject
```
Get-AzureRmSiteRecoveryNetwork -Fabric <ASRFabric> [<CommonParameters>]
```

### ByName
```
Get-AzureRmSiteRecoveryNetwork -Fabric <ASRFabric> -Name <String> [<CommonParameters>]
```

### ByFriendlyName
```
Get-AzureRmSiteRecoveryNetwork -Fabric <ASRFabric> -FriendlyName <String> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmSiteRecoveryNetwork** cmdlet gets information about Azure Site Recovery networks for the current Azure Site Recovery vault.

## EXAMPLES

## PARAMETERS

### -Fabric
```yaml
Type: ASRFabric
Parameter Sets: ByFabricObject, ByName, ByFriendlyName
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -FriendlyName
Specifies the friendly name of the virtual machine network.

```yaml
Type: String
Parameter Sets: ByFriendlyNameLegacy
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: ByFriendlyName
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Name
Specifies the name of the virtual machine network.

```yaml
Type: String
Parameter Sets: ByNameLegacy
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: ByName
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Server
```yaml
Type: ASRServer
Parameter Sets: ByServerObject, ByNameLegacy, ByFriendlyNameLegacy
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### ASRFabric

Parameter 'Fabric' accepts value of type 'ASRFabric' from the pipeline

### String

Parameter 'FriendlyName' accepts value of type 'String' from the pipeline

### String

Parameter 'FriendlyName' accepts value of type 'String' from the pipeline

### String

Parameter 'Name' accepts value of type 'String' from the pipeline

### String

Parameter 'Name' accepts value of type 'String' from the pipeline

### ASRServer

Parameter 'Server' accepts value of type 'ASRServer' from the pipeline

## OUTPUTS

### System.Collections.Generic.IEnumerable`1[Microsoft.Azure.Commands.SiteRecovery.ASRNetwork]

## NOTES

## RELATED LINKS

