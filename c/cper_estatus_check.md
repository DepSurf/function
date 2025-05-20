# Function: <code>cper_estatus_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff816d3790)
Location: drivers/firmware/efi/cper.c:478
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff816d3790-ffffffff816d381f: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81737150)
Location: drivers/firmware/efi/cper.c:478
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff81737150-ffffffff817371df: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff8176a2f0)
Location: drivers/firmware/efi/cper.c:478
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff8176a2f0-ffffffff8176a37f: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff817886a0)
Location: drivers/firmware/efi/cper.c:646
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff817886a0-ffffffff8178870f: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff817feb40)
Location: drivers/firmware/efi/cper.c:641
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff817feb40-ffffffff817febc4: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81848340)
Location: drivers/firmware/efi/cper.c:533
Inline: False
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff81848340-ffffffff818483c8: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81874590)
Location: drivers/firmware/efi/cper.c:546
Inline: False
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81874590-ffffffff81874618: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818b8800)
Location: drivers/firmware/efi/cper.c:534
Inline: False
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff818b8800-ffffffff818b887f: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818eb200)
Location: drivers/firmware/efi/cper.c:549
Inline: False
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff818eb200-ffffffff818eb27f: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff819bed80)
Location: drivers/firmware/efi/cper.c:611
Inline: True
Direct callers:
  - drivers/acpi/apei/bert.c:bert_print_all
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff819bed80-ffffffff819bedff: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff819c07f0)
Location: drivers/firmware/efi/cper.c:625
Inline: True
Direct callers:
  - drivers/acpi/apei/bert.c:bert_print_all
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff819c07f0-ffffffff819c086f: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff819a4ef0)
Location: drivers/firmware/efi/cper.c:623
Inline: True
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff819a4ef0-ffffffff819a4f6c: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81a52160)
Location: drivers/firmware/efi/cper.c:622
Inline: True
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a52160-ffffffff81a521dc: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81bc0d60)
Location: drivers/firmware/efi/cper.c:650
Inline: True
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81bc0d60-ffffffff81bc0e0c: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81d64d10)
Location: drivers/firmware/efi/cper.c:662
Inline: True
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81d64d10-ffffffff81d64dbc: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81dcfe40)
Location: drivers/firmware/efi/cper.c:662
Inline: True
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81dcfe40-ffffffff81dcfeec: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81e88b70)
Location: drivers/firmware/efi/cper.c:681
Inline: True
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81e88b70-ffffffff81e88c1c: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffff800010b5e438)
Location: drivers/firmware/efi/cper.c:549
Inline: False
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffff800010b5e438-ffff800010b5e4f8: cper_estatus_check (STB_GLOBAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81845900)
Location: drivers/firmware/efi/cper.c:549
Inline: False
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
```
**Symbols:**

```
ffffffff81845900-ffffffff8184597f: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818e0060)
Location: drivers/firmware/efi/cper.c:549
Inline: False
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff818e0060-ffffffff818e00df: cper_estatus_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cper_estatus_check(const struct acpi_hest_generic_status *estatus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818fcb00)
Location: drivers/firmware/efi/cper.c:549
Inline: False
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff818fcb00-ffffffff818fcb7f: cper_estatus_check (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
