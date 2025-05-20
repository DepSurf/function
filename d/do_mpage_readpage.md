# Function: <code>do_mpage_readpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct bio *bio, struct page *page, unsigned int nr_pages, sector_t *last_block_in_bio, struct buffer_head *map_bh, long unsigned int *first_logical_block, get_block_t *get_block, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff8124df20)
Location: fs/mpage.c:140
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:mpage_readpage
```
**Symbols:**

```
ffffffff8124df20-ffffffff8124e6bc: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct bio *bio, struct page *page, unsigned int nr_pages, sector_t *last_block_in_bio, struct buffer_head *map_bh, long unsigned int *first_logical_block, get_block_t *get_block, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81276670)
Location: fs/mpage.c:144
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff81276670-ffffffff81276df5: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct bio *bio, struct page *page, unsigned int nr_pages, sector_t *last_block_in_bio, struct buffer_head *map_bh, long unsigned int *first_logical_block, get_block_t *get_block, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff8128a380)
Location: fs/mpage.c:144
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff8128a380-ffffffff8128aac2: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct bio *bio, struct page *page, unsigned int nr_pages, sector_t *last_block_in_bio, struct buffer_head *map_bh, long unsigned int *first_logical_block, get_block_t *get_block, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff812971a0)
Location: fs/mpage.c:145
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff812971a0-ffffffff81297917: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct bio *bio, struct page *page, unsigned int nr_pages, sector_t *last_block_in_bio, struct buffer_head *map_bh, long unsigned int *first_logical_block, get_block_t *get_block, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff812ba410)
Location: fs/mpage.c:146
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff812ba410-ffffffff812bab9e: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct bio *bio, struct page *page, unsigned int nr_pages, sector_t *last_block_in_bio, struct buffer_head *map_bh, long unsigned int *first_logical_block, get_block_t *get_block, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff812e2f70)
Location: fs/mpage.c:146
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff812e2f70-ffffffff812e3711: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff812f7bd0)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff812f7bd0-ffffffff812f83ff: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81318210)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff81318210-ffffffff81318a27: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff8132b070)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff8132b070-ffffffff8132b86e: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81364d20)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
```
**Symbols:**

```
ffffffff81364d20-ffffffff813654ec: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81371ca0)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
```
**Symbols:**

```
ffffffff81371ca0-ffffffff813723b4: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81377dc0)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
```
**Symbols:**

```
ffffffff81377dc0-ffffffff81378492: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mpage.c (0)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
```
**Symbols:**

```
ffffffff813c4480-ffffffff813c4d7a: do_mpage_readpage (STB_LOCAL)
ffffffff81cc5039-ffffffff81cc52ce: do_mpage_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mpage.c (0)
Location: fs/mpage.c:131
Inline: False
Direct callers:
  - fs/mpage.c:mpage_read_folio
  - fs/mpage.c:mpage_readahead
```
**Symbols:**

```
ffffffff8144b250-ffffffff8144bbbf: do_mpage_readpage (STB_LOCAL)
ffffffff81e77a42-ffffffff81e77ce7: do_mpage_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mpage.c (0)
Location: fs/mpage.c:133
Inline: False
Direct callers:
  - fs/mpage.c:mpage_read_folio
  - fs/mpage.c:mpage_readahead
```
**Symbols:**

```
ffffffff814d9990-ffffffff814da1dd: do_mpage_readpage (STB_LOCAL)
ffffffff82069a8b-ffffffff82069d2d: do_mpage_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mpage.c (0)
Location: fs/mpage.c:159
Inline: False
Direct callers:
  - fs/mpage.c:mpage_read_folio
  - fs/mpage.c:mpage_readahead
```
**Symbols:**

```
ffffffff8150d900-ffffffff8150e112: do_mpage_readpage (STB_LOCAL)
ffffffff820e8da1-ffffffff820e9050: do_mpage_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mpage.c (0)
Location: fs/mpage.c:158
Inline: False
Direct callers:
  - fs/mpage.c:mpage_read_folio
  - fs/mpage.c:mpage_readahead
```
**Symbols:**

```
ffffffff81542610-ffffffff81542bf4: do_mpage_readpage (STB_LOCAL)
ffffffff821c5a33-ffffffff821c5c7d: do_mpage_readpage.cold (STB_LOCAL)
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
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffff8000103e66a8)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffff8000103e66a8-ffff8000103e6e0c: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (c05be29c)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
c05be29c-c05beb48: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (c0000000004ec9b0)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
c0000000004ec9b0-c0000000004ed2d8: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffe00029b9b8)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffe00029b9b8-ffffffe00029bfac: do_mpage_readpage (STB_LOCAL)
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
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81323650)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff81323650-ffffffff81323e4e: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813141f0)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff813141f0-ffffffff813149ee: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81321120)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff81321120-ffffffff8132191e: do_mpage_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bio *do_mpage_readpage(struct mpage_readpage_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81332e60)
Location: fs/mpage.c:156
Inline: False
Direct callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
**Symbols:**

```
ffffffff81332e60-ffffffff8133367c: do_mpage_readpage (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mpage_readpage_args *args</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bio *bio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_pages</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t *last_block_in_bio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct buffer_head *map_bh</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *first_logical_block</code>
</li>
<li>
<b>Param removed. </b>
<code>get_block_t *get_block</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
