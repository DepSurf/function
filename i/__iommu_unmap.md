# Function: <code>__iommu_unmap</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816263e0)
Location: drivers/iommu/iommu.c:1560
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff816263e0-ffffffff816265bd: __iommu_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1566
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff81661020-ffffffff816611ea: __iommu_unmap (STB_LOCAL)
ffffffff81662cba-ffffffff81662cd5: __iommu_unmap.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1642
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff8167f8f0-ffffffff8167faad: __iommu_unmap (STB_LOCAL)
ffffffff8168129a-ffffffff816812b7: __iommu_unmap.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1863
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_map
```
**Symbols:**

```
ffffffff816b6ce0-ffffffff816b6e9a: __iommu_unmap (STB_LOCAL)
ffffffff816b8983-ffffffff816b899e: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1919
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff816d9870-ffffffff816d99eb: __iommu_unmap (STB_LOCAL)
ffffffff816db803-ffffffff816db81e: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2246
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff8178e810-ffffffff8178e97f: __iommu_unmap (STB_LOCAL)
ffffffff8179071b-ffffffff81790736: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2466
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff817baa50-ffffffff817babb0: __iommu_unmap (STB_LOCAL)
ffffffff81c0d5e7-ffffffff81c0d602: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2497
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff8179d360-ffffffff8179d4bd: __iommu_unmap (STB_LOCAL)
ffffffff81bff894-ffffffff81bff8ac: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2583
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff81826030-ffffffff818261f1: __iommu_unmap (STB_LOCAL)
ffffffff81d01964-ffffffff81d019a0: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2360
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff819662e0-ffffffff819664d7: __iommu_unmap (STB_LOCAL)
ffffffff81ec9e8b-ffffffff81ec9ec4: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2424
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff81acfc80-ffffffff81acfe88: __iommu_unmap (STB_LOCAL)
ffffffff82097c8f-ffffffff82097cb0: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2436
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff81b1ef30-ffffffff81b1f138: __iommu_unmap (STB_LOCAL)
ffffffff82118c8a-ffffffff82118cab: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2700
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff81b753a0-ffffffff81b75579: __iommu_unmap (STB_LOCAL)
ffffffff821f6bb1-ffffffff821f6bd2: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c56b8)
Location: drivers/iommu/iommu.c:1919
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffff8000108c56b8-ffff8000108c58bc: __iommu_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bc498)
Location: drivers/iommu/iommu.c:1919
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
c09bc498-c09bc68c: __iommu_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096b190)
Location: drivers/iommu/iommu.c:1919
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
c00000000096b190-c00000000096b424: __iommu_unmap (STB_LOCAL)
```
</details>
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
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1919
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff8169f2c0-ffffffff8169f43b: __iommu_unmap (STB_LOCAL)
ffffffff816a1253-ffffffff816a126e: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1919
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff8167ccb0-ffffffff8167ce2b: __iommu_unmap (STB_LOCAL)
ffffffff8167ec43-ffffffff8167ec5e: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1919
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff816cd530-ffffffff816cd6ab: __iommu_unmap (STB_LOCAL)
ffffffff816cf4c3-ffffffff816cf4de: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
size_t __iommu_unmap(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1919
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_unmap_fast
  - drivers/iommu/iommu.c:iommu_unmap
```
**Symbols:**

```
ffffffff816e7a40-ffffffff816e7bd4: __iommu_unmap (STB_LOCAL)
ffffffff816e9a4a-ffffffff816e9a65: __iommu_unmap.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_iotlb_gather *iotlb_gather</code>
</li>
<li>
<b>Param removed. </b>
<code>bool sync</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
