# Function: <code>iommu_flush_tlb_all</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8153245f)
Location: drivers/iommu/amd_iommu.c:938
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
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
In drivers/iommu/amd_iommu.c (ffffffff81586c36)
Location: drivers/iommu/amd_iommu.c:1034
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
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
In drivers/iommu/amd_iommu.c (ffffffff815b4223)
Location: drivers/iommu/amd_iommu.c:1123
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
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
In drivers/iommu/amd_iommu.c (ffffffff815c9f87)
Location: drivers/iommu/amd_iommu.c:1182
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
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
In drivers/iommu/iommu.c (ffffffff81626f8d)
Location: include/linux/iommu.h:362
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
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
In drivers/iommu/iommu.c (ffffffff81661b2c)
Location: include/linux/iommu.h:362
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
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
In drivers/iommu/iommu.c (ffffffff816801ec)
Location: include/linux/iommu.h:353
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
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
In drivers/iommu/iommu.c (ffffffff816b767f)
Location: include/linux/iommu.h:473
Inline: True
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
In drivers/iommu/iommu.c (ffffffff816da22f)
Location: include/linux/iommu.h:499
Inline: True
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
In drivers/iommu/iommu.c (ffffffff8178fce7)
Location: include/linux/iommu.h:539
Inline: True
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/iommu/iommu.c (ffff8000108c645c)
Location: include/linux/iommu.h:499
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bccc0)
Location: include/linux/iommu.h:499
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_create_direct_mappings
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096bc74)
Location: include/linux/iommu.h:499
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_create_direct_mappings
```
</details>
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
In drivers/iommu/iommu.c (ffffffff8169fc7f)
Location: include/linux/iommu.h:499
Inline: True
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
In drivers/iommu/iommu.c (ffffffff8167d66f)
Location: include/linux/iommu.h:499
Inline: True
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
In drivers/iommu/iommu.c (ffffffff816cdeef)
Location: include/linux/iommu.h:499
Inline: True
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
In drivers/iommu/iommu.c (ffffffff816e842f)
Location: include/linux/iommu.h:499
Inline: True
```
</details>
</li>
</ul>

## Differences
