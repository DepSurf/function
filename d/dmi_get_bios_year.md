# Function: <code>dmi_get_bios_year</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818439c0)
Location: drivers/firmware/dmi_scan.c:1040
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff818439c0-ffffffff81843a1d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8186f9e0)
Location: drivers/firmware/dmi_scan.c:1040
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff8186f9e0-ffffffff8186fa3d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818b3c90)
Location: drivers/firmware/dmi_scan.c:1043
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff818b3c90-ffffffff818b3ced: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818e65b0)
Location: drivers/firmware/dmi_scan.c:1043
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff818e65b0-ffffffff818e660d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819b97b0)
Location: drivers/firmware/dmi_scan.c:1079
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/direct.c:pci_sanity_check
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff819b97b0-ffffffff819b980d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819bbc20)
Location: drivers/firmware/dmi_scan.c:1079
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/direct.c:pci_sanity_check
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff819bbc20-ffffffff819bbc7d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819a0420)
Location: drivers/firmware/dmi_scan.c:1080
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/direct.c:pci_sanity_check
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff819a0420-ffffffff819a047d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81a4d1c0)
Location: drivers/firmware/dmi_scan.c:1080
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/direct.c:pci_sanity_check
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff81a4d1c0-ffffffff81a4d21d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81bbba30)
Location: drivers/firmware/dmi_scan.c:1080
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/direct.c:pci_sanity_check
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff81bbba30-ffffffff81bbbaa0: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81d611b0)
Location: drivers/firmware/dmi_scan.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_sanity_check
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff81d611b0-ffffffff81d61220: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81dcc270)
Location: drivers/firmware/dmi_scan.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_sanity_check
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff81dcc270-ffffffff81dcc2e0: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81e84db0)
Location: drivers/firmware/dmi_scan.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - arch/x86/pci/direct.c:pci_sanity_check
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff81e84db0-ffffffff81e84e20: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffff800010b4ddf0)
Location: drivers/firmware/dmi_scan.c:1043
Inline: False
```
**Symbols:**

```
ffff800010b4ddf0-ffff800010b4de6c: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (c0c34e84)
Location: drivers/firmware/dmi_scan.c:1043
Inline: False
```
**Symbols:**

```
c0c34e84-c0c34f04: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: include/linux/dmi.h:134
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: include/linux/dmi.h:134
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81889330)
Location: drivers/firmware/dmi_scan.c:1043
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff81889330-ffffffff8188938d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81840cb0)
Location: drivers/firmware/dmi_scan.c:1043
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff81840cb0-ffffffff81840d0d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818db410)
Location: drivers/firmware/dmi_scan.c:1043
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff818db410-ffffffff818db46d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dmi_get_bios_year();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818f7f30)
Location: drivers/firmware/dmi_scan.c:1043
Inline: False
Direct callers:
  - arch/x86/kernel/i8237.c:i8237A_init_ops
  - drivers/acpi/sleep.c:acpi_sleep_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/acpi.c:pci_acpi_crs_quirks
```
**Symbols:**

```
ffffffff818f7f30-ffffffff818f7f8d: dmi_get_bios_year (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
