# Function: <code>xgene_8250_erratum_present</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/spcr.c (ffffffff82721e49)
Location: drivers/acpi/spcr.c:54
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
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
In drivers/acpi/spcr.c (ffffffff828d9f65)
Location: drivers/acpi/spcr.c:54
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
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
In drivers/acpi/spcr.c (ffffffff828f4847)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
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
In drivers/acpi/spcr.c (ffffffff828fd89e)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/spcr.c (ffffffff82d147dc)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/spcr.c (ffffffff8300245d)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/spcr.c (ffffffff8320d4fc)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/spcr.c (ffffffff832f5d36)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/spcr.c (ffffffff834ae18c)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool xgene_8250_erratum_present(struct acpi_table_spcr *tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/spcr.c (ffffffff819e2190)
Location: drivers/acpi/spcr.c:50
Inline: False
Direct callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
```
**Symbols:**

```
ffffffff819e2190-ffffffff819e2217: xgene_8250_erratum_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool xgene_8250_erratum_present(struct acpi_table_spcr *tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/spcr.c (ffffffff81a2a790)
Location: drivers/acpi/spcr.c:50
Inline: False
Direct callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
```
**Symbols:**

```
ffffffff81a2a790-ffffffff81a2a817: xgene_8250_erratum_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool xgene_8250_erratum_present(struct acpi_table_spcr *tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/spcr.c (ffffffff81a75960)
Location: drivers/acpi/spcr.c:50
Inline: False
Direct callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
```
**Symbols:**

```
ffffffff81a75960-ffffffff81a759e7: xgene_8250_erratum_present (STB_LOCAL)
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
In drivers/acpi/spcr.c (ffff8000114806a4)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/spcr.c (ffffffff828e5af6)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
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
In drivers/acpi/spcr.c (ffffffff828ddcd1)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
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
In drivers/acpi/spcr.c (ffffffff828f8bc1)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
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
In drivers/acpi/spcr.c (ffffffff828fe8f2)
Location: drivers/acpi/spcr.c:50
Inline: True
Inline callers:
  - drivers/acpi/spcr.c:acpi_parse_spcr
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
