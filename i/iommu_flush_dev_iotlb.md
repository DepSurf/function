# Function: <code>iommu_flush_dev_iotlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_flush_dev_iotlb(struct dmar_domain *domain, u64 addr, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81536390)
Location: drivers/iommu/intel-iommu.c:1513
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel-iommu.c:flush_unmaps
```
**Symbols:**

```
ffffffff81536390-ffffffff8153641e: iommu_flush_dev_iotlb (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff8158b8f6)
Location: drivers/iommu/intel-iommu.c:1549
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff8158b690-ffffffff8158b724: iommu_flush_dev_iotlb.part.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b9047)
Location: drivers/iommu/intel-iommu.c:1563
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff815b8de0-ffffffff815b8e74: iommu_flush_dev_iotlb.part.49 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff815ce8cd)
Location: drivers/iommu/intel-iommu.c:1568
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:flush_unmaps_timeout
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff815ce670-ffffffff815ce6f6: iommu_flush_dev_iotlb.part.44 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff81635793)
Location: drivers/iommu/intel-iommu.c:1551
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff81635550-ffffffff816355d6: iommu_flush_dev_iotlb.part.45 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff81670d22)
Location: drivers/iommu/intel-iommu.c:1567
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff81670b00-ffffffff81670b8a: iommu_flush_dev_iotlb.part.54 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff8168f622)
Location: drivers/iommu/intel-iommu.c:1444
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff8168f400-ffffffff8168f48a: iommu_flush_dev_iotlb.part.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c6fd2)
Location: drivers/iommu/intel-iommu.c:1452
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff816c6eb0-ffffffff816c6f3a: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ea032)
Location: drivers/iommu/intel-iommu.c:1463
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff816e9e10-ffffffff816e9e9a: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a136f)
Location: drivers/iommu/intel/iommu.c:1478
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iova
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel/iommu.c:iommu_flush_iova
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff817a08e0-ffffffff817a0963: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817aedcf)
Location: drivers/iommu/intel/iommu.c:1580
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff817aeb30-ffffffff817aec36: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81791593)
Location: drivers/iommu/intel/iommu.c:1604
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff817912f0-ffffffff817913f6: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81818b25)
Location: drivers/iommu/intel/iommu.c:1608
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff818187b0-ffffffff818188b6: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81959bbb)
Location: drivers/iommu/intel/iommu.c:1526
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff81959570-ffffffff8195960c: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac1317)
Location: drivers/iommu/intel/iommu.c:1494
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff81ac0e80-ffffffff81ac0f5e: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0dba7)
Location: drivers/iommu/intel/iommu.c:1464
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff81b0d6f0-ffffffff81b0d7ce: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b62528)
Location: drivers/iommu/intel/iommu.c:1333
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff81b62080-ffffffff81b621b6: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816afb12)
Location: drivers/iommu/intel-iommu.c:1463
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff816af8f0-ffffffff816af97a: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168d462)
Location: drivers/iommu/intel-iommu.c:1463
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff8168d240-ffffffff8168d2ca: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ddcf2)
Location: drivers/iommu/intel-iommu.c:1463
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff816ddad0-ffffffff816ddb5a: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f82f2)
Location: drivers/iommu/intel-iommu.c:1463
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_iova
  - drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi
```
**Symbols:**

```
ffffffff816f80d0-ffffffff816f815a: iommu_flush_dev_iotlb.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
