# Function: <code>iommu_support_dev_iotlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153898b)
Location: drivers/iommu/intel-iommu.c:1440
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158d4b9)
Location: drivers/iommu/intel-iommu.c:1447
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bade1)
Location: drivers/iommu/intel-iommu.c:1461
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d0ad5)
Location: drivers/iommu/intel-iommu.c:1466
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816378cf)
Location: drivers/iommu/intel-iommu.c:1449
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81672af2)
Location: drivers/iommu/intel-iommu.c:1451
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168f320)
Location: drivers/iommu/intel-iommu.c:1327
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff8168f320-ffffffff8168f386: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c6c00)
Location: drivers/iommu/intel-iommu.c:1332
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff816c6c00-ffffffff816c6c68: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e9bc0)
Location: drivers/iommu/intel-iommu.c:1343
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff816e9bc0-ffffffff816e9c28: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179f260)
Location: drivers/iommu/intel/iommu.c:1359
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff8179f260-ffffffff8179f2ce: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ac9e0)
Location: drivers/iommu/intel/iommu.c:1442
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff817ac9e0-ffffffff817aca4e: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8178f8b0)
Location: drivers/iommu/intel/iommu.c:1466
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff8178f8b0-ffffffff8178f915: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff818171e0)
Location: drivers/iommu/intel/iommu.c:1470
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff818171e0-ffffffff81817245: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81958110)
Location: drivers/iommu/intel/iommu.c:1400
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81958110-ffffffff8195818d: iommu_support_dev_iotlb (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816af6a0)
Location: drivers/iommu/intel-iommu.c:1343
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff816af6a0-ffffffff816af708: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168cff0)
Location: drivers/iommu/intel-iommu.c:1343
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff8168cff0-ffffffff8168d058: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dd880)
Location: drivers/iommu/intel-iommu.c:1343
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff816dd880-ffffffff816dd8e8: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct device_domain_info *iommu_support_dev_iotlb(struct dmar_domain *domain, struct intel_iommu *iommu, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f7c20)
Location: drivers/iommu/intel-iommu.c:1343
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff816f7c20-ffffffff816f7c88: iommu_support_dev_iotlb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
