---
-api-id: T:Windows.ApplicationModel.Contacts.ContactStoreAccessType
-api-type: winrt enum
---

<!-- Enumeration syntax
public enum Windows.ApplicationModel.Contacts.ContactStoreAccessType : int
-->

# ContactStoreAccessType

## -description
Defines the type of access the app has to the [ContactStore](contactstore.md).

## -enum-fields
### -field AppContactsReadWrite:0
Read and write contacts that belong to the app only.

### -field AllContactsReadOnly:1
Read access to all app and system contacts. This value requires the contacts capability. See [App capability declarations](http://msdn.microsoft.com/library/25b18ba5-e584-4537-9f19-bb2c8c52dfe1) for more information.

### -field AllContactsReadWrite:2
Read and write access to all app and system contacts. This value is not available to all apps. Your developer account must be specially provisioned by Microsoft in order to request this level of access.


## -remarks

## -examples

## -see-also