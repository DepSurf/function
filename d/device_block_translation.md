# Function: <code>device_block_translation</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_block_translation(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac2530)
Location: drivers/iommu/intel/iommu.c:4115
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:blocking_domain_attach_dev
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81ac2530-ffffffff81ac2663: device_block_translation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_block_translation(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0ed90)
Location: drivers/iommu/intel/iommu.c:4005
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:blocking_domain_attach_dev
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81b0ed90-ffffffff81b0eec3: device_block_translation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_block_translation(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b67040)
Location: drivers/iommu/intel/iommu.c:3847
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:blocking_domain_attach_dev
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/nested.c:intel_nested_attach_dev
```
**Symbols:**

```
ffffffff81b67040-ffffffff81b67172: device_block_translation (STB_GLOBAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
