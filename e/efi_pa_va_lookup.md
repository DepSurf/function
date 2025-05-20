# Function: <code>efi_pa_va_lookup</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 efi_pa_va_lookup(u64 pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81cf0fa4)
Location: drivers/acpi/prmt.c:77
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
**Symbols:**

```
ffffffff81cf0fa4-ffffffff81cf0ffb: efi_pa_va_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 efi_pa_va_lookup(u64 pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81eb8e59)
Location: drivers/acpi/prmt.c:75
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
**Symbols:**

```
ffffffff81eb8e59-ffffffff81eb8ec2: efi_pa_va_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 efi_pa_va_lookup(u64 pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81979ca0)
Location: drivers/acpi/prmt.c:75
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
**Symbols:**

```
ffffffff81979ca0-ffffffff81979d22: efi_pa_va_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 efi_pa_va_lookup(u64 pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff819c0730)
Location: drivers/acpi/prmt.c:75
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
**Symbols:**

```
ffffffff819c0730-ffffffff819c07b2: efi_pa_va_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 efi_pa_va_lookup(u64 pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff81a0b1b0)
Location: drivers/acpi/prmt.c:75
Inline: False
Direct callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
**Symbols:**

```
ffffffff81a0b1b0-ffffffff81a0b232: efi_pa_va_lookup (STB_LOCAL)
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
