# Function: <code>acpi_sleep_run_lps0_dsm</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814f8515)
Location: drivers/acpi/sleep.c:683
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_prepare
  - drivers/acpi/sleep.c:acpi_freeze_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_prepare
  - drivers/acpi/sleep.c:acpi_freeze_prepare
```
**Symbols:**

```
ffffffff814f8470-ffffffff814f84eb: acpi_sleep_run_lps0_dsm.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81539905)
Location: drivers/acpi/sleep.c:866
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff81539860-ffffffff815398db: acpi_sleep_run_lps0_dsm.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8156f565)
Location: drivers/acpi/sleep.c:898
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff8156f4c0-ffffffff8156f538: acpi_sleep_run_lps0_dsm.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81587113)
Location: drivers/acpi/sleep.c:895
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff81587080-ffffffff815870f8: acpi_sleep_run_lps0_dsm.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b7d73)
Location: drivers/acpi/sleep.c:885
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
**Symbols:**

```
ffffffff815b7ce0-ffffffff815b7d58: acpi_sleep_run_lps0_dsm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815d8f70)
Location: drivers/acpi/sleep.c:876
Inline: True
```
**Symbols:**

```
ffffffff815d8f70-ffffffff815d8fe8: acpi_sleep_run_lps0_dsm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81683040)
Location: drivers/acpi/sleep.c:879
Inline: True
```
**Symbols:**

```
ffffffff81683040-ffffffff816830b8: acpi_sleep_run_lps0_dsm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff816ba050)
Location: drivers/acpi/x86/s2idle.c:318
Inline: True
```
**Symbols:**

```
ffffffff816ba050-ffffffff816ba0ca: acpi_sleep_run_lps0_dsm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff8169bf50)
Location: drivers/acpi/x86/s2idle.c:320
Inline: True
```
**Symbols:**

```
ffffffff8169bf50-ffffffff8169bfca: acpi_sleep_run_lps0_dsm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_sleep_run_lps0_dsm(unsigned int func, unsigned int func_mask, guid_t dsm_guid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81711fd0)
Location: drivers/acpi/x86/s2idle.c:320
Inline: False
```
**Symbols:**

```
ffffffff81711fd0-ffffffff8171206a: acpi_sleep_run_lps0_dsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_sleep_run_lps0_dsm(unsigned int func, unsigned int func_mask, guid_t dsm_guid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff818412f0)
Location: drivers/acpi/x86/s2idle.c:322
Inline: False
```
**Symbols:**

```
ffffffff818412f0-ffffffff818413bb: acpi_sleep_run_lps0_dsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_sleep_run_lps0_dsm(unsigned int func, unsigned int func_mask, guid_t dsm_guid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81977d80)
Location: drivers/acpi/x86/s2idle.c:323
Inline: False
```
**Symbols:**

```
ffffffff81977d80-ffffffff81977e4b: acpi_sleep_run_lps0_dsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void acpi_sleep_run_lps0_dsm(unsigned int func, unsigned int func_mask, guid_t dsm_guid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/s2idle.c (0)
Location: drivers/acpi/x86/s2idle.c:355
Inline: False
```
**Symbols:**

```
ffffffff819be820-ffffffff819be936: acpi_sleep_run_lps0_dsm (STB_LOCAL)
ffffffff821125de-ffffffff821125f3: acpi_sleep_run_lps0_dsm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void acpi_sleep_run_lps0_dsm(unsigned int func, unsigned int func_mask, guid_t dsm_guid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/s2idle.c (0)
Location: drivers/acpi/x86/s2idle.c:393
Inline: False
```
**Symbols:**

```
ffffffff81a09020-ffffffff81a09136: acpi_sleep_run_lps0_dsm (STB_LOCAL)
ffffffff821f0346-ffffffff821f035b: acpi_sleep_run_lps0_dsm.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b5460)
Location: drivers/acpi/sleep.c:876
Inline: True
```
**Symbols:**

```
ffffffff815b5460-ffffffff815b54d8: acpi_sleep_run_lps0_dsm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cd250)
Location: drivers/acpi/sleep.c:876
Inline: True
```
**Symbols:**

```
ffffffff815cd250-ffffffff815cd2c8: acpi_sleep_run_lps0_dsm.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815e70f0)
Location: drivers/acpi/sleep.c:876
Inline: True
```
**Symbols:**

```
ffffffff815e70f0-ffffffff815e7168: acpi_sleep_run_lps0_dsm.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
