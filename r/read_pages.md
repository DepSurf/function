# Function: <code>read_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8119bf3d)
Location: mm/readahead.c:111
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811b10ec)
Location: mm/readahead.c:111
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
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
In mm/readahead.c (ffffffff811c16ca)
Location: mm/readahead.c:111
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
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
In mm/readahead.c (ffffffff811c9997)
Location: mm/readahead.c:111
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
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
In mm/readahead.c (ffffffff811de81a)
Location: mm/readahead.c:111
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811ffd70)
Location: mm/readahead.c:111
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff811ffd70-ffffffff811ffeee: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81212640)
Location: mm/readahead.c:113
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff81212640-ffffffff812127be: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81222010)
Location: mm/readahead.c:116
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff81222010-ffffffff812221a4: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8122fac0)
Location: mm/readahead.c:116
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff8122fac0-ffffffff8122fc54: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void read_pages(struct readahead_control *rac, struct list_head *pages, bool skip_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8125cb70)
Location: mm/readahead.c:117
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_readahead_unbounded
  - mm/readahead.c:page_cache_readahead_unbounded
```
**Symbols:**

```
ffffffff8125cb70-ffffffff8125cde6: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void read_pages(struct readahead_control *rac, struct list_head *pages, bool skip_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81266ef0)
Location: mm/readahead.c:117
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff81266ef0-ffffffff81267160: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void read_pages(struct readahead_control *rac, struct list_head *pages, bool skip_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126bb30)
Location: mm/readahead.c:117
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff8126bb30-ffffffff8126bda2: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void read_pages(struct readahead_control *rac, struct list_head *pages, bool skip_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812a8800)
Location: mm/readahead.c:117
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff812a8800-ffffffff812a8a6f: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void read_pages(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81301440)
Location: mm/readahead.c:146
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff81301440-ffffffff8130172f: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void read_pages(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/readahead.c (0)
Location: mm/readahead.c:147
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff8136bb00-ffffffff8136bd97: read_pages (STB_LOCAL)
ffffffff820624a7-ffffffff820624d1: read_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void read_pages(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/readahead.c (0)
Location: mm/readahead.c:146
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff8139dd90-ffffffff8139e024: read_pages (STB_LOCAL)
ffffffff820e1c82-ffffffff820e1cac: read_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void read_pages(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/readahead.c (0)
Location: mm/readahead.c:146
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff813c7a40-ffffffff813c7ccb: read_pages (STB_LOCAL)
ffffffff821be6a7-ffffffff821be6d1: read_pages.cold (STB_LOCAL)
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
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffff8000102bf098)
Location: mm/readahead.c:116
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffff8000102bf098-ffff8000102bf218: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c04eadc4)
Location: mm/readahead.c:116
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
c04eadc4-c04eaf2c: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c000000000377ed0)
Location: mm/readahead.c:116
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
c000000000377ed0-c000000000378148: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffe0001e1552)
Location: mm/readahead.c:116
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffe0001e1552-ffffffe0001e165a: read_pages (STB_LOCAL)
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
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81228110)
Location: mm/readahead.c:116
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff81228110-ffffffff812282a4: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8121b250)
Location: mm/readahead.c:116
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff8121b250-ffffffff8121b3e4: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81225eb0)
Location: mm/readahead.c:116
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff81225eb0-ffffffff81226044: read_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int read_pages(struct address_space *mapping, struct file *filp, struct list_head *pages, unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812351b0)
Location: mm/readahead.c:116
Inline: False
Direct callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff812351b0-ffffffff81235344: read_pages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct readahead_control *rac</code>
</li>
<li>
<b>Param added. </b>
<code>bool skip_page</code>
</li>
<li>
<b>Param removed. </b>
<code>struct address_space *mapping</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *filp</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_pages</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, filp, pages, nr_pages, gfp</code> ➡️ <code>rac, pages, skip_page</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct list_head *pages</code>
</li>
<li>
<b>Param removed. </b>
<code>bool skip_page</code>
</li>
</ul>
</details>
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
