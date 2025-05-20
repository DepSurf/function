# Function: <code>raw_pci_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff816fa440)
Location: arch/x86/pci/common.c:41
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff816fa440-ffffffff816fa478: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8175f250)
Location: arch/x86/pci/common.c:40
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff8175f250-ffffffff8175f288: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8178b780)
Location: arch/x86/pci/common.c:40
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff8178b780-ffffffff8178b7b8: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff817aa700)
Location: arch/x86/pci/common.c:39
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff817aa700-ffffffff817aa738: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81821bd0)
Location: arch/x86/pci/common.c:39
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff81821bd0-ffffffff81821c0e: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8186bea0)
Location: arch/x86/pci/common.c:39
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff8186bea0-ffffffff8186bede: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8188bf80)
Location: arch/x86/pci/common.c:39
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff8188bf80-ffffffff8188bfbe: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff818d68d0)
Location: arch/x86/pci/common.c:40
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff818d68d0-ffffffff818d690e: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81908c50)
Location: arch/x86/pci/common.c:40
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff81908c50-ffffffff81908c8e: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81bb957c)
Location: arch/x86/pci/common.c:40
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_read
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
```
**Symbols:**

```
ffffffff81bb95c0-ffffffff81bb95fe: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81bcde6c)
Location: arch/x86/pci/common.c:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_read
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
```
**Symbols:**

```
ffffffff81bcdeb0-ffffffff81bcdeee: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81bc182c)
Location: arch/x86/pci/common.c:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_read
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
```
**Symbols:**

```
ffffffff81bc1870-ffffffff81bc18ae: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81c91dfc)
Location: arch/x86/pci/common.c:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_read
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
```
**Symbols:**

```
ffffffff81c91e40-ffffffff81c91e7e: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81e4134c)
Location: arch/x86/pci/common.c:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_read
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
```
**Symbols:**

```
ffffffff81e413c0-ffffffff81e41422: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8201b84c)
Location: arch/x86/pci/common.c:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_read
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
```
**Symbols:**

```
ffffffff8201b970-ffffffff8201b9d2: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8209bebc)
Location: arch/x86/pci/common.c:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_read
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
```
**Symbols:**

```
ffffffff8209bfe0-ffffffff8209c042: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8217366c)
Location: arch/x86/pci/common.c:41
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_read
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
```
**Symbols:**

```
ffffffff82173790-ffffffff821737f2: raw_pci_read (STB_GLOBAL)
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
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/pci.c (ffff8000100a7ac0)
Location: arch/arm64/kernel/pci.c:37
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
```
**Symbols:**

```
ffff8000100a7ac0-ffff8000100a7b4c: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff818a8010)
Location: arch/x86/pci/common.c:40
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff818a8010-ffffffff818a804e: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81862a90)
Location: arch/x86/pci/common.c:40
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff81862a90-ffffffff81862ace: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff818f9670)
Location: arch/x86/pci/common.c:40
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff818f9670-ffffffff818f96ae: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int raw_pci_read(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8191a7d0)
Location: arch/x86/pci/common.c:40
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_read_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_read
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/numachip.c:pci_numachip_init
  - arch/x86/pci/common.c:pci_read
```
**Symbols:**

```
ffffffff8191a7d0-ffffffff8191a80e: raw_pci_read (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
