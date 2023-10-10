**OmenMon** is a lightweight application that interacts with the Embedded Controller (EC) and WMI BIOS routines of an _HP Omen_ laptop in order to access hardware settings, in particular to query temperature sensors, and dynamically adjust fan speeds.

**OmenMon** is designed to run in the background with minimal resource overhead.

**OmenMon** also features a command-line mode where various BIOS and EC read and write operations can be performed manually.

The Embedded Controller mode should work on all laptops. BIOS features are specific to _HP_ devices with a compatible BIOS interface exposed by the `ACPI\PNP0C14` driver.
