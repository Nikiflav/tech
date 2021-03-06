---
uid: cao-GETVALUE
---

# GETVALUE - Calculated Attribute Operator

| Specification         | Value                                                        |
| --------------------- | ------------------------------------------------------------ |
| Description           | Gets the value from the current object.          |
| Parameter 1 Name      | Value                                                        |
| Parameter 1 Type      | attribute value                                   |
| Parameter 2 Name      | -                                                            |
| Parameter 2 Type      | -                                                            |
| Parameter 3 Name      | -                                                            |
| Parameter 3 Type      | -                                                            |
| Return Value          | Value                                                         |

## Example

The following example returns the value of the Notes of the current Sales Order Line:
```
10: GETVALUE ATTRIB:Notes             
```
OUTPUT: If 'Notes = Apple', the output will be 'Apple'.

> [!NOTE]
> The repository of the attribute is *Crm.Sales.SalesOrderLiness*

