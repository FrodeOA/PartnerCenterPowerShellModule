# New-PCAddress

Returns a PowerShell object with the attributes needed to create a new address.

## SYNTAX

```powershell
New-PCAddress [-Address1Line] <String> [[-AddressLine2] <String>] [-City] <String> [-State] <String> [-PostalCode] <String> [-Country] <String> [[-Region] <String>] [<CommonParameters>]
```

## DESCRIPTION

The New-PCAddress cmdlet returns a PowerShell object with all of address properties.

## PARAMETERS

### -AddressLine1 &lt;String&gt;

Specifies the first line of the new address.
```
Required?                    true
Position?                    1
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -AddressLine2 &lt;String&gt;

Specifies address line 2 for the new address.

```
Required?                    false
Position?                    2
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -City &lt;String&gt;

Specifies the city name.

```
Required?                    true
Position?                    3
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -State &lt;String&gt;

Specifies the state name.

```
Required?                    true
Position?                    4
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -PostalCode &lt;String&gt;

Specifies the postal code.

```
Required?                    true
Position?                    5
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -Country &lt;String&gt;

Specifies the country

```
Required?                    true
Position?                    6
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -Region &lt;String&gt;

Specifies the region.

```
Required?                    false
Position?                    7
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

## INPUTS

## OUTPUTS

## NOTES

## EXAMPLES

### EXAMPLE 1

Create a new address object for an address and assign it to the $add variable.

```powershell
PS C:\>$add = New-PCAddress -AddressLine1 '1 Microsoft Way' -City 'Redmond' -State 'WA' -Country 'US' -PostalCode '95802'
```
