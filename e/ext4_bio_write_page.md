# Function: <code>ext4_bio_write_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8129fe10)
Location: fs/ext4/page-io.c:416
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff8129fe10-ffffffff812a023f: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812ce700)
Location: fs/ext4/page-io.c:400
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff812ce700-ffffffff812cebce: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812e44e0)
Location: fs/ext4/page-io.c:400
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff812e44e0-ffffffff812e49d2: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8131e1c0)
Location: fs/ext4/page-io.c:411
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff8131e1c0-ffffffff8131e6b5: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813427d0)
Location: fs/ext4/page-io.c:412
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813427d0-ffffffff81342cfe: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:412
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81370b5f-ffffffff81370b7a: ext4_bio_write_page.cold.20 (STB_LOCAL)
ffffffff81370650-ffffffff81370b30: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:412
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81388ff5-ffffffff81389010: ext4_bio_write_page.cold.20 (STB_LOCAL)
ffffffff81388ae0-ffffffff81388fc6: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:404
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813b313d-ffffffff813b3160: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff813b2bd0-ffffffff813b30e3: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:404
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813cc1ad-ffffffff813cc1d0: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff813cbc30-ffffffff813cc18c: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:436
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff8141828f-ffffffff814182aa: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff81417d90-ffffffff8141826e: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:435
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81bec532-ffffffff81bec54d: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff8142b890-ffffffff8142bd02: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:435
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81bde5e4-ffffffff81bde5ff: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff814324b0-ffffffff814329ce: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:435
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81ccce39-ffffffff81ccce78: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff81485d70-ffffffff81486296: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:431
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81e7fd16-ffffffff81e7fd55: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff81509320-ffffffff81509964: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:431
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff820701b5-ffffffff820701df: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff815a3f00-ffffffff815a45c7: ext4_bio_write_page (STB_GLOBAL)
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
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffff8000104a3db0)
Location: fs/ext4/page-io.c:404
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffff8000104a3db0-ffff8000104a43ac: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (c0665c60)
Location: fs/ext4/page-io.c:404
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
c0665c60-c06661d0: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (c0000000005d0e60)
Location: fs/ext4/page-io.c:404
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
c0000000005d0e60-c0000000005d1548: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffe00032530c)
Location: fs/ext4/page-io.c:404
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffe00032530c-ffffffe0003257d4: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:404
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813c478d-ffffffff813c47b0: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff813c4210-ffffffff813c476c: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:404
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813b520d-ffffffff813b5230: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff813b4c90-ffffffff813b51ec: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:404
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813c1c1d-ffffffff813c1c40: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff813c16a0-ffffffff813c1bfc: ext4_bio_write_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ext4_bio_write_page(struct ext4_io_submit *io, struct page *page, int len, struct writeback_control *wbc, bool keep_towrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:404
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813d6d96-ffffffff813d6db9: ext4_bio_write_page.cold (STB_LOCAL)
ffffffff813d6800-ffffffff813d6d75: ext4_bio_write_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct writeback_control *wbc</code>
</li>
<li>
<b>Param reordered. </b>
<code>io, page, len, wbc, keep_towrite</code> ➡️ <code>io, page, len, keep_towrite</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>bool keep_towrite</code>
</li>
</ul>
</details>
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
