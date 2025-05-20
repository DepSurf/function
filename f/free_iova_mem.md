# Function: <code>free_iova_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8152cd80)
Location: drivers/iommu/iova.c:218
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff8152cd80-ffffffff8152cd9a: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580e73)
Location: drivers/iommu/iova.c:230
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81580130-ffffffff8158014a: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815ada33)
Location: drivers/iommu/iova.c:230
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff815accc0-ffffffff815accda: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815c3695)
Location: drivers/iommu/iova.c:206
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff815c2900-ffffffff815c291a: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8162a339)
Location: drivers/iommu/iova.c:232
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816292b0-ffffffff816292ca: free_iova_mem.part.7 (STB_LOCAL)
ffffffff816292d0-ffffffff816292e9: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81665050)
Location: drivers/iommu/iova.c:232
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81663fd0-ffffffff81663fea: free_iova_mem.part.9 (STB_LOCAL)
ffffffff81663ff0-ffffffff81664008: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81683650)
Location: drivers/iommu/iova.c:241
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81682860-ffffffff8168287a: free_iova_mem.part.11 (STB_LOCAL)
ffffffff81682880-ffffffff81682898: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816baf3e)
Location: drivers/iommu/iova.c:240
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816b9f90-ffffffff816b9faa: free_iova_mem.part.0 (STB_LOCAL)
ffffffff816b9fb0-ffffffff816b9fc8: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ddd9e)
Location: drivers/iommu/iova.c:240
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816dcda0-ffffffff816dcdba: free_iova_mem.part.0 (STB_LOCAL)
ffffffff816dcdc0-ffffffff816dcdd8: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81794a88)
Location: drivers/iommu/iova.c:240
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81793b90-ffffffff81793bb2: free_iova_mem (STB_GLOBAL)
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
In drivers/iommu/iova.c (ffffffff817c0694)
Location: drivers/iommu/iova.c:251
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff817a37e8)
Location: drivers/iommu/iova.c:305
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff8182ca71)
Location: drivers/iommu/iova.c:302
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff8196dda3)
Location: drivers/iommu/iova.c:243
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff81ad8c09)
Location: drivers/iommu/iova.c:248
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff81b26ba1)
Location: drivers/iommu/iova.c:248
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff81b7dca1)
Location: drivers/iommu/iova.c:249
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108ce360)
Location: drivers/iommu/iova.c:240
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffff8000108ccbb8-ffff8000108ccbec: free_iova_mem.part.0 (STB_LOCAL)
ffff8000108ccbf0-ffff8000108ccc28: free_iova_mem (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a37ee)
Location: drivers/iommu/iova.c:240
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816a27f0-ffffffff816a280a: free_iova_mem.part.0 (STB_LOCAL)
ffffffff816a2810-ffffffff816a2828: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816811de)
Location: drivers/iommu/iova.c:240
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816801e0-ffffffff816801fa: free_iova_mem.part.0 (STB_LOCAL)
ffffffff81680200-ffffffff81680218: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d1a5e)
Location: drivers/iommu/iova.c:240
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816d0a60-ffffffff816d0a7a: free_iova_mem.part.0 (STB_LOCAL)
ffffffff816d0a80-ffffffff816d0a98: free_iova_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_iova_mem(struct iova *iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ec01e)
Location: drivers/iommu/iova.c:240
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816eb1c0-ffffffff816eb1da: free_iova_mem.part.0 (STB_LOCAL)
ffffffff816eb1e0-ffffffff816eb1f8: free_iova_mem (STB_GLOBAL)
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
