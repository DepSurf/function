# Function: <code>lz4_uncompress</code>

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
In lib/lz4/lz4_decompress.c (ffffffff8140e6d1)
Location: lib/lz4/lz4_decompress.c:55
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:lz4_decompress
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff81325e50)
Location: fs/squashfs/lz4_wrapper.c:93
Inline: False
```
```
In lib/lz4/lz4_decompress.c (ffffffff81456400)
Location: lib/lz4/lz4_decompress.c:55
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:lz4_decompress
```
**Symbols:**

```
ffffffff81325e50-ffffffff81326036: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff8133bc00)
Location: fs/squashfs/lz4_wrapper.c:93
Inline: False
```
```
In lib/lz4/lz4_decompress.c (ffffffff81474dc0)
Location: lib/lz4/lz4_decompress.c:55
Inline: True
Inline callers:
  - lib/lz4/lz4_decompress.c:lz4_decompress
```
**Symbols:**

```
ffffffff8133bc00-ffffffff8133bde6: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff81350720)
Location: fs/squashfs/lz4_wrapper.c:93
Inline: False
```
**Symbols:**

```
ffffffff81350720-ffffffff813508d8: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff81374eb0)
Location: fs/squashfs/lz4_wrapper.c:93
Inline: False
```
**Symbols:**

```
ffffffff81374eb0-ffffffff81375082: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff813a38a0)
Location: fs/squashfs/lz4_wrapper.c:93
Inline: False
```
**Symbols:**

```
ffffffff813a38a0-ffffffff813a3a6f: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff813bc6a0)
Location: fs/squashfs/lz4_wrapper.c:93
Inline: False
```
**Symbols:**

```
ffffffff813bc6a0-ffffffff813bc86f: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff813e6f50)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff813e6f50-ffffffff813e710f: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff81400fd0)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff81400fd0-ffffffff8140118f: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff8144ea20)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff8144ea20-ffffffff8144ec7d: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff8146b010)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff8146b010-ffffffff8146b26d: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff814706d0)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff814706d0-ffffffff8147092b: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff814c7140)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff814c7140-ffffffff814c739b: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff815524e0)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff815524e0-ffffffff8155276c: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff815f3a40)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff815f3a40-ffffffff815f3ce8: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff8162bb30)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff8162bb30-ffffffff8162bdd8: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff81664f00)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff81664f00-ffffffff816651a8: lz4_uncompress (STB_LOCAL)
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
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffff8000104df280)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffff8000104df280-ffff8000104df408: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (c06a0c18)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
c06a0c18-c06a0d54: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (c00000000061b370)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
c00000000061b370-c00000000061b55c: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffe000353864)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffe000353864-ffffffe000353988: lz4_uncompress (STB_LOCAL)
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
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff813f95b0)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff813f95b0-ffffffff813f976f: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff813ea030)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff813ea030-ffffffff813ea1ef: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff813f6930)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff813f6930-ffffffff813f6aef: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int lz4_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lz4_wrapper.c (ffffffff8140c5c0)
Location: fs/squashfs/lz4_wrapper.c:91
Inline: False
```
**Symbols:**

```
ffffffff8140c5c0-ffffffff8140c77f: lz4_uncompress (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bio *bio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct buffer_head **bh</code>
</li>
<li>
<b>Param removed. </b>
<code>int b</code>
</li>
<li>
<b>Param reordered. </b>
<code>msblk, strm, bh, b, offset, length, output</code> ➡️ <code>msblk, strm, bio, offset, length, output</code>
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
