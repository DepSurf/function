# Function: <code>intel_iommu_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815380d0)
Location: drivers/iommu/intel-iommu.c:4854
Inline: False
```
**Symbols:**

```
ffffffff815380d0-ffffffff8153816e: intel_iommu_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158cbc0)
Location: drivers/iommu/intel-iommu.c:4992
Inline: False
```
**Symbols:**

```
ffffffff8158cbc0-ffffffff8158cc5e: intel_iommu_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815ba300)
Location: drivers/iommu/intel-iommu.c:5085
Inline: False
```
**Symbols:**

```
ffffffff815ba300-ffffffff815ba39e: intel_iommu_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cfe30)
Location: drivers/iommu/intel-iommu.c:5119
Inline: False
```
**Symbols:**

```
ffffffff815cfe30-ffffffff815cfecd: intel_iommu_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81636bd0)
Location: drivers/iommu/intel-iommu.c:5033
Inline: False
```
**Symbols:**

```
ffffffff81636bd0-ffffffff81636c6d: intel_iommu_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5075
Inline: False
```
**Symbols:**

```
ffffffff816721b0-ffffffff81672232: intel_iommu_map (STB_LOCAL)
ffffffff81675519-ffffffff8167553b: intel_iommu_map.cold.89 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5130
Inline: False
```
**Symbols:**

```
ffffffff81691d90-ffffffff81691e12: intel_iommu_map (STB_LOCAL)
ffffffff81693b8f-ffffffff81693bb1: intel_iommu_map.cold.98 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5165
Inline: False
```
**Symbols:**

```
ffffffff816c9b50-ffffffff816c9be7: intel_iommu_map (STB_LOCAL)
ffffffff816cc45d-ffffffff816cc480: intel_iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5449
Inline: False
```
**Symbols:**

```
ffffffff816ec600-ffffffff816ec687: intel_iommu_map (STB_LOCAL)
ffffffff816efca8-ffffffff816efccb: intel_iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:5508
Inline: False
```
**Symbols:**

```
ffffffff817a46f0-ffffffff817a4779: intel_iommu_map (STB_LOCAL)
ffffffff817a737b-ffffffff817a739e: intel_iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4939
Inline: False
```
**Symbols:**

```
ffffffff817b1ae0-ffffffff817b1c09: intel_iommu_map (STB_LOCAL)
ffffffff81c0cbc0-ffffffff81c0cbe3: intel_iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:5039
Inline: False
```
**Symbols:**

```
ffffffff81792ff0-ffffffff81793075: intel_iommu_map (STB_LOCAL)
ffffffff81bfde16-ffffffff81bfde39: intel_iommu_map.cold (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff8181afa3)
Location: drivers/iommu/intel/iommu.c:5030
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
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
In drivers/iommu/intel/iommu.c (ffffffff8195b686)
Location: drivers/iommu/intel/iommu.c:4380
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
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
In drivers/iommu/intel/iommu.c (ffffffff81ac3416)
Location: drivers/iommu/intel/iommu.c:4284
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
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
In drivers/iommu/intel/iommu.c (ffffffff81b101a6)
Location: drivers/iommu/intel/iommu.c:4173
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b64c46)
Location: drivers/iommu/intel/iommu.c:4065
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5449
Inline: False
```
**Symbols:**

```
ffffffff816b1f30-ffffffff816b1fb7: intel_iommu_map (STB_LOCAL)
ffffffff816b548e-ffffffff816b54b1: intel_iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5449
Inline: False
```
**Symbols:**

```
ffffffff8168fa30-ffffffff8168fab7: intel_iommu_map (STB_LOCAL)
ffffffff816930d8-ffffffff816930fb: intel_iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5449
Inline: False
```
**Symbols:**

```
ffffffff816e02c0-ffffffff816e0347: intel_iommu_map (STB_LOCAL)
ffffffff816e3968-ffffffff816e398b: intel_iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t hpa, size_t size, int iommu_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5449
Inline: False
```
**Symbols:**

```
ffffffff816fa8d0-ffffffff816fa957: intel_iommu_map (STB_LOCAL)
ffffffff816fdff8-ffffffff816fe01b: intel_iommu_map.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
