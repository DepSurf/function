# Function: <code>is_aux_domain</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c7d4c)
Location: drivers/iommu/intel-iommu.c:4945
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
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
In drivers/iommu/intel-iommu.c (ffffffff816eacfc)
Location: drivers/iommu/intel-iommu.c:5229
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
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
In drivers/iommu/intel/iommu.c (ffffffff817a2e65)
Location: drivers/iommu/intel/iommu.c:5114
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
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
In drivers/iommu/intel/iommu.c (ffffffff817b2d20)
Location: drivers/iommu/intel/iommu.c:4491
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:aux_domain_remove_dev
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
In drivers/iommu/intel/iommu.c (ffffffff81793375)
Location: drivers/iommu/intel/iommu.c:4589
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
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
In drivers/iommu/intel/iommu.c (ffffffff8181b195)
Location: drivers/iommu/intel/iommu.c:4574
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
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
In drivers/iommu/intel-iommu.c (ffffffff816b07dc)
Location: drivers/iommu/intel-iommu.c:5229
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
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
In drivers/iommu/intel-iommu.c (ffffffff8168e12c)
Location: drivers/iommu/intel-iommu.c:5229
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
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
In drivers/iommu/intel-iommu.c (ffffffff816de9bc)
Location: drivers/iommu/intel-iommu.c:5229
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
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
In drivers/iommu/intel-iommu.c (ffffffff816f89ec)
Location: drivers/iommu/intel-iommu.c:5229
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
```
</details>
</li>
</ul>

## Differences
