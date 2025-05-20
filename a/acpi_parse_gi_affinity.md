# Function: <code>acpi_parse_gi_affinity</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_parse_gi_affinity(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8300116e)
Location: drivers/acpi/numa/srat.c:372
Inline: False
```
**Symbols:**

```
ffffffff8300116e-ffffffff830011e4: acpi_parse_gi_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_parse_gi_affinity(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8320c25e)
Location: drivers/acpi/numa/srat.c:372
Inline: False
```
**Symbols:**

```
ffffffff8320c25e-ffffffff8320c2d4: acpi_parse_gi_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_parse_gi_affinity(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff832f49d8)
Location: drivers/acpi/numa/srat.c:372
Inline: False
```
**Symbols:**

```
ffffffff832f49d8-ffffffff832f4a4e: acpi_parse_gi_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_parse_gi_affinity(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff834acd2c)
Location: drivers/acpi/numa/srat.c:412
Inline: False
```
**Symbols:**

```
ffffffff834acd2c-ffffffff834acd9d: acpi_parse_gi_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_parse_gi_affinity(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff83ee58e0)
Location: drivers/acpi/numa/srat.c:413
Inline: False
```
**Symbols:**

```
ffffffff83ee58e0-ffffffff83ee5952: acpi_parse_gi_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_parse_gi_affinity(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8370b2b0)
Location: drivers/acpi/numa/srat.c:413
Inline: False
```
**Symbols:**

```
ffffffff8370b2b0-ffffffff8370b322: acpi_parse_gi_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_parse_gi_affinity(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8393e750)
Location: drivers/acpi/numa/srat.c:418
Inline: False
```
**Symbols:**

```
ffffffff8393e750-ffffffff8393e7bb: acpi_parse_gi_affinity (STB_LOCAL)
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
