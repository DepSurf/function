# Function: <code>replace_page_cache_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e710)
Location: mm/filemap.c:516
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff8118e710-ffffffff8118e84e: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a2260)
Location: mm/filemap.c:597
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811a2260-ffffffff811a23d4: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b20b0)
Location: mm/filemap.c:562
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811b20b0-ffffffff811b2218: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b8d70)
Location: mm/filemap.c:680
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811b8d70-ffffffff811b8e98: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd360)
Location: mm/filemap.c:781
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811cd360-ffffffff811cd4c6: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eeeb0)
Location: mm/filemap.c:781
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811eeeb0-ffffffff811ef01c: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fd2b0)
Location: mm/filemap.c:757
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811fd2b0-ffffffff811fd494: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81215710)
Location: mm/filemap.c:802
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81215710-ffffffff812158f8: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81222ac0)
Location: mm/filemap.c:811
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81222ac0-ffffffff81222ca8: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81250210)
Location: mm/filemap.c:789
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81250210-ffffffff812505d6: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81259e70)
Location: mm/filemap.c:790
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81259e70-ffffffff8125a066: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void replace_page_cache_page(struct page *old, struct page *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125e420)
Location: mm/filemap.c:818
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8125e420-ffffffff8125e614: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void replace_page_cache_page(struct page *old, struct page *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129ad30)
Location: mm/filemap.c:836
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8129ad30-ffffffff8129af23: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void replace_page_cache_page(struct page *old, struct page *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f0ad0)
Location: mm/filemap.c:805
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff812f0ad0-ffffffff812f0e05: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b00c8)
Location: mm/filemap.c:811
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffff8000102b00c8-ffff8000102b034c: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dc9e0)
Location: mm/filemap.c:811
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
c04dc9e0-c04dcba0: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000365400)
Location: mm/filemap.c:811
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
c000000000365400-c0000000003656e4: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d557c)
Location: mm/filemap.c:811
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffe0001d557c-ffffffe0001d571a: replace_page_cache_page (STB_GLOBAL)
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
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121b110)
Location: mm/filemap.c:811
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8121b110-ffffffff8121b2f8: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120e300)
Location: mm/filemap.c:811
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8120e300-ffffffff8120e4e8: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218eb0)
Location: mm/filemap.c:811
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81218eb0-ffffffff81219098: replace_page_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int replace_page_cache_page(struct page *old, struct page *new, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81227fa0)
Location: mm/filemap.c:811
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81227fa0-ffffffff81228188: replace_page_cache_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
