# Function: <code>fpdt_process_subtable</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_fpdt.c (ffffffff81bf3f31)
Location: drivers/acpi/acpi_fpdt.c:146
Inline: True
Direct callers:
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
```
**Symbols:**

```
ffffffff81bf3f31-ffffffff81bf411e: fpdt_process_subtable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_fpdt.c (ffffffff81cf0cea)
Location: drivers/acpi/acpi_fpdt.c:146
Inline: True
Direct callers:
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
```
**Symbols:**

```
ffffffff81cf0cea-ffffffff81cf0ec1: fpdt_process_subtable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_fpdt.c (ffffffff81eb8b85)
Location: drivers/acpi/acpi_fpdt.c:146
Inline: True
Direct callers:
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
```
**Symbols:**

```
ffffffff81eb8b85-ffffffff81eb8d6c: fpdt_process_subtable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_fpdt.c (0)
Location: drivers/acpi/acpi_fpdt.c:163
Inline: True
Direct callers:
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
```
**Symbols:**

```
ffffffff819793e0-ffffffff8197965d: fpdt_process_subtable.isra.0 (STB_LOCAL)
ffffffff82091daa-ffffffff82091dc8: fpdt_process_subtable.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_fpdt.c (0)
Location: drivers/acpi/acpi_fpdt.c:163
Inline: True
Direct callers:
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
```
**Symbols:**

```
ffffffff819bfe80-ffffffff819c00d7: fpdt_process_subtable.isra.0 (STB_LOCAL)
ffffffff8211269b-ffffffff821126b2: fpdt_process_subtable.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fpdt_process_subtable(u64 address, u32 subtable_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_fpdt.c (0)
Location: drivers/acpi/acpi_fpdt.c:163
Inline: False
Direct callers:
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
```
**Symbols:**

```
ffffffff81a0a880-ffffffff81a0ab59: fpdt_process_subtable (STB_LOCAL)
ffffffff821f0403-ffffffff821f041a: fpdt_process_subtable.cold (STB_LOCAL)
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
</ul>
