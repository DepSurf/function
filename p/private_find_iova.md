# Function: <code>private_find_iova</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815803f0)
Location: drivers/iommu/iova.c:307
Inline: True
Direct callers:
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff815803f0-ffffffff81580431: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815acf90)
Location: drivers/iommu/iova.c:307
Inline: True
Direct callers:
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff815acf90-ffffffff815acfd1: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815c2e00)
Location: drivers/iommu/iova.c:283
Inline: True
Direct callers:
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff815c2e00-ffffffff815c2e3f: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816298f0)
Location: drivers/iommu/iova.c:310
Inline: True
Direct callers:
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff816298f0-ffffffff8162992e: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816645f0)
Location: drivers/iommu/iova.c:310
Inline: True
Direct callers:
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff816645f0-ffffffff8166462c: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816824e0)
Location: drivers/iommu/iova.c:319
Inline: True
Direct callers:
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff816824e0-ffffffff8168251c: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816b9cf0)
Location: drivers/iommu/iova.c:318
Inline: True
Direct callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff816b9cf0-ffffffff816b9d27: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dcaf0)
Location: drivers/iommu/iova.c:318
Inline: True
Direct callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff816dcaf0-ffffffff816dcb27: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817937a0)
Location: drivers/iommu/iova.c:318
Inline: True
Inline callers:
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:find_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0040)
Location: drivers/iommu/iova.c:328
Inline: True
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff817c0040-ffffffff817c0077: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a31c0)
Location: drivers/iommu/iova.c:395
Inline: True
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff817a31c0-ffffffff817a31f7: private_find_iova (STB_LOCAL)
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
In drivers/iommu/iova.c (ffffffff8182cf12)
Location: drivers/iommu/iova.c:392
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
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
In drivers/iommu/iova.c (ffffffff8196dfe2)
Location: drivers/iommu/iova.c:333
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
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
In drivers/iommu/iova.c (ffffffff81ad8b98)
Location: drivers/iommu/iova.c:338
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
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
In drivers/iommu/iova.c (ffffffff81b26b31)
Location: drivers/iommu/iova.c:338
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
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
In drivers/iommu/iova.c (ffffffff81b7dc31)
Location: drivers/iommu/iova.c:339
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108ccab0)
Location: drivers/iommu/iova.c:318
Inline: True
Direct callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffff8000108ccab0-ffff8000108ccb14: private_find_iova (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a2540)
Location: drivers/iommu/iova.c:318
Inline: True
Direct callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff816a2540-ffffffff816a2577: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8167ff30)
Location: drivers/iommu/iova.c:318
Inline: True
Direct callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff8167ff30-ffffffff8167ff67: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d07b0)
Location: drivers/iommu/iova.c:318
Inline: True
Direct callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff816d07b0-ffffffff816d07e7: private_find_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct iova *private_find_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ead40)
Location: drivers/iommu/iova.c:318
Inline: True
Direct callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:find_iova
```
**Symbols:**

```
ffffffff816ead40-ffffffff816ead77: private_find_iova (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
