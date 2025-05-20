# Function: <code>auxiliary_unlink_device</code>

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
In drivers/iommu/intel-iommu.c (ffffffff816c7d9c)
Location: drivers/iommu/intel-iommu.c:4966
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
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
In drivers/iommu/intel-iommu.c (ffffffff816ead4c)
Location: drivers/iommu/intel-iommu.c:5250
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void auxiliary_unlink_device(struct dmar_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179f2d0)
Location: drivers/iommu/intel/iommu.c:5135
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
```
**Symbols:**

```
ffffffff8179f2d0-ffffffff8179f356: auxiliary_unlink_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int auxiliary_unlink_device(struct dmar_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817acb00)
Location: drivers/iommu/intel/iommu.c:4535
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_remove_dev
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
```
**Symbols:**

```
ffffffff817acb00-ffffffff817acc08: auxiliary_unlink_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int auxiliary_unlink_device(struct dmar_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8178f9d0)
Location: drivers/iommu/intel/iommu.c:4635
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
```
**Symbols:**

```
ffffffff8178f9d0-ffffffff8178fad5: auxiliary_unlink_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int auxiliary_unlink_device(struct dmar_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81817300)
Location: drivers/iommu/intel/iommu.c:4620
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
```
**Symbols:**

```
ffffffff81817300-ffffffff81817405: auxiliary_unlink_device (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816b082c)
Location: drivers/iommu/intel-iommu.c:5250
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
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
In drivers/iommu/intel-iommu.c (ffffffff8168e17c)
Location: drivers/iommu/intel-iommu.c:5250
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
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
In drivers/iommu/intel-iommu.c (ffffffff816dea0c)
Location: drivers/iommu/intel-iommu.c:5250
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
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
In drivers/iommu/intel-iommu.c (ffffffff816f8a3c)
Location: drivers/iommu/intel-iommu.c:5250
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
