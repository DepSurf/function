# Function: <code>domain_unmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815359d0)
Location: drivers/iommu/intel-iommu.c:1250
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff815359d0-ffffffff81535acb: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158a230)
Location: drivers/iommu/intel-iommu.c:1257
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff8158a230-ffffffff8158a332: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b78b0)
Location: drivers/iommu/intel-iommu.c:1271
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff815b78b0-ffffffff815b79ac: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cd8a0)
Location: drivers/iommu/intel-iommu.c:1276
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff815cd8a0-ffffffff815cd993: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816346d0)
Location: drivers/iommu/intel-iommu.c:1252
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
```
**Symbols:**

```
ffffffff816346d0-ffffffff816347c3: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8166fbe0)
Location: drivers/iommu/intel-iommu.c:1254
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
```
**Symbols:**

```
ffffffff8166fbe0-ffffffff8166fcd3: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168e0f0)
Location: drivers/iommu/intel-iommu.c:1130
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
```
**Symbols:**

```
ffffffff8168e0f0-ffffffff8168e1e3: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c5710)
Location: drivers/iommu/intel-iommu.c:1135
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff816c5710-ffffffff816c5804: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e8680)
Location: drivers/iommu/intel-iommu.c:1146
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff816e8680-ffffffff816e8774: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a11f0)
Location: drivers/iommu/intel/iommu.c:1162
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:intel_unmap
  - drivers/iommu/intel/iommu.c:intel_unmap
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff817a11f0-ffffffff817a12e4: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ae780)
Location: drivers/iommu/intel/iommu.c:1252
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff817ae780-ffffffff817ae876: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81791000)
Location: drivers/iommu/intel/iommu.c:1271
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff81791000-ffffffff817910f5: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1275
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff81819e80-ffffffff81819f9e: domain_unmap (STB_LOCAL)
ffffffff81cff678-ffffffff81cff6fa: domain_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, struct list_head *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1222
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff8195a760-ffffffff8195a8ba: domain_unmap (STB_LOCAL)
ffffffff81ec7e78-ffffffff81ec7ef2: domain_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, struct list_head *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1174
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff81ac2000-ffffffff81ac2144: domain_unmap (STB_LOCAL)
ffffffff820976ed-ffffffff82097764: domain_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, struct list_head *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1173
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff81b0e2a0-ffffffff81b0e3f4: domain_unmap (STB_LOCAL)
ffffffff82118766-ffffffff8211879c: domain_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, struct list_head *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1033
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff81b630a0-ffffffff81b631f4: domain_unmap (STB_LOCAL)
ffffffff821f64b2-ffffffff821f64e8: domain_unmap.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ae160)
Location: drivers/iommu/intel-iommu.c:1146
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff816ae160-ffffffff816ae254: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168bac0)
Location: drivers/iommu/intel-iommu.c:1146
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff8168bac0-ffffffff8168bbb4: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dc340)
Location: drivers/iommu/intel-iommu.c:1146
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff816dc340-ffffffff816dc434: domain_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *domain_unmap(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f6980)
Location: drivers/iommu/intel-iommu.c:1146
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:domain_exit
```
**Symbols:**

```
ffffffff816f6980-ffffffff816f6a74: domain_unmap (STB_LOCAL)
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
<b>Param added. </b>
<code>struct page *freelist</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct page *freelist</code> ➡️ <code>struct list_head *freelist</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
