# Function: <code>bdev_write_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81247840)
Location: fs/block_dev.c:426
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81247840-ffffffff81247919: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8126ffe0)
Location: fs/block_dev.c:445
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8126ffe0-ffffffff812700bc: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812831e0)
Location: fs/block_dev.c:697
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff812831e0-ffffffff812832bc: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81290990)
Location: fs/block_dev.c:705
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81290990-ffffffff81290a69: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b3660)
Location: fs/block_dev.c:693
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff812b3660-ffffffff812b3746: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812db530)
Location: fs/block_dev.c:694
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff812db530-ffffffff812db60e: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f0a80)
Location: fs/block_dev.c:732
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff812f0a80-ffffffff812f0b5e: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813123f0)
Location: fs/block_dev.c:737
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff813123f0-ffffffff813124cc: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81325340)
Location: fs/block_dev.c:737
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81325340-ffffffff8132541c: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81361860)
Location: fs/block_dev.c:734
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81361860-ffffffff8136193c: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e600)
Location: fs/block_dev.c:761
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8136e600-ffffffff8136e6cc: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374f10)
Location: fs/block_dev.c:765
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81374f10-ffffffff81374fdc: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c48f0)
Location: block/bdev.c:357
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff815c48f0-ffffffff815c49bc: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166f320)
Location: block/bdev.c:361
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8166f320-ffffffff8166f406: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a6a0)
Location: block/bdev.c:360
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8172a6a0-ffffffff8172a786: bdev_write_page (STB_GLOBAL)
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
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103df970)
Location: fs/block_dev.c:737
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffff8000103df970-ffff8000103dfa5c: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b7c38)
Location: fs/block_dev.c:737
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
c05b7c38-c05b7d24: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e4910)
Location: fs/block_dev.c:737
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
c0000000004e4910-c0000000004e4a5c: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000296730)
Location: fs/block_dev.c:737
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffe000296730-ffffffe0002967ea: bdev_write_page (STB_GLOBAL)
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
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d920)
Location: fs/block_dev.c:737
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8131d920-ffffffff8131d9fc: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130e4c0)
Location: fs/block_dev.c:737
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8130e4c0-ffffffff8130e59c: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131b3f0)
Location: fs/block_dev.c:737
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8131b3f0-ffffffff8131b4cc: bdev_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bdev_write_page(struct block_device *bdev, sector_t sector, struct page *page, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132d090)
Location: fs/block_dev.c:737
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8132d090-ffffffff8132d16c: bdev_write_page (STB_GLOBAL)
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
