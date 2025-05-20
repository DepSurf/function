# Function: <code>dev_iommu_priv_set</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81797e39)
Location: include/linux/iommu.h:639
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a662e)
Location: include/linux/iommu.h:625
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b1a20)
Location: include/linux/iommu.h:625
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81789b9e)
Location: include/linux/iommu.h:586
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff81794760)
Location: include/linux/iommu.h:586
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81810dde)
Location: include/linux/iommu.h:663
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181c690)
Location: include/linux/iommu.h:663
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182f3f1)
Location: include/linux/iommu.h:663
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff819517df)
Location: include/linux/iommu.h:655
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195c060)
Location: include/linux/iommu.h:655
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
```
In drivers/iommu/virtio-iommu.c (ffffffff819705c2)
Location: include/linux/iommu.h:655
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab5401)
Location: include/linux/iommu.h:698
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac2775)
Location: include/linux/iommu.h:698
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adb3d2)
Location: include/linux/iommu.h:698
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b01551)
Location: include/linux/iommu.h:701
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0efd5)
Location: include/linux/iommu.h:701
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b29692)
Location: include/linux/iommu.h:701
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_iommu_priv_set(struct device *dev, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b721a0)
Location: drivers/iommu/iommu.c:390
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81b721a0-ffffffff81b721c0: dev_iommu_priv_set (STB_GLOBAL)
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
