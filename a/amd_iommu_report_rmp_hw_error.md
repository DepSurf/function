# Function: <code>amd_iommu_report_rmp_hw_error</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void amd_iommu_report_rmp_hw_error(volatile u32 *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:487
Inline: False
```
**Symbols:**

```
ffffffff817a38f0-ffffffff817a39cb: amd_iommu_report_rmp_hw_error (STB_LOCAL)
ffffffff81c0b482-ffffffff81c0b4fe: amd_iommu_report_rmp_hw_error.cold (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff81786ab1)
Location: drivers/iommu/amd/iommu.c:411
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff8180db6d)
Location: drivers/iommu/amd/iommu.c:411
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff8194e43b)
Location: drivers/iommu/amd/iommu.c:412
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff81ab2bce)
Location: drivers/iommu/amd/iommu.c:471
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_print_event
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
In drivers/iommu/amd/iommu.c (ffffffff81aff64f)
Location: drivers/iommu/amd/iommu.c:471
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_print_event
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
In drivers/iommu/amd/iommu.c (ffffffff81b52a3f)
Location: drivers/iommu/amd/iommu.c:589
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_print_event
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
