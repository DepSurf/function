# Function: <code>free_iova</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8152d3d0)
Location: drivers/iommu/iova.c:362
Inline: False
```
**Symbols:**

```
ffffffff8152d3d0-ffffffff8152d3f5: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580790)
Location: drivers/iommu/iova.c:383
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff81580790-ffffffff815807b5: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815ad330)
Location: drivers/iommu/iova.c:383
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff815ad330-ffffffff815ad355: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815c2f40)
Location: drivers/iommu/iova.c:359
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff815c2f40-ffffffff815c2f65: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816299f0)
Location: drivers/iommu/iova.c:383
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816299f0-ffffffff81629a15: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81664700)
Location: drivers/iommu/iova.c:383
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff81664700-ffffffff81664725: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81682d00)
Location: drivers/iommu/iova.c:392
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff81682d00-ffffffff81682d25: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ba410)
Location: drivers/iommu/iova.c:391
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816ba410-ffffffff816ba437: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dd240)
Location: drivers/iommu/iova.c:391
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816dd240-ffffffff816dd267: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8179439d)
Location: drivers/iommu/iova.c:391
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_ring_free
```
**Symbols:**

```
ffffffff81794610-ffffffff81794658: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0da0)
Location: drivers/iommu/iova.c:401
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff817c07d0-ffffffff817c081b: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a400b)
Location: drivers/iommu/iova.c:468
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff817a3a60-ffffffff817a3aab: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8182cef0)
Location: drivers/iommu/iova.c:465
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff8182cef0-ffffffff8182cf8a: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8196dfc0)
Location: drivers/iommu/iova.c:406
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff8196dfc0-ffffffff8196e069: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81ad8910)
Location: drivers/iommu/iova.c:411
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff81ad8910-ffffffff81ad89b9: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b26a30)
Location: drivers/iommu/iova.c:411
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff81b26a30-ffffffff81b26ad9: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b7d670)
Location: drivers/iommu/iova.c:412
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff81b7d670-ffffffff81b7d719: free_iova (STB_GLOBAL)
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
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cd290)
Location: drivers/iommu/iova.c:391
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffff8000108cd290-ffff8000108cd2d4: free_iova (STB_GLOBAL)
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
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a2c90)
Location: drivers/iommu/iova.c:391
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816a2c90-ffffffff816a2cb7: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81680680)
Location: drivers/iommu/iova.c:391
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff81680680-ffffffff816806a7: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d0f00)
Location: drivers/iommu/iova.c:391
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816d0f00-ffffffff816d0f27: free_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_iova(struct iova_domain *iovad, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eb660)
Location: drivers/iommu/iova.c:391
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova_fast
```
**Symbols:**

```
ffffffff816eb660-ffffffff816eb687: free_iova (STB_GLOBAL)
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
