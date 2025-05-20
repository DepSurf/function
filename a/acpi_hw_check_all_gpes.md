# Function: <code>acpi_hw_check_all_gpes</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u8 acpi_hw_check_all_gpes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8160f42a)
Location: drivers/acpi/acpica/hwgpe.c:573
Inline: False
```
**Symbols:**

```
ffffffff8160f42a-ffffffff8160f494: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u8 acpi_hw_check_all_gpes(acpi_handle gpe_skip_device, u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816bb7a4)
Location: drivers/acpi/acpica/hwgpe.c:587
Inline: False
```
**Symbols:**

```
ffffffff816bb7a4-ffffffff816bb871: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 acpi_hw_check_all_gpes(acpi_handle gpe_skip_device, u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816d92b2)
Location: drivers/acpi/acpica/hwgpe.c:657
Inline: False
```
**Symbols:**

```
ffffffff816d92b2-ffffffff816d937f: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 acpi_hw_check_all_gpes(acpi_handle gpe_skip_device, u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816bb23f)
Location: drivers/acpi/acpica/hwgpe.c:657
Inline: False
```
**Symbols:**

```
ffffffff816bb23f-ffffffff816bb30c: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 acpi_hw_check_all_gpes(acpi_handle gpe_skip_device, u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff817322a6)
Location: drivers/acpi/acpica/hwgpe.c:657
Inline: False
```
**Symbols:**

```
ffffffff817322a6-ffffffff81732373: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 acpi_hw_check_all_gpes(acpi_handle gpe_skip_device, u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff818630c4)
Location: drivers/acpi/acpica/hwgpe.c:657
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
```
**Symbols:**

```
ffffffff818630c4-ffffffff81863195: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u8 acpi_hw_check_all_gpes(acpi_handle gpe_skip_device, u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (0)
Location: drivers/acpi/acpica/hwgpe.c:657
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
```
**Symbols:**

```
ffffffff820920d8-ffffffff820920f7: acpi_hw_check_all_gpes.cold (STB_LOCAL)
ffffffff819a0a90-ffffffff819a0b79: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u8 acpi_hw_check_all_gpes(acpi_handle gpe_skip_device, u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (0)
Location: drivers/acpi/acpica/hwgpe.c:657
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
```
**Symbols:**

```
ffffffff821129cc-ffffffff821129eb: acpi_hw_check_all_gpes.cold (STB_LOCAL)
ffffffff819e7770-ffffffff819e7859: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u8 acpi_hw_check_all_gpes(acpi_handle gpe_skip_device, u32 gpe_skip_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (0)
Location: drivers/acpi/acpica/hwgpe.c:657
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
```
**Symbols:**

```
ffffffff821f0720-ffffffff821f073f: acpi_hw_check_all_gpes.cold (STB_LOCAL)
ffffffff81a324c0-ffffffff81a325a9: acpi_hw_check_all_gpes (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u8 acpi_hw_check_all_gpes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815f0a11)
Location: drivers/acpi/acpica/hwgpe.c:573
Inline: False
```
**Symbols:**

```
ffffffff815f0a11-ffffffff815f0a5e: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u8 acpi_hw_check_all_gpes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815dbfe3)
Location: drivers/acpi/acpica/hwgpe.c:573
Inline: False
```
**Symbols:**

```
ffffffff815dbfe3-ffffffff815dc030: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u8 acpi_hw_check_all_gpes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8160370a)
Location: drivers/acpi/acpica/hwgpe.c:573
Inline: False
```
**Symbols:**

```
ffffffff8160370a-ffffffff81603774: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u8 acpi_hw_check_all_gpes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8161d5ba)
Location: drivers/acpi/acpica/hwgpe.c:573
Inline: False
```
**Symbols:**

```
ffffffff8161d5ba-ffffffff8161d624: acpi_hw_check_all_gpes (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>acpi_handle gpe_skip_device</code>
</li>
<li>
<b>Param added. </b>
<code>u32 gpe_skip_number</code>
</li>
</ul>
</details>
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
