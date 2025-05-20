# Function: <code>get_iommu_domain</code>

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
In drivers/iommu/intel-iommu.c (ffffffff815364db)
Location: drivers/iommu/intel-iommu.c:615
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
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
In drivers/iommu/intel-iommu.c (ffffffff8158ba57)
Location: drivers/iommu/intel-iommu.c:622
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_notifier
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
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
In drivers/iommu/intel-iommu.c (ffffffff815b9195)
Location: drivers/iommu/intel-iommu.c:623
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
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
In drivers/iommu/intel-iommu.c (ffffffff815ce9f5)
Location: drivers/iommu/intel-iommu.c:628
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
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
In drivers/iommu/intel-iommu.c (ffffffff81635389)
Location: drivers/iommu/intel-iommu.c:601
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
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
In drivers/iommu/intel-iommu.c (ffffffff81670969)
Location: drivers/iommu/intel-iommu.c:603
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
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
In drivers/iommu/intel-iommu.c (ffffffff8168ed09)
Location: drivers/iommu/intel-iommu.c:479
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
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
In drivers/iommu/intel-iommu.c (ffffffff816c6239)
Location: drivers/iommu/intel-iommu.c:473
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
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
In drivers/iommu/intel-iommu.c (ffffffff816e9269)
Location: drivers/iommu/intel-iommu.c:484
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
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
In drivers/iommu/intel/iommu.c (ffffffff817a1429)
Location: drivers/iommu/intel/iommu.c:481
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_all_cpu_cached_iovas
  - drivers/iommu/intel/iommu.c:iommu_flush_iova
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
In drivers/iommu/intel/iommu.c (ffffffff817ae8b9)
Location: drivers/iommu/intel/iommu.c:471
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_all_cpu_cached_iovas
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
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
In drivers/iommu/intel/iommu.c (ffffffff81791573)
Location: drivers/iommu/intel/iommu.c:480
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
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
In drivers/iommu/intel/iommu.c (ffffffff81818b05)
Location: drivers/iommu/intel/iommu.c:469
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
```
</details>
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
In drivers/iommu/intel-iommu.c (ffffffff816aed49)
Location: drivers/iommu/intel-iommu.c:484
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
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
In drivers/iommu/intel-iommu.c (ffffffff8168c6a9)
Location: drivers/iommu/intel-iommu.c:484
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
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
In drivers/iommu/intel-iommu.c (ffffffff816dcf29)
Location: drivers/iommu/intel-iommu.c:484
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
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
In drivers/iommu/intel-iommu.c (ffffffff816f7569)
Location: drivers/iommu/intel-iommu.c:484
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
```
</details>
</li>
</ul>

## Differences
