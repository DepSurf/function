# Function: <code>acpi_mask_gpe</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81504d2e)
Location: drivers/acpi/acpica/evxfgpe.c:274
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff81504d2e-ffffffff81504d92: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815152a2)
Location: drivers/acpi/acpica/evxfgpe.c:274
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff815152a2-ffffffff81515306: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8155f856)
Location: drivers/acpi/acpica/evxfgpe.c:274
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff8155f856-ffffffff8155f8f8: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81596648)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff81596648-ffffffff815966ea: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815aed4c)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff815aed4c-ffffffff815aedee: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e05a9)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff815e05a9-ffffffff815e064c: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816018ec)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff816018ec-ffffffff8160198f: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816adb31)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff816adb31-ffffffff816adbd4: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816cb470)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff816cb470-ffffffff816cb513: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816ad43c)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff816ad43c-ffffffff816ad4df: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff817241fb)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff817241fb-ffffffff8172429e: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff818547b9)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff818547b9-ffffffff8185486a: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8198f110)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff8198f110-ffffffff8198f1c1: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff819d5bb0)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff819d5bb0-ffffffff819d5c61: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81a20840)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff81a20840-ffffffff81a208f1: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: include/acpi/acpixf.h:725
Inline: True
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e9132)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff815e9132-ffffffff815e9195: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815d475a)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff815d475a-ffffffff815d47bd: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815f5bcc)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff815f5bcc-ffffffff815f5c6f: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8160fa7c)
Location: drivers/acpi/acpica/evxfgpe.c:259
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff8160fa7c-ffffffff8160fb1f: acpi_mask_gpe (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
