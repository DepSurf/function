# Function: <code>apei_hest_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/hest.c (ffffffff814b3b60)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_acpi.c:pcie_aer_get_firmware_first
  - drivers/pci/pcie/aer/aerdrv_acpi.c:aer_acpi_firmware_first
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff814b3b60-ffffffff814b3c73: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/hest.c (ffffffff815034e0)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_acpi.c:aer_acpi_firmware_first
  - drivers/pci/pcie/aer/aerdrv_acpi.c:pcie_aer_get_firmware_first
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff815034e0-ffffffff815035eb: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/hest.c (ffffffff815276d0)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_acpi.c:aer_acpi_firmware_first
  - drivers/pci/pcie/aer/aerdrv_acpi.c:pcie_aer_get_firmware_first
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff815276d0-ffffffff815277db: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/hest.c (ffffffff8153a610)
Location: drivers/acpi/apei/hest.c:84
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_acpi.c:aer_acpi_firmware_first
  - drivers/pci/pcie/aer/aerdrv_acpi.c:pcie_aer_get_firmware_first
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff8153a610-ffffffff8153a727: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/hest.c (ffffffff8159d170)
Location: drivers/acpi/apei/hest.c:84
Inline: False
Direct callers:
  - drivers/pci/pcie/aer/aerdrv_acpi.c:aer_acpi_firmware_first
  - drivers/pci/pcie/aer/aerdrv_acpi.c:pcie_aer_get_firmware_first
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff8159d170-ffffffff8159d28a: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:84
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_acpi_firmware_first
  - drivers/pci/pcie/aer.c:aer_set_firmware_first
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff815d4fb1-ffffffff815d4fd3: apei_hest_parse.cold.1 (STB_LOCAL)
ffffffff815d4eb0-ffffffff815d4fb1: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:85
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_acpi_firmware_first
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff815ee761-ffffffff815ee783: apei_hest_parse.cold.1 (STB_LOCAL)
ffffffff815ee660-ffffffff815ee761: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_acpi_firmware_first
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff816204dc-ffffffff81620510: apei_hest_parse.cold (STB_LOCAL)
ffffffff81620400-ffffffff816204dc: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_acpi_firmware_first
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff81641fbc-ffffffff81641ff0: apei_hest_parse.cold (STB_LOCAL)
ffffffff81641ee0-ffffffff81641fbc: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff816ef3fd-ffffffff816ef431: apei_hest_parse.cold (STB_LOCAL)
ffffffff816ef310-ffffffff816ef3ec: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff81c03517-ffffffff81c0354b: apei_hest_parse.cold (STB_LOCAL)
ffffffff8170c760-ffffffff8170c83c: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:89
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff81bf4f01-ffffffff81bf4f35: apei_hest_parse.cold (STB_LOCAL)
ffffffff816eddc0-ffffffff816ede9c: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:89
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff81cf2300-ffffffff81cf2339: apei_hest_parse.cold (STB_LOCAL)
ffffffff81767e50-ffffffff81767f78: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/hest.c (ffffffff81eba35c)
Location: drivers/acpi/apei/hest.c:91
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff81eba35c-ffffffff81eba49f: apei_hest_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/hest.c (ffffffff819e4fb0)
Location: drivers/acpi/apei/hest.c:91
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff819e4fb0-ffffffff819e5138: apei_hest_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/hest.c (ffffffff81a2d5d0)
Location: drivers/acpi/apei/hest.c:91
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff81a2d5d0-ffffffff81a2d758: apei_hest_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/hest.c (ffffffff81a78810)
Location: drivers/acpi/apei/hest.c:91
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff81a78810-ffffffff81a78998: apei_hest_parse (STB_LOCAL)
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
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/hest.c (ffff8000107ace28)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_acpi_firmware_first
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffff8000107ace28-ffff8000107acf88: apei_hest_parse (STB_GLOBAL)
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
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_acpi_firmware_first
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff815fe3cc-ffffffff815fe400: apei_hest_parse.cold (STB_LOCAL)
ffffffff815fe2f0-ffffffff815fe3cc: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_acpi_firmware_first
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff81635dfc-ffffffff81635e30: apei_hest_parse.cold (STB_LOCAL)
ffffffff81635d20-ffffffff81635dfc: apei_hest_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int apei_hest_parse(apei_hest_func_t func, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/hest.c (0)
Location: drivers/acpi/apei/hest.c:83
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_acpi_firmware_first
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff8165010c-ffffffff81650140: apei_hest_parse.cold (STB_LOCAL)
ffffffff81650030-ffffffff8165010c: apei_hest_parse (STB_GLOBAL)
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
