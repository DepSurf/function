# Function: <code>cper_print_pcie</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff816d3fd2)
Location: drivers/firmware/efi/cper.c:353
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81737992)
Location: drivers/firmware/efi/cper.c:353
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff8176ab32)
Location: drivers/firmware/efi/cper.c:353
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81788f76)
Location: drivers/firmware/efi/cper.c:476
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff817ff40e)
Location: drivers/firmware/efi/cper.c:476
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818490a7)
Location: drivers/firmware/efi/cper.c:358
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81875317)
Location: drivers/firmware/efi/cper.c:371
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818b9522)
Location: drivers/firmware/efi/cper.c:359
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818ebf37)
Location: drivers/firmware/efi/cper.c:359
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cper_print_pcie(const char *pfx, const struct cper_sec_pcie *pcie, const struct acpi_hest_generic_data *gdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff819bf048)
Location: drivers/firmware/efi/cper.c:359
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff819bf048-ffffffff819bf1e7: cper_print_pcie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cper_print_pcie(const char *pfx, const struct cper_sec_pcie *pcie, const struct acpi_hest_generic_data *gdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81c2bde0)
Location: drivers/firmware/efi/cper.c:373
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81c2bde0-ffffffff81c2bf7f: cper_print_pcie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cper_print_pcie(const char *pfx, const struct cper_sec_pcie *pcie, const struct acpi_hest_generic_data *gdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81c1e13c)
Location: drivers/firmware/efi/cper.c:371
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81c1e13c-ffffffff81c1e2db: cper_print_pcie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cper_print_pcie(const char *pfx, const struct cper_sec_pcie *pcie, const struct acpi_hest_generic_data *gdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81d2f624)
Location: drivers/firmware/efi/cper.c:370
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81d2f624-ffffffff81d2f7e2: cper_print_pcie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cper_print_pcie(const char *pfx, const struct cper_sec_pcie *pcie, const struct acpi_hest_generic_data *gdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81efb8e1)
Location: drivers/firmware/efi/cper.c:398
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81efb8e1-ffffffff81efbab3: cper_print_pcie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cper_print_pcie(const char *pfx, const struct cper_sec_pcie *pcie, const struct acpi_hest_generic_data *gdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81d64660)
Location: drivers/firmware/efi/cper.c:402
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81d64660-ffffffff81d64890: cper_print_pcie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cper_print_pcie(const char *pfx, const struct cper_sec_pcie *pcie, const struct acpi_hest_generic_data *gdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81dcf790)
Location: drivers/firmware/efi/cper.c:402
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81dcf790-ffffffff81dcf9c0: cper_print_pcie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cper_print_pcie(const char *pfx, const struct cper_sec_pcie *pcie, const struct acpi_hest_generic_data *gdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81e884c0)
Location: drivers/firmware/efi/cper.c:402
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81e884c0-ffffffff81e886f0: cper_print_pcie (STB_LOCAL)
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
In drivers/firmware/efi/cper.c (ffff800010b5f278)
Location: drivers/firmware/efi/cper.c:359
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81846637)
Location: drivers/firmware/efi/cper.c:359
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818e0d97)
Location: drivers/firmware/efi/cper.c:359
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818fd837)
Location: drivers/firmware/efi/cper.c:359
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
