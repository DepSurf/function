# Function: <code>iova_rcache_get</code>

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
In drivers/iommu/iova.c (ffffffff81580f26)
Location: drivers/iommu/iova.c:850
Inline: True
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
In drivers/iommu/iova.c (ffffffff815adaff)
Location: drivers/iommu/iova.c:850
Inline: True
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
In drivers/iommu/iova.c (ffffffff815c376f)
Location: drivers/iommu/iova.c:822
Inline: True
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
In drivers/iommu/iova.c (ffffffff8162a41f)
Location: drivers/iommu/iova.c:982
Inline: True
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
In drivers/iommu/iova.c (ffffffff81665115)
Location: drivers/iommu/iova.c:982
Inline: True
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
In drivers/iommu/iova.c (ffffffff81683715)
Location: drivers/iommu/iova.c:991
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int iova_rcache_get(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816bab80)
Location: drivers/iommu/iova.c:990
Inline: False
```
**Symbols:**

```
ffffffff816bab80-ffffffff816bad28: iova_rcache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int iova_rcache_get(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dd9e0)
Location: drivers/iommu/iova.c:992
Inline: False
```
**Symbols:**

```
ffffffff816dd9e0-ffffffff816ddb88: iova_rcache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int iova_rcache_get(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817947f0)
Location: drivers/iommu/iova.c:994
Inline: False
```
**Symbols:**

```
ffffffff817947f0-ffffffff8179484e: iova_rcache_get (STB_LOCAL)
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
In drivers/iommu/iova.c (ffffffff817c1273)
Location: drivers/iommu/iova.c:968
Inline: True
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
In drivers/iommu/iova.c (ffffffff817a3d32)
Location: drivers/iommu/iova.c:1005
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova_fast
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
In drivers/iommu/iova.c (ffffffff8182d664)
Location: drivers/iommu/iova.c:1018
Inline: True
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
In drivers/iommu/iova.c (ffffffff8196e3f9)
Location: drivers/iommu/iova.c:869
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova_fast
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
In drivers/iommu/iova.c (ffffffff81ad8d89)
Location: drivers/iommu/iova.c:872
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova_fast
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
In drivers/iommu/iova.c (ffffffff81b26d27)
Location: drivers/iommu/iova.c:878
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova_fast
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
In drivers/iommu/iova.c (ffffffff81b7de2a)
Location: drivers/iommu/iova.c:913
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova_fast
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
long unsigned int iova_rcache_get(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cdec0)
Location: drivers/iommu/iova.c:992
Inline: False
```
**Symbols:**

```
ffff8000108cdec0-ffff8000108ce10c: iova_rcache_get (STB_LOCAL)
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
long unsigned int iova_rcache_get(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a3430)
Location: drivers/iommu/iova.c:992
Inline: False
```
**Symbols:**

```
ffffffff816a3430-ffffffff816a35d8: iova_rcache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int iova_rcache_get(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81680e20)
Location: drivers/iommu/iova.c:992
Inline: False
```
**Symbols:**

```
ffffffff81680e20-ffffffff81680fc8: iova_rcache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int iova_rcache_get(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d16a0)
Location: drivers/iommu/iova.c:992
Inline: False
```
**Symbols:**

```
ffffffff816d16a0-ffffffff816d1848: iova_rcache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int iova_rcache_get(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eaff0)
Location: drivers/iommu/iova.c:992
Inline: False
```
**Symbols:**

```
ffffffff816eaff0-ffffffff816eb1b2: iova_rcache_get (STB_LOCAL)
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
