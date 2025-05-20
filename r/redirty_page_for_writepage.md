# Function: <code>redirty_page_for_writepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8119abf0)
Location: mm/page-writeback.c:2523
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8119abf0-ffffffff8119ac1f: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811af510)
Location: mm/page-writeback.c:2567
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff811af510-ffffffff811af53f: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bfbd0)
Location: mm/page-writeback.c:2534
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff811bfbd0-ffffffff811bfbff: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c7da0)
Location: mm/page-writeback.c:2537
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff811c7da0-ffffffff811c7dcf: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dcbe0)
Location: mm/page-writeback.c:2520
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff811dcbe0-ffffffff811dcc0f: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fcb40)
Location: mm/page-writeback.c:2521
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff811fcb40-ffffffff811fcb6f: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81210900)
Location: mm/page-writeback.c:2515
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81210900-ffffffff8121092f: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812216b0)
Location: mm/page-writeback.c:2523
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812216b0-ffffffff812216e1: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122f160)
Location: mm/page-writeback.c:2527
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8122f160-ffffffff8122f191: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8125c220)
Location: mm/page-writeback.c:2537
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8125c220-ffffffff8125c251: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812665f0)
Location: mm/page-writeback.c:2535
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
**Symbols:**

```
ffffffff812665f0-ffffffff81266621: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8126b0f0)
Location: mm/page-writeback.c:2535
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
**Symbols:**

```
ffffffff8126b0f0-ffffffff8126b121: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a7fb0)
Location: mm/page-writeback.c:2573
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
**Symbols:**

```
ffffffff812a7fb0-ffffffff812a7fe1: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300f60)
Location: mm/folio-compat.c:100
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/super.c:ext4_journalled_writepage_callback
  - fs/fuse/file.c:fuse_writepage
```
**Symbols:**

```
ffffffff81300f60-ffffffff81300fbb: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b790)
Location: mm/folio-compat.c:72
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/super.c:ext4_journalled_writepage_callback
  - fs/fuse/file.c:fuse_writepage
```
**Symbols:**

```
ffffffff8136b790-ffffffff8136b7eb: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139d9a0)
Location: mm/folio-compat.c:73
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage
```
**Symbols:**

```
ffffffff8139d9a0-ffffffff8139da0a: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7710)
Location: mm/folio-compat.c:73
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage
```
**Symbols:**

```
ffffffff813c7710-ffffffff813c7777: redirty_page_for_writepage (STB_GLOBAL)
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
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102be498)
Location: mm/page-writeback.c:2527
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffff8000102be498-ffff8000102be4e4: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04ea6f4)
Location: mm/page-writeback.c:2527
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
c04ea6f4-c04ea738: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c000000000377410)
Location: mm/page-writeback.c:2527
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
c000000000377410-c000000000377474: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001e0e94)
Location: mm/page-writeback.c:2527
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffe0001e0e94-ffffffe0001e0edc: redirty_page_for_writepage (STB_GLOBAL)
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
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812277b0)
Location: mm/page-writeback.c:2527
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812277b0-ffffffff812277e1: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121a920)
Location: mm/page-writeback.c:2527
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8121a920-ffffffff8121a951: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81225550)
Location: mm/page-writeback.c:2527
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81225550-ffffffff81225581: redirty_page_for_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int redirty_page_for_writepage(struct writeback_control *wbc, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81234850)
Location: mm/page-writeback.c:2527
Inline: False
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81234850-ffffffff81234881: redirty_page_for_writepage (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
