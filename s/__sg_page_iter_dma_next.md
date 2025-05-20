# Function: <code>__sg_page_iter_dma_next</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504940)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
ffffffff81504940-ffffffff815049bc: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522880)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
ffffffff81522880-ffffffff815228fc: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81585ad0)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
ffffffff81585ad0-ffffffff81585b4c: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a2bb0)
Location: lib/scatterlist.c:722
Inline: True
```
**Symbols:**

```
ffffffff815a2bb0-ffffffff815a2c2c: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a9ae0)
Location: lib/scatterlist.c:722
Inline: True
```
**Symbols:**

```
ffffffff815a9ae0-ffffffff815a9b5c: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81612d20)
Location: lib/scatterlist.c:753
Inline: True
```
**Symbols:**

```
ffffffff81612d20-ffffffff81612d9c: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816dee50)
Location: lib/scatterlist.c:753
Inline: False
```
**Symbols:**

```
ffffffff816dee50-ffffffff816deef0: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cf010)
Location: lib/scatterlist.c:763
Inline: False
```
**Symbols:**

```
ffffffff817cf010-ffffffff817cf0b0: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180d4c0)
Location: lib/scatterlist.c:765
Inline: False
```
**Symbols:**

```
ffffffff8180d4c0-ffffffff8180d559: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81853170)
Location: lib/scatterlist.c:766
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_prime.c:drm_prime_sg_to_dma_addr_array
```
**Symbols:**

```
ffffffff81853170-ffffffff81853209: __sg_page_iter_dma_next (STB_GLOBAL)
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
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c5d8)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
ffff80001062c5d8-ffff80001062c684: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d30ac)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
c07d30ac-c07d3170: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cf150)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
c0000000007cf150-c0000000007cf238: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c7c6)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
ffffffe00045c7c6-ffffffe00045c84e: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151ae60)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
ffffffff8151ae60-ffffffff8151aedc: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150b150)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
ffffffff8150b150-ffffffff8150b1cc: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81516ef0)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
ffffffff81516ef0-ffffffff81516f6c: __sg_page_iter_dma_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool __sg_page_iter_dma_next(struct sg_dma_page_iter *dma_iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530680)
Location: lib/scatterlist.c:641
Inline: True
```
**Symbols:**

```
ffffffff81530680-ffffffff815306fc: __sg_page_iter_dma_next (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
