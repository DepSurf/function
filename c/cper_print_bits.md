# Function: <code>cper_print_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff816d3c30)
Location: drivers/firmware/efi/cper.c:81
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff816d3c30-ffffffff816d3d71: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff817375f0)
Location: drivers/firmware/efi/cper.c:81
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff817375f0-ffffffff81737731: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff8176a790)
Location: drivers/firmware/efi/cper.c:81
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff8176a790-ffffffff8176a8d1: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81788b20)
Location: drivers/firmware/efi/cper.c:85
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81788b20-ffffffff81788c61: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff817fefe0)
Location: drivers/firmware/efi/cper.c:85
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff817fefe0-ffffffff817ff121: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:83
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81848ba6-ffffffff81848be4: cper_print_bits.cold.6 (STB_LOCAL)
ffffffff818487f0-ffffffff81848904: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:96
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81874e16-ffffffff81874e54: cper_print_bits.cold.6 (STB_LOCAL)
ffffffff81874a60-ffffffff81874b74: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:84
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff818b9049-ffffffff818b9087: cper_print_bits.cold (STB_LOCAL)
ffffffff818b8c90-ffffffff818b8da4: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:84
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff818eba49-ffffffff818eba87: cper_print_bits.cold (STB_LOCAL)
ffffffff818eb690-ffffffff818eb7a4: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:84
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
```
**Symbols:**

```
ffffffff819bf2e6-ffffffff819bf324: cper_print_bits.cold (STB_LOCAL)
ffffffff819bee00-ffffffff819bef14: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:84
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
```
**Symbols:**

```
ffffffff81c2c07e-ffffffff81c2c0bc: cper_print_bits.cold (STB_LOCAL)
ffffffff819c0870-ffffffff819c0984: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:84
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
```
**Symbols:**

```
ffffffff81c1e2f0-ffffffff81c1e32e: cper_print_bits.cold (STB_LOCAL)
ffffffff819a4f70-ffffffff819a5084: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:82
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
```
**Symbols:**

```
ffffffff81d2f7f7-ffffffff81d2f84e: cper_print_bits.cold (STB_LOCAL)
ffffffff81a521e0-ffffffff81a52300: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:82
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
```
**Symbols:**

```
ffffffff81efbad2-ffffffff81efbb29: cper_print_bits.cold (STB_LOCAL)
ffffffff81bc0e10-ffffffff81bc0f70: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:83
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
```
**Symbols:**

```
ffffffff820a9e7d-ffffffff820a9e96: cper_print_bits.cold (STB_LOCAL)
ffffffff81d65040-ffffffff81d651bf: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:83
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
```
**Symbols:**

```
ffffffff8212b22b-ffffffff8212b244: cper_print_bits.cold (STB_LOCAL)
ffffffff81dd0170-ffffffff81dd02ef: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:83
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
  - drivers/firmware/efi/cper.c:cper_print_proc_generic
```
**Symbols:**

```
ffffffff8220cff4-ffffffff8220d00d: cper_print_bits.cold (STB_LOCAL)
ffffffff81e88ea0-ffffffff81e8901f: cper_print_bits (STB_GLOBAL)
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
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffff800010b5e920)
Location: drivers/firmware/efi/cper.c:84
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffff800010b5e920-ffff800010b5ea78: cper_print_bits (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:84
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81846149-ffffffff81846187: cper_print_bits.cold (STB_LOCAL)
ffffffff81845d90-ffffffff81845ea4: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:84
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff818e08a9-ffffffff818e08e7: cper_print_bits.cold (STB_LOCAL)
ffffffff818e04f0-ffffffff818e0604: cper_print_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void cper_print_bits(const char *pfx, unsigned int bits, const const char * *strs, unsigned int strs_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/cper.c (0)
Location: drivers/firmware/efi/cper.c:84
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff818fd349-ffffffff818fd387: cper_print_bits.cold (STB_LOCAL)
ffffffff818fcf90-ffffffff818fd0a4: cper_print_bits (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
