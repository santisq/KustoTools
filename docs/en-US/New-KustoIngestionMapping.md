---
external help file: PowerShellKusto.dll-Help.xml
Module Name: PowerShellKusto
online version: https://github.com/santisq/PowerShellKusto/blob/main/docs/en-US/New-KustoIngestionMapping.md
schema: 2.0.0
---

# New-KustoIngestionMapping

## SYNOPSIS

{{ Fill in the Synopsis }}

## SYNTAX

```powershell
New-KustoIngestionMapping
    [-Kind <IngestionMappingKind>]
    [-Reference <String>]
    [-Columns <ColumnMapping[]>]
    [<CommonParameters>]
```

## DESCRIPTION

{{ Fill in the Description }}

## EXAMPLES

### Example 1

```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -Columns

{{ Fill Columns Description }}

```yaml
Type: ColumnMapping[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Kind

{{ Fill Kind Description }}

```yaml
Type: IngestionMappingKind
Parameter Sets: (All)
Aliases:
Accepted values: Unknown, Csv, Json, Avro, Parquet, SStream, Orc, ApacheAvro, W3CLogFile

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Reference

{{ Fill Reference Description }}

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

### -ProgressAction

{{ Fill ProgressAction Description }}

```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: proga

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters

This cmdlet supports the common parameters.
For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### Kusto.Ingest.IngestionMapping

## NOTES

## RELATED LINKS
