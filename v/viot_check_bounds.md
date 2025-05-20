# Function: <code>viot_check_bounds</code>

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
int viot_check_bounds(const struct acpi_viot_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff832f6a18)
Location: drivers/acpi/viot.c:58
Inline: False
Direct callers:
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/acpi/viot.c:acpi_viot_init
```
**Symbols:**

```
ffffffff832f6a18-ffffffff832f6a7e: viot_check_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int viot_check_bounds(const struct acpi_viot_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff834aef67)
Location: drivers/acpi/viot.c:58
Inline: False
Direct callers:
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/acpi/viot.c:acpi_viot_init
```
**Symbols:**

```
ffffffff834aef67-ffffffff834aefd7: viot_check_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int viot_check_bounds(const struct acpi_viot_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff83ee8500)
Location: drivers/acpi/viot.c:57
Inline: False
Direct callers:
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/acpi/viot.c:acpi_viot_init
```
**Symbols:**

```
ffffffff83ee8500-ffffffff83ee8586: viot_check_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int viot_check_bounds(const struct acpi_viot_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff8370dec0)
Location: drivers/acpi/viot.c:57
Inline: False
Direct callers:
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/acpi/viot.c:acpi_viot_init
```
**Symbols:**

```
ffffffff8370dec0-ffffffff8370df46: viot_check_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int viot_check_bounds(const struct acpi_viot_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff839415a0)
Location: drivers/acpi/viot.c:57
Inline: False
Direct callers:
  - drivers/acpi/viot.c:viot_parse_node
  - drivers/acpi/viot.c:viot_get_iommu
```
**Symbols:**

```
ffffffff839415a0-ffffffff83941626: viot_check_bounds (STB_LOCAL)
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
