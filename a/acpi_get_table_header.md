# Function: <code>acpi_get_table_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff814a5aac)
Location: drivers/acpi/acpica/tbxface.c:206
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff814a5aac-ffffffff814a5b68: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff814f4d88)
Location: drivers/acpi/acpica/tbxface.c:206
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
```
**Symbols:**

```
ffffffff814f4d88-ffffffff814f4e43: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81517ad7)
Location: drivers/acpi/acpica/tbxface.c:222
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
```
**Symbols:**

```
ffffffff81517ad7-ffffffff81517b92: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81528319)
Location: drivers/acpi/acpica/tbxface.c:222
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:acpi_blacklisted
```
**Symbols:**

```
ffffffff81528319-ffffffff815283d4: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff8157fd19)
Location: drivers/acpi/acpica/tbxface.c:250
Inline: True
```
**Symbols:**

```
ffffffff8157fd19-ffffffff8157fdd4: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815b6f10)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff815b6f10-ffffffff815b6fcb: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815d02cd)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff815d02cd-ffffffff815d0388: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81601b66)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff81601b66-ffffffff81601c22: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff8162300f)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff8162300f-ffffffff816230cb: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816cf723)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff816cf723-ffffffff816cf7c6: acpi_get_table_header.part.0 (STB_LOCAL)
ffffffff816cf7c6-ffffffff816cf7e6: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816ed723)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff816ed723-ffffffff816ed7c6: acpi_get_table_header.part.0 (STB_LOCAL)
ffffffff816ed7c6-ffffffff816ed7e6: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816cf5df)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff816cf5df-ffffffff816cf69b: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81746c4f)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff81746c4f-ffffffff81746d0b: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81878b0d)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_match_platform_list
```
**Symbols:**

```
ffffffff81878b0d-ffffffff81878bee: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff819bb090)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_match_platform_list
```
**Symbols:**

```
ffffffff819bb090-ffffffff819bb1ca: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81a02230)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_match_platform_list
```
**Symbols:**

```
ffffffff81a02230-ffffffff81a0236a: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81a4d0b0)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_match_platform_list
```
**Symbols:**

```
ffffffff81a4d0b0-ffffffff81a4d1ea: acpi_get_table_header (STB_GLOBAL)
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
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffff8000107984d4)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffff8000107984d4-ffff8000107985dc: acpi_get_table_header (STB_GLOBAL)
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
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815fcfb9)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff815fcfb9-ffffffff815fd075: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815e84df)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff815e84df-ffffffff815e859b: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816172ef)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff816172ef-ffffffff816173ab: acpi_get_table_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_header(char *signature, u32 instance, struct acpi_table_header *out_table_header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff8163119f)
Location: drivers/acpi/acpica/tbxface.c:216
Inline: True
```
**Symbols:**

```
ffffffff8163119f-ffffffff8163125b: acpi_get_table_header (STB_GLOBAL)
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
