# Function: <code>block_read_full_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81244c60)
Location: fs/buffer.c:2182
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81244c60-ffffffff81244f85: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126d820)
Location: fs/buffer.c:2238
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8126d820-ffffffff8126db5a: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81280a70)
Location: fs/buffer.c:2279
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81280a70-ffffffff81280da9: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128e330)
Location: fs/buffer.c:2276
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8128e330-ffffffff8128e685: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b0f40)
Location: fs/buffer.c:2236
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812b0f40-ffffffff812b127f: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d8db0)
Location: fs/buffer.c:2207
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812d8db0-ffffffff812d90de: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ee280)
Location: fs/buffer.c:2219
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812ee280-ffffffff812ee5b0: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2216
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81311d33-ffffffff81311d78: block_read_full_page.cold (STB_LOCAL)
ffffffff8130fa50-ffffffff8130fdae: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813229d0)
Location: fs/buffer.c:2216
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813229d0-ffffffff81322d71: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135c0a0)
Location: fs/buffer.c:2260
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8135c0a0-ffffffff8135c450: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813697b0)
Location: fs/buffer.c:2259
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813697b0-ffffffff81369adc: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813705c0)
Location: fs/buffer.c:2280
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813705c0-ffffffff813708ec: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2259
Inline: False
Direct callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - block/fops.c:blkdev_readpage
```
**Symbols:**

```
ffffffff81cc45a9-ffffffff81cc461d: block_read_full_page.cold (STB_LOCAL)
ffffffff813bf140-ffffffff813bf51f: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103db9d0)
Location: fs/buffer.c:2216
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffff8000103db9d0-ffff8000103dbe34: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b4d44)
Location: fs/buffer.c:2216
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
c05b4d44-c05b51a8: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e0d80)
Location: fs/buffer.c:2216
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
c0000000004e0d80-c0000000004e1240: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe00029406a)
Location: fs/buffer.c:2216
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffe00029406a-ffffffe0002943c4: block_read_full_page (STB_GLOBAL)
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
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131afb0)
Location: fs/buffer.c:2216
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8131afb0-ffffffff8131b351: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130bb50)
Location: fs/buffer.c:2216
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8130bb50-ffffffff8130bef1: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318a80)
Location: fs/buffer.c:2216
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81318a80-ffffffff81318e21: block_read_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int block_read_full_page(struct page *page, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132a6a0)
Location: fs/buffer.c:2216
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8132a6a0-ffffffff8132aa55: block_read_full_page (STB_GLOBAL)
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
