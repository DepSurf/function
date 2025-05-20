# Function: <code>domain_setup_first_level</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int domain_setup_first_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, int pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179f3a0)
Location: drivers/iommu/intel/iommu.c:2480
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8179f3a0-ffffffff8179f442: domain_setup_first_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int domain_setup_first_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ace70)
Location: drivers/iommu/intel/iommu.c:2501
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff817ace70-ffffffff817acf12: domain_setup_first_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int domain_setup_first_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8178fb80)
Location: drivers/iommu/intel/iommu.c:2535
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8178fb80-ffffffff8178fc3f: domain_setup_first_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int domain_setup_first_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff818174b0)
Location: drivers/iommu/intel/iommu.c:2525
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff818174b0-ffffffff818175b2: domain_setup_first_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195d54e)
Location: drivers/iommu/intel/iommu.c:2391
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac5081)
Location: drivers/iommu/intel/iommu.c:2326
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b11ac0)
Location: drivers/iommu/intel/iommu.c:2292
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int domain_setup_first_level(struct intel_iommu *iommu, struct dmar_domain *domain, struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b60070)
Location: drivers/iommu/intel/iommu.c:2213
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff81b60070-ffffffff81b6015b: domain_setup_first_level (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pasid</code> ➡️ <code>u32 pasid</code>
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
