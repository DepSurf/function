# Function: <code>bdev_read_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81247790)
Location: fs/block_dev.c:389
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81247790-ffffffff81247833: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8126ff30)
Location: fs/block_dev.c:408
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8126ff30-ffffffff8126ffdc: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81283130)
Location: fs/block_dev.c:660
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81283130-ffffffff812831dc: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812908f0)
Location: fs/block_dev.c:668
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812908f0-ffffffff8129098f: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b35b0)
Location: fs/block_dev.c:656
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812b35b0-ffffffff812b3654: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812db480)
Location: fs/block_dev.c:657
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812db480-ffffffff812db524: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f09d0)
Location: fs/block_dev.c:694
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812f09d0-ffffffff812f0a74: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81312350)
Location: fs/block_dev.c:699
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81312350-ffffffff813123ee: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813252a0)
Location: fs/block_dev.c:699
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff813252a0-ffffffff8132533e: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813617c0)
Location: fs/block_dev.c:697
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff813617c0-ffffffff8136185e: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e560)
Location: fs/block_dev.c:724
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8136e560-ffffffff8136e5f2: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374e70)
Location: fs/block_dev.c:728
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81374e70-ffffffff81374f02: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4850)
Location: block/bdev.c:320
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff815c4850-ffffffff815c48e2: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166f280)
Location: block/bdev.c:324
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8166f280-ffffffff8166f320: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a5f0)
Location: block/bdev.c:323
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8172a5f0-ffffffff8172a690: bdev_read_page (STB_GLOBAL)
```
</details>
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
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103df8c0)
Location: fs/block_dev.c:699
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffff8000103df8c0-ffff8000103df96c: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b7b84)
Location: fs/block_dev.c:699
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
c05b7b84-c05b7c38: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e4800)
Location: fs/block_dev.c:699
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
c0000000004e4800-c0000000004e490c: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002966ac)
Location: fs/block_dev.c:699
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffe0002966ac-ffffffe000296730: bdev_read_page (STB_GLOBAL)
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
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d880)
Location: fs/block_dev.c:699
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8131d880-ffffffff8131d91e: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130e420)
Location: fs/block_dev.c:699
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8130e420-ffffffff8130e4be: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131b350)
Location: fs/block_dev.c:699
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8131b350-ffffffff8131b3ee: bdev_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bdev_read_page(struct block_device *bdev, sector_t sector, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132cff0)
Location: fs/block_dev.c:699
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8132cff0-ffffffff8132d08e: bdev_read_page (STB_GLOBAL)
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
