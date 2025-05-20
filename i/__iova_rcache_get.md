# Function: <code>__iova_rcache_get</code>

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
In drivers/iommu/iova.c (ffffffff81580fe7)
Location: drivers/iommu/iova.c:810
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
In drivers/iommu/iova.c (ffffffff815adbad)
Location: drivers/iommu/iova.c:810
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
In drivers/iommu/iova.c (ffffffff815c381e)
Location: drivers/iommu/iova.c:783
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
In drivers/iommu/iova.c (ffffffff8162a498)
Location: drivers/iommu/iova.c:943
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
In drivers/iommu/iova.c (ffffffff816651c8)
Location: drivers/iommu/iova.c:943
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
In drivers/iommu/iova.c (ffffffff816837c8)
Location: drivers/iommu/iova.c:952
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816babe6)
Location: drivers/iommu/iova.c:951
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dda46)
Location: drivers/iommu/iova.c:953
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __iova_rcache_get(struct iova_rcache *rcache, long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817946d0)
Location: drivers/iommu/iova.c:955
Inline: False
Direct callers:
  - drivers/iommu/iova.c:iova_rcache_get
```
**Symbols:**

```
ffffffff817946d0-ffffffff817947e5: __iova_rcache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __iova_rcache_get(struct iova_rcache *rcache, long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0c50)
Location: drivers/iommu/iova.c:929
Inline: False
```
**Symbols:**

```
ffffffff817c0c50-ffffffff817c0d65: __iova_rcache_get (STB_LOCAL)
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
In drivers/iommu/iova.c (ffffffff817a3e4c)
Location: drivers/iommu/iova.c:966
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
In drivers/iommu/iova.c (ffffffff8182d7c8)
Location: drivers/iommu/iova.c:979
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
In drivers/iommu/iova.c (ffffffff8196e433)
Location: drivers/iommu/iova.c:830
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
In drivers/iommu/iova.c (ffffffff81ad8daa)
Location: drivers/iommu/iova.c:833
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
In drivers/iommu/iova.c (ffffffff81b26d50)
Location: drivers/iommu/iova.c:839
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
In drivers/iommu/iova.c (ffffffff81b7de50)
Location: drivers/iommu/iova.c:874
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cdf34)
Location: drivers/iommu/iova.c:953
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a3496)
Location: drivers/iommu/iova.c:953
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81680e86)
Location: drivers/iommu/iova.c:953
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d1706)
Location: drivers/iommu/iova.c:953
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eb056)
Location: drivers/iommu/iova.c:953
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
