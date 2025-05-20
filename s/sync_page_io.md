# Function: <code>sync_page_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int rw, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81690d80)
Location: drivers/md/md.c:760
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81690d80-ffffffff81690e7c: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f1aa0)
Location: drivers/md/md.c:758
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff816f1aa0-ffffffff816f1c41: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81723350)
Location: drivers/md/md.c:788
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81723350-ffffffff8172345a: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8173a7d0)
Location: drivers/md/md.c:800
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff8173a7d0-ffffffff8173a8ce: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817acdf0)
Location: drivers/md/md.c:835
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff817acdf0-ffffffff817acf36: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f2f10)
Location: drivers/md/md.c:850
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff817f2f10-ffffffff817f3056: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8181eef0)
Location: drivers/md/md.c:843
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff8181eef0-ffffffff8181f039: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81861360)
Location: drivers/md/md.c:904
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81861360-ffffffff818614ce: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81892f90)
Location: drivers/md/md.c:916
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81892f90-ffffffff818930fe: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81961610)
Location: drivers/md/md.c:1042
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81961610-ffffffff819617c0: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81967f40)
Location: drivers/md/md.c:1031
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81967f40-ffffffff819680f6: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8194b4d0)
Location: drivers/md/md.c:990
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff8194b4d0-ffffffff8194b69e: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f0690)
Location: drivers/md/md.c:991
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff819f0690-ffffffff819f085e: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b59840)
Location: drivers/md/md.c:995
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81b59840-ffffffff81b5999e: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, blk_opf_t opf, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf0870)
Location: drivers/md/md.c:986
Inline: False
Direct callers:
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81cf0870-ffffffff81cf09b2: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, blk_opf_t opf, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d597f0)
Location: drivers/md/md.c:962
Inline: False
Direct callers:
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81d597f0-ffffffff81d59932: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, blk_opf_t opf, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e108b0)
Location: drivers/md/md.c:1074
Inline: False
Direct callers:
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81e108b0-ffffffff81e109f2: sync_page_io (STB_GLOBAL)
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
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae4620)
Location: drivers/md/md.c:916
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffff800010ae4620-ffff800010ae47a0: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc7c50)
Location: drivers/md/md.c:916
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
c0bc7c50-c0bc7de0: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd04b0)
Location: drivers/md/md.c:916
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
c000000000bd04b0-c000000000bd0690: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006db828)
Location: drivers/md/md.c:916
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffe0006db828-ffffffe0006db970: sync_page_io (STB_GLOBAL)
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
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81838e10)
Location: drivers/md/md.c:916
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81838e10-ffffffff81838f7e: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81800480)
Location: drivers/md/md.c:916
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81800480-ffffffff818005ee: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81888440)
Location: drivers/md/md.c:916
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff81888440-ffffffff818885ae: sync_page_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sync_page_io(struct md_rdev *rdev, sector_t sector, int size, struct page *page, int op, int op_flags, bool metadata_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a59e0)
Location: drivers/md/md.c:916
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:read_sb_page
```
**Symbols:**

```
ffffffff818a59e0-ffffffff818a5b4e: sync_page_io (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rdev, sector, size, page, rw, metadata_op</code> ➡️ <code>rdev, sector, size, page, op, op_flags, metadata_op</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>rdev, sector, size, page, op, op_flags, metadata_op</code> ➡️ <code>rdev, sector, size, page, opf, metadata_op</code>
</li>
</ul>
</details>
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
