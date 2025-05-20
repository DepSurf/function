# Function: <code>dmar_hotplug_remove</code>

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
In drivers/iommu/dmar.c (ffffffff81533a2e)
Location: drivers/iommu/dmar.c:1933
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
In drivers/iommu/dmar.c (ffffffff815882c0)
Location: drivers/iommu/dmar.c:1954
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
In drivers/iommu/dmar.c (ffffffff815b5980)
Location: drivers/iommu/dmar.c:1955
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
In drivers/iommu/dmar.c (ffffffff815cb6ed)
Location: drivers/iommu/dmar.c:1963
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
In drivers/iommu/dmar.c (ffffffff816324bd)
Location: drivers/iommu/dmar.c:1967
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
In drivers/iommu/dmar.c (ffffffff8166d8ab)
Location: drivers/iommu/dmar.c:1965
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
In drivers/iommu/dmar.c (ffffffff8168bcbb)
Location: drivers/iommu/dmar.c:1996
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
In drivers/iommu/dmar.c (ffffffff816c36b6)
Location: drivers/iommu/dmar.c:1985
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
In drivers/iommu/dmar.c (ffffffff816e6606)
Location: drivers/iommu/dmar.c:2063
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_device_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dmar_hotplug_remove(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179caa0)
Location: drivers/iommu/intel/dmar.c:2179
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
```
**Symbols:**

```
ffffffff8179caa0-ffffffff8179cb40: dmar_hotplug_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dmar_hotplug_remove(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff817aa770)
Location: drivers/iommu/intel/dmar.c:2217
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
```
**Symbols:**

```
ffffffff817aa770-ffffffff817aa810: dmar_hotplug_remove (STB_LOCAL)
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
In drivers/iommu/intel/dmar.c (ffffffff8178dbf8)
Location: drivers/iommu/intel/dmar.c:2288
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
In drivers/iommu/intel/dmar.c (ffffffff81815488)
Location: drivers/iommu/intel/dmar.c:2324
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
In drivers/iommu/intel/dmar.c (ffffffff81955c04)
Location: drivers/iommu/intel/dmar.c:2325
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
In drivers/iommu/intel/dmar.c (ffffffff81abc793)
Location: drivers/iommu/intel/dmar.c:2314
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
In drivers/iommu/intel/dmar.c (ffffffff81b09083)
Location: drivers/iommu/intel/dmar.c:2337
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
In drivers/iommu/intel/dmar.c (ffffffff81b5d0a3)
Location: drivers/iommu/intel/dmar.c:2355
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
In drivers/iommu/dmar.c (ffffffff816ac0e6)
Location: drivers/iommu/dmar.c:2063
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
In drivers/iommu/dmar.c (ffffffff81689a46)
Location: drivers/iommu/dmar.c:2063
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
In drivers/iommu/dmar.c (ffffffff816da2c6)
Location: drivers/iommu/dmar.c:2063
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
In drivers/iommu/dmar.c (ffffffff816f4876)
Location: drivers/iommu/dmar.c:2063
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
