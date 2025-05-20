# Function: <code>sfi_check_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff8181af60)
Location: drivers/sfi/sfi_core.c:231
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
  - drivers/sfi/sfi_core.c:sfi_get_table
```
**Symbols:**

```
ffffffff8181af60-ffffffff8181b03e: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff818950d0)
Location: drivers/sfi/sfi_core.c:231
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff818950d0-ffffffff818951b1: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff818c9820)
Location: drivers/sfi/sfi_core.c:231
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff818c9820-ffffffff818c9901: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81900df0)
Location: drivers/sfi/sfi_core.c:231
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff81900df0-ffffffff81900ecb: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff8198ae00)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff8198ae00-ffffffff8198aedb: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff819e7720)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff819e7720-ffffffff819e77fd: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81a22b90)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff81a22b90-ffffffff81a22c6d: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81a92c50)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff81a92c50-ffffffff81a92d3e: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81aca420)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff81aca420-ffffffff81aca50e: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81bc2960)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff81bc2960-ffffffff81bc2a24: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81c3b9b0)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff81c3b9b0-ffffffff81c3ba74: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81a69290)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff81a69290-ffffffff81a6937e: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81a25d50)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff81a25d50-ffffffff81a25e3e: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81ad56a0)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff81ad56a0-ffffffff81ad578e: sfi_check_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sfi_table_header *sfi_check_table(u64 pa, struct sfi_table_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81ae1b60)
Location: drivers/sfi/sfi_core.c:232
Inline: False
Direct callers:
  - drivers/sfi/sfi_acpi.c:sfi_acpi_get_table
  - drivers/sfi/sfi_acpi.c:sfi_acpi_parse_xsdt
  - drivers/sfi/sfi_core.c:sfi_get_table
  - drivers/sfi/sfi_core.c:sfi_init
```
**Symbols:**

```
ffffffff81ae1b60-ffffffff81ae1c4e: sfi_check_table (STB_GLOBAL)
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
