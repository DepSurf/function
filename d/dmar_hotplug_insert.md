# Function: <code>dmar_hotplug_insert</code>

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
In drivers/iommu/dmar.c (ffffffff8153393f)
Location: drivers/iommu/dmar.c:1887
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff815881d1)
Location: drivers/iommu/dmar.c:1908
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff815b5891)
Location: drivers/iommu/dmar.c:1909
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff815cb71e)
Location: drivers/iommu/dmar.c:1917
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff816324ee)
Location: drivers/iommu/dmar.c:1921
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff8166d790)
Location: drivers/iommu/dmar.c:1919
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff8168bba0)
Location: drivers/iommu/dmar.c:1950
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff816c3590)
Location: drivers/iommu/dmar.c:1939
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff816e64e0)
Location: drivers/iommu/dmar.c:2017
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dmar_hotplug_insert(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:2133
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
```
**Symbols:**

```
ffffffff8179c960-ffffffff8179ca9f: dmar_hotplug_insert (STB_LOCAL)
ffffffff8179ec8d-ffffffff8179ec9e: dmar_hotplug_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dmar_hotplug_insert(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:2171
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
```
**Symbols:**

```
ffffffff817aa630-ffffffff817aa76f: dmar_hotplug_insert (STB_LOCAL)
ffffffff81c0c0b8-ffffffff81c0c0c9: dmar_hotplug_insert.cold (STB_LOCAL)
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
In drivers/iommu/intel/dmar.c (ffffffff8178dc69)
Location: drivers/iommu/intel/dmar.c:2242
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
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
In drivers/iommu/intel/dmar.c (ffffffff818154f9)
Location: drivers/iommu/intel/dmar.c:2278
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
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
In drivers/iommu/intel/dmar.c (ffffffff81955b6e)
Location: drivers/iommu/intel/dmar.c:2279
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abc68e)
Location: drivers/iommu/intel/dmar.c:2268
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b08f7e)
Location: drivers/iommu/intel/dmar.c:2291
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5cf9e)
Location: drivers/iommu/intel/dmar.c:2309
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816abfc0)
Location: drivers/iommu/dmar.c:2017
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff81689920)
Location: drivers/iommu/dmar.c:2017
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff816da1a0)
Location: drivers/iommu/dmar.c:2017
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
In drivers/iommu/dmar.c (ffffffff816f4750)
Location: drivers/iommu/dmar.c:2017
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
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
