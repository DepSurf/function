# Function: <code>iommu_get_domain_for_dev_pasid</code>

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
struct iommu_domain *iommu_get_domain_for_dev_pasid(struct device *dev, ioasid_t pasid, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acf030)
Location: drivers/iommu/iommu.c:3410
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid
  - drivers/iommu/io-pgfault.c:iopf_handler
```
**Symbols:**

```
ffffffff81acf030-ffffffff81acf0b7: iommu_get_domain_for_dev_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev_pasid(struct device *dev, ioasid_t pasid, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1dba0)
Location: drivers/iommu/iommu.c:3363
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid
  - drivers/iommu/io-pgfault.c:iopf_handler
```
**Symbols:**

```
ffffffff81b1dba0-ffffffff81b1dc27: iommu_get_domain_for_dev_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev_pasid(struct device *dev, ioasid_t pasid, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b73d60)
Location: drivers/iommu/iommu.c:3605
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid
  - drivers/iommu/io-pgfault.c:iopf_handler
```
**Symbols:**

```
ffffffff81b73d60-ffffffff81b73dd2: iommu_get_domain_for_dev_pasid (STB_GLOBAL)
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
