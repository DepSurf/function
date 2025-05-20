# Function: <code>iommu_set_cmd_line_dma_api</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff829036b9)
Location: drivers/iommu/iommu.c:71
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
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
In drivers/iommu/iommu.c (ffffffff82d1a55a)
Location: drivers/iommu/iommu.c:73
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
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
In drivers/iommu/iommu.c (ffffffff8300c37c)
Location: drivers/iommu/iommu.c:73
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
```
</details>
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
In drivers/iommu/iommu.c (ffff800011496558)
Location: drivers/iommu/iommu.c:71
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
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
In drivers/iommu/iommu.c (c15970fc)
Location: drivers/iommu/iommu.c:71
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
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
In drivers/iommu/iommu.c (c0000000013a99fc)
Location: drivers/iommu/iommu.c:71
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
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
In drivers/iommu/iommu.c (ffffffff828eaea0)
Location: drivers/iommu/iommu.c:71
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
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
In drivers/iommu/iommu.c (ffffffff828e232d)
Location: drivers/iommu/iommu.c:71
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
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
In drivers/iommu/iommu.c (ffffffff828fe9dc)
Location: drivers/iommu/iommu.c:71
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
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
In drivers/iommu/iommu.c (ffffffff8290471b)
Location: drivers/iommu/iommu.c:71
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
```
</details>
</li>
</ul>

## Differences
