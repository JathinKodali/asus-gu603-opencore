# ASUS GU603 OpenCore configuration

**Experimental configuration reference. Not a complete or verified bootable EFI.**

This repository currently contains a sanitized Trial13 configuration for the GU603VV investigation. Machine identity fields are empty and must be generated for the target machine. The actual known-good EFI, its component inventory, and hardware validation must be recovered before publishing a bootable release.

Do not replace a working EFI with this example. Trial configurations reference components that are not bundled here.

The local investigation identifies an i7-13620H and Intel PCI ID 8086:A7A8 revision 4. These are investigation records, not proof of compatibility for other GU603 variants.

## Publication status

- Plist parses successfully.
- Machine identity fields cleared in the example.
- Referenced kexts and ACPI files are not included.
- OpenCore validator and hardware boot validation remain pending.
- WhateverXe source attribution and release linkage remain pending.
