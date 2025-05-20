# Function: <code>__iova_rcache_insert</code>

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
In drivers/iommu/iova.c (ffffffff81580899)
Location: drivers/iommu/iova.c:745
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
In drivers/iommu/iova.c (ffffffff815ad6f5)
Location: drivers/iommu/iova.c:745
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
In drivers/iommu/iova.c (ffffffff815c3313)
Location: drivers/iommu/iova.c:719
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
In drivers/iommu/iova.c (ffffffff81629c93)
Location: drivers/iommu/iova.c:879
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
In drivers/iommu/iova.c (ffffffff816649a3)
Location: drivers/iommu/iova.c:879
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
In drivers/iommu/iova.c (ffffffff81682f93)
Location: drivers/iommu/iova.c:888
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
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
In drivers/iommu/iova.c (ffffffff816ba51a)
Location: drivers/iommu/iova.c:887
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_insert
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
In drivers/iommu/iova.c (ffffffff816dd34a)
Location: drivers/iommu/iova.c:889
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __iova_rcache_insert(struct iova_domain *iovad, struct iova_rcache *rcache, long unsigned int iova_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81794030)
Location: drivers/iommu/iova.c:891
Inline: False
Direct callers:
  - drivers/iommu/iova.c:iova_rcache_insert
```
**Symbols:**

```
ffffffff81794030-ffffffff81794224: __iova_rcache_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __iova_rcache_insert(struct iova_domain *iovad, struct iova_rcache *rcache, long unsigned int iova_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c08a0)
Location: drivers/iommu/iova.c:865
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff817c08a0-ffffffff817c0a94: __iova_rcache_insert (STB_LOCAL)
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
In drivers/iommu/iova.c (ffffffff817a4055)
Location: drivers/iommu/iova.c:902
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
In drivers/iommu/iova.c (ffffffff8182d1af)
Location: drivers/iommu/iova.c:915
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
In drivers/iommu/iova.c (ffffffff8196e740)
Location: drivers/iommu/iova.c:766
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
In drivers/iommu/iova.c (ffffffff81ad90ac)
Location: drivers/iommu/iova.c:769
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
In drivers/iommu/iova.c (ffffffff81b2716c)
Location: drivers/iommu/iova.c:775
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
In drivers/iommu/iova.c (ffffffff81b7d783)
Location: drivers/iommu/iova.c:820
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cd6e0)
Location: drivers/iommu/iova.c:889
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_insert
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
In drivers/iommu/iova.c (ffffffff816a2d9a)
Location: drivers/iommu/iova.c:889
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_insert
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
In drivers/iommu/iova.c (ffffffff8168078a)
Location: drivers/iommu/iova.c:889
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_insert
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
In drivers/iommu/iova.c (ffffffff816d100a)
Location: drivers/iommu/iova.c:889
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_insert
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
In drivers/iommu/iova.c (ffffffff816eb90a)
Location: drivers/iommu/iova.c:889
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_insert
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
