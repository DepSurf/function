# Function: <code>acpi_match_platform_list</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81538b30)
Location: drivers/acpi/utils.c:828
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81538b30-ffffffff81538c3a: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156e8f0)
Location: drivers/acpi/utils.c:855
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8156e8f0-ffffffff8156e9fa: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815864b0)
Location: drivers/acpi/utils.c:855
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815864b0-ffffffff815865ba: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b7130)
Location: drivers/acpi/utils.c:842
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815b7130-ffffffff815b722a: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d8360)
Location: drivers/acpi/utils.c:842
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815d8360-ffffffff815d845a: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81681ec0)
Location: drivers/acpi/utils.c:899
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff81681ec0-ffffffff81681fae: acpi_match_platform_list.part.0 (STB_LOCAL)
ffffffff81681fb0-ffffffff81681fd0: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a0ab0)
Location: drivers/acpi/utils.c:895
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff816a0ab0-ffffffff816a0b9e: acpi_match_platform_list.part.0 (STB_LOCAL)
ffffffff816a0ba0-ffffffff816a0bc0: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816838b0)
Location: drivers/acpi/utils.c:925
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff816838b0-ffffffff816839aa: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f8a40)
Location: drivers/acpi/utils.c:939
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff816f8a40-ffffffff816f8b3a: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff818257b0)
Location: drivers/acpi/utils.c:939
Inline: False
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff818257b0-ffffffff818258db: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81956a60)
Location: drivers/acpi/utils.c:1001
Inline: False
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/apei/ghes.c:ghes_get_devices
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81956a60-ffffffff81956b8b: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199ce60)
Location: drivers/acpi/utils.c:1001
Inline: False
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/apei/ghes.c:ghes_get_devices
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8199ce60-ffffffff8199cf8b: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e4ed0)
Location: drivers/acpi/utils.c:1047
Inline: False
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/acpi/apei/ghes.c:ghes_get_devices
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff819e4ed0-ffffffff819e4ffb: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff8000107658f8)
Location: drivers/acpi/utils.c:842
Inline: True
Direct callers:
  - drivers/acpi/arm64/iort.c:arm_smmu_v3_pmcg_add_platdata
```
**Symbols:**

```
ffff8000107658f8-ffff800010765a38: acpi_match_platform_list (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cb690)
Location: drivers/acpi/utils.c:842
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815cb690-ffffffff815cb78a: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b46e0)
Location: drivers/acpi/utils.c:842
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815b46e0-ffffffff815b47da: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cc640)
Location: drivers/acpi/utils.c:842
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815cc640-ffffffff815cc73a: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_platform_list(const struct acpi_platform_list *plat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e64e0)
Location: drivers/acpi/utils.c:842
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815e64e0-ffffffff815e65da: acpi_match_platform_list (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
