# Function: <code>get_private_domain_for_dev</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816cb17e)
Location: drivers/iommu/intel-iommu.c:3400
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816cabf0-ffffffff816cb051: get_private_domain_for_dev.part.0 (STB_LOCAL)
ffffffff816cc503-ffffffff816cc64d: get_private_domain_for_dev.part.0.cold (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816ee923)
Location: drivers/iommu/intel-iommu.c:3412
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816ee360-ffffffff816ee7c1: get_private_domain_for_dev.part.0 (STB_LOCAL)
ffffffff816efd4e-ffffffff816efe98: get_private_domain_for_dev.part.0.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b4093)
Location: drivers/iommu/intel-iommu.c:3412
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816b3ad0-ffffffff816b3f31: get_private_domain_for_dev.part.0 (STB_LOCAL)
ffffffff816b5534-ffffffff816b567e: get_private_domain_for_dev.part.0.cold (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff81691d53)
Location: drivers/iommu/intel-iommu.c:3412
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff81691790-ffffffff81691bf1: get_private_domain_for_dev.part.0 (STB_LOCAL)
ffffffff8169317e-ffffffff816932c8: get_private_domain_for_dev.part.0.cold (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816e25e3)
Location: drivers/iommu/intel-iommu.c:3412
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816e2020-ffffffff816e2481: get_private_domain_for_dev.part.0 (STB_LOCAL)
ffffffff816e3a0e-ffffffff816e3b58: get_private_domain_for_dev.part.0.cold (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816fcc43)
Location: drivers/iommu/intel-iommu.c:3412
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816fc680-ffffffff816fcaeb: get_private_domain_for_dev.part.0 (STB_LOCAL)
ffffffff816fe0ba-ffffffff816fe204: get_private_domain_for_dev.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
