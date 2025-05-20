# Function: <code>__sg_alloc_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813f9f50)
Location: lib/scatterlist.c:275
Inline: False
```
**Symbols:**

```
ffffffff813f9f50-ffffffff813fa0a3: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81440f20)
Location: lib/scatterlist.c:275
Inline: False
```
**Symbols:**

```
ffffffff81440f20-ffffffff8144107f: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e140)
Location: lib/scatterlist.c:275
Inline: False
```
**Symbols:**

```
ffffffff8145e140-ffffffff8145e29f: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81463790)
Location: lib/scatterlist.c:275
Inline: True
```
**Symbols:**

```
ffffffff81463790-ffffffff814638df: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f6a0)
Location: lib/scatterlist.c:275
Inline: True
```
**Symbols:**

```
ffffffff8148f6a0-ffffffff8148f7f2: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c42d0)
Location: lib/scatterlist.c:263
Inline: True
```
**Symbols:**

```
ffffffff814c42d0-ffffffff814c4423: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d89c0)
Location: lib/scatterlist.c:263
Inline: True
```
**Symbols:**

```
ffffffff814d89c0-ffffffff814d8b13: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504440)
Location: lib/scatterlist.c:266
Inline: False
```
**Symbols:**

```
ffffffff81504440-ffffffff815045a8: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522450)
Location: lib/scatterlist.c:266
Inline: False
```
**Symbols:**

```
ffffffff81522450-ffffffff815225b8: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815857b0)
Location: lib/scatterlist.c:266
Inline: False
Direct callers:
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff815857b0-ffffffff81585918: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a2890)
Location: lib/scatterlist.c:266
Inline: False
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff815a2890-ffffffff815a29f8: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a97c0)
Location: lib/scatterlist.c:266
Inline: False
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff815a97c0-ffffffff815a992c: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81612a00)
Location: lib/scatterlist.c:282
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff81612a00-ffffffff81612b6c: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816df0e0)
Location: lib/scatterlist.c:282
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff816df0e0-ffffffff816df27a: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cf2f0)
Location: lib/scatterlist.c:282
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff817cf2f0-ffffffff817cf48a: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180d7a0)
Location: lib/scatterlist.c:284
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff8180d7a0-ffffffff8180d93a: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81853450)
Location: lib/scatterlist.c:285
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff81853450-ffffffff818535ea: __sg_alloc_table (STB_GLOBAL)
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
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c0d8)
Location: lib/scatterlist.c:266
Inline: False
```
**Symbols:**

```
ffff80001062c0d8-ffff80001062c240: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d2abc)
Location: lib/scatterlist.c:266
Inline: False
```
**Symbols:**

```
c07d2abc-c07d2c0c: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007ce9f0)
Location: lib/scatterlist.c:266
Inline: False
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
c0000000007ce9f0-c0000000007cebc0: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c326)
Location: lib/scatterlist.c:266
Inline: False
```
**Symbols:**

```
ffffffe00045c326-ffffffe00045c43c: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151aa30)
Location: lib/scatterlist.c:266
Inline: False
```
**Symbols:**

```
ffffffff8151aa30-ffffffff8151ab98: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150ad20)
Location: lib/scatterlist.c:266
Inline: False
```
**Symbols:**

```
ffffffff8150ad20-ffffffff8150ae88: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81516ac0)
Location: lib/scatterlist.c:266
Inline: False
```
**Symbols:**

```
ffffffff81516ac0-ffffffff81516c28: __sg_alloc_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sg_alloc_table(struct sg_table *table, unsigned int nents, unsigned int max_ents, struct scatterlist *first_chunk, unsigned int nents_first_chunk, gfp_t gfp_mask, sg_alloc_fn *alloc_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530250)
Location: lib/scatterlist.c:266
Inline: False
```
**Symbols:**

```
ffffffff81530250-ffffffff815303b8: __sg_alloc_table (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nents_first_chunk</code>
</li>
<li>
<b>Param reordered. </b>
<code>table, nents, max_ents, first_chunk, gfp_mask, alloc_fn</code> ➡️ <code>table, nents, max_ents, first_chunk, nents_first_chunk, gfp_mask, alloc_fn</code>
</li>
</ul>
</details>
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
