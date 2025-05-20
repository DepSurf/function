# Function: <code>__iommu_map</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2171
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map_atomic
```
**Symbols:**

```
ffffffff81790736-ffffffff81790759: __iommu_map.cold (STB_LOCAL)
ffffffff8178f8e0-ffffffff8178fb0e: __iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2381
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map_atomic
```
**Symbols:**

```
ffffffff817bb590-ffffffff817bb770: __iommu_map (STB_LOCAL)
ffffffff81c0d602-ffffffff81c0d625: __iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2412
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map_atomic
```
**Symbols:**

```
ffffffff8179dc90-ffffffff8179de70: __iommu_map (STB_LOCAL)
ffffffff81bff8ac-ffffffff81bff8cf: __iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2482
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map_atomic
```
**Symbols:**

```
ffffffff81826cc0-ffffffff81826f25: __iommu_map (STB_LOCAL)
ffffffff81d019a0-ffffffff81d019e8: __iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2259
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map_atomic
```
**Symbols:**

```
ffffffff81966840-ffffffff81966abb: __iommu_map (STB_LOCAL)
ffffffff81ec9ec4-ffffffff81ec9f05: __iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2323
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map_atomic
```
**Symbols:**

```
ffffffff81acff80-ffffffff81ad0212: __iommu_map (STB_LOCAL)
ffffffff82097cb0-ffffffff82097cd5: __iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2342
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
```
**Symbols:**

```
ffffffff81b1f8b0-ffffffff81b1fb42: __iommu_map (STB_LOCAL)
ffffffff82118cc9-ffffffff82118cee: __iommu_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2607
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff81b75920-ffffffff81b75b9a: __iommu_map (STB_LOCAL)
ffffffff821f6bd2-ffffffff821f6c07: __iommu_map.cold (STB_LOCAL)
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
