# Function: <code>iosf_mbi_block_punit_i2c_access</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108fcd0)
Location: arch/x86/platform/intel/iosf_mbi.c:300
Inline: False
```
**Symbols:**

```
ffffffff8108fcd0-ffffffff8108fed3: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:291
Inline: False
```
**Symbols:**

```
ffffffff81093c51-ffffffff81093cf7: iosf_mbi_block_punit_i2c_access.cold (STB_LOCAL)
ffffffff81093920-ffffffff81093aa1: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81094957)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: True
```
**Symbols:**

```
ffffffff81094ba5-ffffffff81094c29: iosf_mbi_block_punit_i2c_access.cold (STB_LOCAL)
ffffffff81094910-ffffffff81094af4: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81099de0)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: True
```
**Symbols:**

```
ffffffff81099bf0-ffffffff81099dd4: iosf_mbi_block_punit_i2c_access.part.0 (STB_LOCAL)
ffffffff81099ea4-ffffffff81099f95: iosf_mbi_block_punit_i2c_access.part.0.cold (STB_LOCAL)
ffffffff81099de0-ffffffff81099e18: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81098ed0)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: True
```
**Symbols:**

```
ffffffff81098ce0-ffffffff81098ec4: iosf_mbi_block_punit_i2c_access.part.0 (STB_LOCAL)
ffffffff81bda407-ffffffff81bda4f8: iosf_mbi_block_punit_i2c_access.part.0.cold (STB_LOCAL)
ffffffff81098ed0-ffffffff81098f08: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81099710)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: True
```
**Symbols:**

```
ffffffff81099520-ffffffff81099704: iosf_mbi_block_punit_i2c_access.part.0 (STB_LOCAL)
ffffffff81bcc52f-ffffffff81bcc620: iosf_mbi_block_punit_i2c_access.part.0.cold (STB_LOCAL)
ffffffff81099710-ffffffff81099748: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810a9730)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: True
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
```
**Symbols:**

```
ffffffff810a94f0-ffffffff810a972f: iosf_mbi_block_punit_i2c_access.part.0 (STB_LOCAL)
ffffffff81ca27db-ffffffff81ca28cc: iosf_mbi_block_punit_i2c_access.part.0.cold (STB_LOCAL)
ffffffff810a9730-ffffffff810a9768: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
```
**Symbols:**

```
ffffffff81e52040-ffffffff81e52136: iosf_mbi_block_punit_i2c_access.cold (STB_LOCAL)
ffffffff810bed90-ffffffff810bf029: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810da9c0)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
```
**Symbols:**

```
ffffffff810da9c0-ffffffff810dad42: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e5f50)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
```
**Symbols:**

```
ffffffff810e5f50-ffffffff810e62d2: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810ee340)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: False
Direct callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power
```
**Symbols:**

```
ffffffff810ee340-ffffffff810ee6c5: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093917)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: True
```
**Symbols:**

```
ffffffff81093b65-ffffffff81093be9: iosf_mbi_block_punit_i2c_access.cold (STB_LOCAL)
ffffffff810938d0-ffffffff81093ab4: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810823a7)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: True
```
**Symbols:**

```
ffffffff810825f5-ffffffff81082679: iosf_mbi_block_punit_i2c_access.cold (STB_LOCAL)
ffffffff81082360-ffffffff81082544: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810938c7)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: True
```
**Symbols:**

```
ffffffff81093b15-ffffffff81093b99: iosf_mbi_block_punit_i2c_access.cold (STB_LOCAL)
ffffffff81093880-ffffffff81093a64: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iosf_mbi_block_punit_i2c_access();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81095e17)
Location: arch/x86/platform/intel/iosf_mbi.c:312
Inline: True
```
**Symbols:**

```
ffffffff81096063-ffffffff810960e7: iosf_mbi_block_punit_i2c_access.cold (STB_LOCAL)
ffffffff81095dd0-ffffffff81095fb2: iosf_mbi_block_punit_i2c_access (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
