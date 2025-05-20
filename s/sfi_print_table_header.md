# Function: <code>sfi_print_table_header</code>

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
In drivers/sfi/sfi_core.c (ffffffff8181afec)
Location: drivers/sfi/sfi_core.c:120
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
In drivers/sfi/sfi_core.c (ffffffff8189515c)
Location: drivers/sfi/sfi_core.c:120
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
In drivers/sfi/sfi_core.c (ffffffff818c98ac)
Location: drivers/sfi/sfi_core.c:120
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
In drivers/sfi/sfi_core.c (ffffffff81900e78)
Location: drivers/sfi/sfi_core.c:120
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
In drivers/sfi/sfi_core.c (ffffffff8198ae88)
Location: drivers/sfi/sfi_core.c:121
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
In drivers/sfi/sfi_core.c (ffffffff819e77a8)
Location: drivers/sfi/sfi_core.c:121
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
In drivers/sfi/sfi_core.c (ffffffff81a22c18)
Location: drivers/sfi/sfi_core.c:121
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
In drivers/sfi/sfi_core.c (ffffffff81a92ce9)
Location: drivers/sfi/sfi_core.c:121
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
In drivers/sfi/sfi_core.c (ffffffff81aca4b9)
Location: drivers/sfi/sfi_core.c:121
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sfi_print_table_header(long long unsigned int pa, struct sfi_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff816f45b0)
Location: drivers/sfi/sfi_core.c:121
Inline: False
Direct callers:
  - drivers/sfi/sfi_core.c:sfi_find_syst
  - drivers/sfi/sfi_core.c:sfi_check_table
```
**Symbols:**

```
ffffffff816f45b0-ffffffff816f45dc: sfi_print_table_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sfi_print_table_header(long long unsigned int pa, struct sfi_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81c0391c)
Location: drivers/sfi/sfi_core.c:121
Inline: False
Direct callers:
  - drivers/sfi/sfi_core.c:sfi_find_syst
  - drivers/sfi/sfi_core.c:sfi_check_table
```
**Symbols:**

```
ffffffff81c0391c-ffffffff81c03948: sfi_print_table_header (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81a69329)
Location: drivers/sfi/sfi_core.c:121
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/sfi/sfi_core.c (ffffffff81a25de9)
Location: drivers/sfi/sfi_core.c:121
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
In drivers/sfi/sfi_core.c (ffffffff81ad5739)
Location: drivers/sfi/sfi_core.c:121
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
In drivers/sfi/sfi_core.c (ffffffff81ae1bf9)
Location: drivers/sfi/sfi_core.c:121
Inline: True
Inline callers:
  - drivers/sfi/sfi_core.c:sfi_check_table
  - drivers/sfi/sfi_core.c:sfi_init
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
</ul>
