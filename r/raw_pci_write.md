# Function: <code>raw_pci_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff816fa4b0)
Location: arch/x86/pci/common.c:51
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff816fa4b0-ffffffff816fa4e9: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8175f2c0)
Location: arch/x86/pci/common.c:50
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff8175f2c0-ffffffff8175f2f9: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8178b7f0)
Location: arch/x86/pci/common.c:50
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff8178b7f0-ffffffff8178b829: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff817aa770)
Location: arch/x86/pci/common.c:49
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff817aa770-ffffffff817aa7a9: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81821c40)
Location: arch/x86/pci/common.c:49
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff81821c40-ffffffff81821c7f: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8186bf10)
Location: arch/x86/pci/common.c:49
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff8186bf10-ffffffff8186bf4f: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8188bff0)
Location: arch/x86/pci/common.c:49
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff8188bff0-ffffffff8188c02f: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff818d6940)
Location: arch/x86/pci/common.c:50
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff818d6940-ffffffff818d697f: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81908cc0)
Location: arch/x86/pci/common.c:50
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff81908cc0-ffffffff81908cff: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81bb951c)
Location: arch/x86/pci/common.c:50
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_write
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
```
**Symbols:**

```
ffffffff81bb9600-ffffffff81bb963f: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81bcde0c)
Location: arch/x86/pci/common.c:51
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_write
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
```
**Symbols:**

```
ffffffff81bcdef0-ffffffff81bcdf2f: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81bc17cc)
Location: arch/x86/pci/common.c:51
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_write
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
```
**Symbols:**

```
ffffffff81bc18b0-ffffffff81bc18ef: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81c91d9c)
Location: arch/x86/pci/common.c:51
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_write
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
```
**Symbols:**

```
ffffffff81c91e80-ffffffff81c91ebf: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81e412bc)
Location: arch/x86/pci/common.c:51
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_write
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
```
**Symbols:**

```
ffffffff81e41430-ffffffff81e41493: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8201b8ec)
Location: arch/x86/pci/common.c:51
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_write
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
```
**Symbols:**

```
ffffffff8201b9f0-ffffffff8201ba53: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8209bf5c)
Location: arch/x86/pci/common.c:51
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_write
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
```
**Symbols:**

```
ffffffff8209c060-ffffffff8209c0c3: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8217370c)
Location: arch/x86/pci/common.c:51
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_write
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
```
**Symbols:**

```
ffffffff82173810-ffffffff82173873: raw_pci_write (STB_GLOBAL)
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/pci.c (ffff8000100a7b50)
Location: arch/arm64/kernel/pci.c:47
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
```
**Symbols:**

```
ffff8000100a7b50-ffff8000100a7bdc: raw_pci_write (STB_GLOBAL)
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
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff818a8080)
Location: arch/x86/pci/common.c:50
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff818a8080-ffffffff818a80bf: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff81862b00)
Location: arch/x86/pci/common.c:50
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff81862b00-ffffffff81862b3f: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff818f96e0)
Location: arch/x86/pci/common.c:50
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff818f96e0-ffffffff818f971f: raw_pci_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int raw_pci_write(unsigned int domain, unsigned int bus, unsigned int devfn, int reg, int len, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8191a840)
Location: arch/x86/pci/common.c:50
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_pci_configuration
  - arch/x86/pci/fixup.c:quirk_pcie_aspm_write
  - arch/x86/pci/common.c:pci_write
```
**Symbols:**

```
ffffffff8191a840-ffffffff8191a87f: raw_pci_write (STB_GLOBAL)
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
