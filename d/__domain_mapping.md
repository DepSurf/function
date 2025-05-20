# Function: <code>__domain_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815378f0)
Location: drivers/iommu/intel-iommu.c:2133
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815378f0-ffffffff81537cd4: __domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158c3b0)
Location: drivers/iommu/intel-iommu.c:2177
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff8158c3b0-ffffffff8158c7c7: __domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b9af0)
Location: drivers/iommu/intel-iommu.c:2220
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff815b9af0-ffffffff815b9f01: __domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cfa70)
Location: drivers/iommu/intel-iommu.c:2228
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff815cfa70-ffffffff815cfe2d: __domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81636800)
Location: drivers/iommu/intel-iommu.c:2227
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff81636800-ffffffff81636bce: __domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2255
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff81671d60-ffffffff816720ba: __domain_mapping (STB_LOCAL)
ffffffff816754ca-ffffffff81675519: __domain_mapping.cold.88 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2224
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff81690690-ffffffff816909ea: __domain_mapping (STB_LOCAL)
ffffffff81693976-ffffffff816939c5: __domain_mapping.cold.93 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2212
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816c8840-ffffffff816c8ba0: __domain_mapping (STB_LOCAL)
ffffffff816cc2f4-ffffffff816cc36f: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2223
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816eb800-ffffffff816ebb60: __domain_mapping (STB_LOCAL)
ffffffff816efbb6-ffffffff816efc05: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2239
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
```
**Symbols:**

```
ffffffff817a2970-ffffffff817a2cdf: __domain_mapping (STB_LOCAL)
ffffffff817a6df6-ffffffff817a6e45: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2298
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
```
**Symbols:**

```
ffffffff817afbb0-ffffffff817afe1d: __domain_mapping (STB_LOCAL)
ffffffff81c0c5de-ffffffff81c0c61d: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2339
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
```
**Symbols:**

```
ffffffff81792d90-ffffffff81792feb: __domain_mapping (STB_LOCAL)
ffffffff81bfdde2-ffffffff81bfde16: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2331
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
```
**Symbols:**

```
ffffffff8181ac40-ffffffff8181aeed: __domain_mapping (STB_LOCAL)
ffffffff81cffa52-ffffffff81cffb1d: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2223
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
```
**Symbols:**

```
ffffffff8195b320-ffffffff8195b5b6: __domain_mapping (STB_LOCAL)
ffffffff81ec80fd-ffffffff81ec8184: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2183
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81ac2f20-ffffffff81ac31f3: __domain_mapping (STB_LOCAL)
ffffffff82097993-ffffffff820979e2: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2146
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81b0fe30-ffffffff81b10111: __domain_mapping (STB_LOCAL)
ffffffff82118905-ffffffff8211894b: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2060
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81b648a0-ffffffff81b64bba: __domain_mapping (STB_LOCAL)
ffffffff821f6639-ffffffff821f667f: __domain_mapping.cold (STB_LOCAL)
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
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2223
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816b1130-ffffffff816b1490: __domain_mapping (STB_LOCAL)
ffffffff816b539c-ffffffff816b53eb: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2223
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff8168ec30-ffffffff8168ef90: __domain_mapping (STB_LOCAL)
ffffffff81692fe6-ffffffff81693035: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2223
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816df4c0-ffffffff816df820: __domain_mapping (STB_LOCAL)
ffffffff816e3876-ffffffff816e38c5: __domain_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2223
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff816f9ad0-ffffffff816f9e30: __domain_mapping (STB_LOCAL)
ffffffff816fdf06-ffffffff816fdf55: __domain_mapping.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct scatterlist *sg</code>
</li>
<li>
<b>Param reordered. </b>
<code>domain, iov_pfn, sg, phys_pfn, nr_pages, prot</code> ➡️ <code>domain, iov_pfn, phys_pfn, nr_pages, prot</code>
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
