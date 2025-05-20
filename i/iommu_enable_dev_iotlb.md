# Function: <code>iommu_enable_dev_iotlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815362d0)
Location: drivers/iommu/intel-iommu.c:1461
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
```
**Symbols:**

```
ffffffff815362d0-ffffffff81536381: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158b560)
Location: drivers/iommu/intel-iommu.c:1491
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff8158b560-ffffffff8158b626: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b8cb0)
Location: drivers/iommu/intel-iommu.c:1505
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff815b8cb0-ffffffff815b8d76: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cee40)
Location: drivers/iommu/intel-iommu.c:1510
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff815cee40-ffffffff815cef0b: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81635bb0)
Location: drivers/iommu/intel-iommu.c:1493
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81635bb0-ffffffff81635c79: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81670dd0)
Location: drivers/iommu/intel-iommu.c:1495
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81670dd0-ffffffff81670ee7: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168f1f0)
Location: drivers/iommu/intel-iommu.c:1371
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff8168f1f0-ffffffff8168f314: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c6a90)
Location: drivers/iommu/intel-iommu.c:1376
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff816c6a90-ffffffff816c6bf5: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e9a50)
Location: drivers/iommu/intel-iommu.c:1387
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff816e9a50-ffffffff816e9bb5: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a0750)
Location: drivers/iommu/intel/iommu.c:1403
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff817a0750-ffffffff817a0895: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ad1f0)
Location: drivers/iommu/intel/iommu.c:1491
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff817ad1f0-ffffffff817ad335: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8178fcd0)
Location: drivers/iommu/intel/iommu.c:1515
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff8178fcd0-ffffffff8178fdef: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff818176e0)
Location: drivers/iommu/intel/iommu.c:1519
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff818176e0-ffffffff818177ff: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81958500)
Location: drivers/iommu/intel/iommu.c:1437
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81958500-ffffffff81958691: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816af530)
Location: drivers/iommu/intel-iommu.c:1387
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff816af530-ffffffff816af695: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168ce80)
Location: drivers/iommu/intel-iommu.c:1387
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff8168ce80-ffffffff8168cfe5: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dd710)
Location: drivers/iommu/intel-iommu.c:1387
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff816dd710-ffffffff816dd875: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f7ab0)
Location: drivers/iommu/intel-iommu.c:1387
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff816f7ab0-ffffffff816f7c15: iommu_enable_dev_iotlb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
