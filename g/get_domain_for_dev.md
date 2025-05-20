# Function: <code>get_domain_for_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153a680)
Location: drivers/iommu/intel-iommu.c:2412
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:__get_valid_domain_for_dev
```
**Symbols:**

```
ffffffff8153a680-ffffffff8153aabc: get_domain_for_dev.constprop.57 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158f180)
Location: drivers/iommu/intel-iommu.c:2456
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:__get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff8158f180-ffffffff8158f5b9: get_domain_for_dev.constprop.59 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff8178615a)
Location: drivers/iommu/intel-iommu.c:2583
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
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
In drivers/iommu/intel-iommu.c (ffffffff815d351f)
Location: drivers/iommu/intel-iommu.c:2591
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
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
In drivers/iommu/intel-iommu.c (ffffffff8163a212)
Location: drivers/iommu/intel-iommu.c:2615
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
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
In drivers/iommu/intel-iommu.c (ffffffff81675844)
Location: drivers/iommu/intel-iommu.c:2671
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
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
In drivers/iommu/intel-iommu.c (ffffffff81693d45)
Location: drivers/iommu/intel-iommu.c:2668
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
</details>
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
