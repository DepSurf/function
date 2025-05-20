# Function: <code>acpi_parse_prmt</code>

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
int acpi_parse_prmt(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff832f336f)
Location: drivers/acpi/prmt.c:96
Inline: False
```
**Symbols:**

```
ffffffff832f336f-ffffffff832f34ed: acpi_parse_prmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_parse_prmt(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff834ab498)
Location: drivers/acpi/prmt.c:93
Inline: False
```
**Symbols:**

```
ffffffff834ab498-ffffffff834ab666: acpi_parse_prmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_parse_prmt(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff83ee3980)
Location: drivers/acpi/prmt.c:93
Inline: False
```
**Symbols:**

```
ffffffff83ee3980-ffffffff83ee3b5b: acpi_parse_prmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_parse_prmt(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff83709370)
Location: drivers/acpi/prmt.c:93
Inline: False
```
**Symbols:**

```
ffffffff83709370-ffffffff8370953f: acpi_parse_prmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_parse_prmt(union acpi_subtable_headers *header, const long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/prmt.c (ffffffff8393c7d0)
Location: drivers/acpi/prmt.c:93
Inline: False
```
**Symbols:**

```
ffffffff8393c7d0-ffffffff8393c9ce: acpi_parse_prmt (STB_LOCAL)
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
