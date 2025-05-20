# Function: <code>viot_get_iommu</code>

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
struct viot_iommu *viot_get_iommu(unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff832f6a7e)
Location: drivers/acpi/viot.c:128
Inline: False
Direct callers:
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_init
```
**Symbols:**

```
ffffffff832f6a7e-ffffffff832f6c7b: viot_get_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct viot_iommu *viot_get_iommu(unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff834aefd7)
Location: drivers/acpi/viot.c:128
Inline: False
Direct callers:
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_init
```
**Symbols:**

```
ffffffff834aefd7-ffffffff834af1e4: viot_get_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct viot_iommu *viot_get_iommu(unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff83ee85a0)
Location: drivers/acpi/viot.c:127
Inline: False
Direct callers:
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_init
```
**Symbols:**

```
ffffffff83ee85a0-ffffffff83ee87b0: viot_get_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct viot_iommu *viot_get_iommu(unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff8370df60)
Location: drivers/acpi/viot.c:127
Inline: False
Direct callers:
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/acpi/viot.c:acpi_viot_init
```
**Symbols:**

```
ffffffff8370df60-ffffffff8370e16c: viot_get_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct viot_iommu *viot_get_iommu(unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff83941640)
Location: drivers/acpi/viot.c:127
Inline: False
Direct callers:
  - drivers/acpi/viot.c:viot_parse_node
  - drivers/acpi/viot.c:viot_parse_node
```
**Symbols:**

```
ffffffff83941640-ffffffff839418ad: viot_get_iommu (STB_LOCAL)
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
