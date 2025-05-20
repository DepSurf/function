# Function: <code>find_or_alloc_domain</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bb5a0)
Location: drivers/iommu/intel-iommu.c:2498
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:__get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff815bb5a0-ffffffff815bb909: find_or_alloc_domain.constprop.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d1200)
Location: drivers/iommu/intel-iommu.c:2506
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff815d1200-ffffffff815d1540: find_or_alloc_domain.constprop.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81637fb0)
Location: drivers/iommu/intel-iommu.c:2530
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff81637fb0-ffffffff81638307: find_or_alloc_domain.constprop.68 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816732f0)
Location: drivers/iommu/intel-iommu.c:2588
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff816732f0-ffffffff81673621: find_or_alloc_domain.constprop.74 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81690d50)
Location: drivers/iommu/intel-iommu.c:2585
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff81690d50-ffffffff81691040: find_or_alloc_domain.constprop.79 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816cac20)
Location: drivers/iommu/intel-iommu.c:2575
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
In drivers/iommu/intel-iommu.c (ffffffff816ee390)
Location: drivers/iommu/intel-iommu.c:2586
Inline: True
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b3b00)
Location: drivers/iommu/intel-iommu.c:2586
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
In drivers/iommu/intel-iommu.c (ffffffff816917c0)
Location: drivers/iommu/intel-iommu.c:2586
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
In drivers/iommu/intel-iommu.c (ffffffff816e2050)
Location: drivers/iommu/intel-iommu.c:2586
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
In drivers/iommu/intel-iommu.c (ffffffff816fc6b0)
Location: drivers/iommu/intel-iommu.c:2586
Inline: True
```
</details>
</li>
</ul>

## Differences
