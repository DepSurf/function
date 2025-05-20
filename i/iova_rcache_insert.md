# Function: <code>iova_rcache_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580846)
Location: drivers/iommu/iova.c:794
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
In drivers/iommu/iova.c (ffffffff815ad6ac)
Location: drivers/iommu/iova.c:794
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
In drivers/iommu/iova.c (ffffffff815c32cc)
Location: drivers/iommu/iova.c:767
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
In drivers/iommu/iova.c (ffffffff81629c4c)
Location: drivers/iommu/iova.c:927
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
In drivers/iommu/iova.c (ffffffff81664945)
Location: drivers/iommu/iova.c:927
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81682f35)
Location: drivers/iommu/iova.c:936
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool iova_rcache_insert(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ba4c0)
Location: drivers/iommu/iova.c:935
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816ba4c0-ffffffff816ba72f: iova_rcache_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool iova_rcache_insert(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dd2f0)
Location: drivers/iommu/iova.c:937
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816dd2f0-ffffffff816dd567: iova_rcache_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool iova_rcache_insert(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81794230)
Location: drivers/iommu/iova.c:939
Inline: False
Direct callers:
  - drivers/iommu/iova.c:fq_ring_free
```
**Symbols:**

```
ffffffff81794230-ffffffff81794288: iova_rcache_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0d80)
Location: drivers/iommu/iova.c:913
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a3fe0)
Location: drivers/iommu/iova.c:950
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
In drivers/iommu/iova.c (ffffffff8182d165)
Location: drivers/iommu/iova.c:963
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
In drivers/iommu/iova.c (ffffffff8196e705)
Location: drivers/iommu/iova.c:814
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
In drivers/iommu/iova.c (ffffffff81ad9075)
Location: drivers/iommu/iova.c:817
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
In drivers/iommu/iova.c (ffffffff81b27135)
Location: drivers/iommu/iova.c:823
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
In drivers/iommu/iova.c (ffffffff81b7d745)
Location: drivers/iommu/iova.c:858
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
bool iova_rcache_insert(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cd668)
Location: drivers/iommu/iova.c:937
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffff8000108cd668-ffff8000108cd8e4: iova_rcache_insert (STB_LOCAL)
```
</details>
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
bool iova_rcache_insert(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a2d40)
Location: drivers/iommu/iova.c:937
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816a2d40-ffffffff816a2fb7: iova_rcache_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool iova_rcache_insert(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81680730)
Location: drivers/iommu/iova.c:937
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff81680730-ffffffff816809a7: iova_rcache_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool iova_rcache_insert(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d0fb0)
Location: drivers/iommu/iova.c:937
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816d0fb0-ffffffff816d1227: iova_rcache_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool iova_rcache_insert(struct iova_domain *iovad, long unsigned int pfn, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eb8b0)
Location: drivers/iommu/iova.c:937
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816eb8b0-ffffffff816ebb37: iova_rcache_insert (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
