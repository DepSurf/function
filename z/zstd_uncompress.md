# Function: <code>zstd_uncompress</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff813759e0)
Location: fs/squashfs/zstd_wrapper.c:70
Inline: False
```
**Symbols:**

```
ffffffff813759e0-ffffffff81375c28: zstd_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:70
Inline: False
```
**Symbols:**

```
ffffffff813a43f0-ffffffff813a4623: zstd_uncompress (STB_LOCAL)
ffffffff813a46d2-ffffffff813a46e5: zstd_uncompress.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:70
Inline: False
```
**Symbols:**

```
ffffffff813bd1f0-ffffffff813bd423: zstd_uncompress (STB_LOCAL)
ffffffff813bd4d2-ffffffff813bd4e5: zstd_uncompress.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff813e7ab0-ffffffff813e7ce2: zstd_uncompress (STB_LOCAL)
ffffffff813e7d93-ffffffff813e7da6: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff81401b30-ffffffff81401d62: zstd_uncompress (STB_LOCAL)
ffffffff81401e13-ffffffff81401e26: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff8144f720-ffffffff8144f955: zstd_uncompress (STB_LOCAL)
ffffffff8144fa03-ffffffff8144fa40: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff8146bc80-ffffffff8146beb5: zstd_uncompress (STB_LOCAL)
ffffffff81bed6a9-ffffffff81bed6e6: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff81471310-ffffffff81471541: zstd_uncompress (STB_LOCAL)
ffffffff81bdf7ac-ffffffff81bdf7e9: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff814c7da0-ffffffff814c7fd1: zstd_uncompress (STB_LOCAL)
ffffffff81ccf35d-ffffffff81ccf39a: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff81553220-ffffffff81553495: zstd_uncompress (STB_LOCAL)
ffffffff81e8240a-ffffffff81e8241b: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff815f4920)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff815f4920-ffffffff815f4be8: zstd_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff8162c9c0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff8162c9c0-ffffffff8162cc67: zstd_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff81665e80)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff81665e80-ffffffff81666127: zstd_uncompress (STB_LOCAL)
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
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffff8000104dfe70)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffff8000104dfe70-ffff8000104e00fc: zstd_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (c06a16d4)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
c06a16d4-c06a1964: zstd_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (c00000000061c370)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
c00000000061c370-c00000000061c734: zstd_uncompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffe00035419a)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffe00035419a-ffffffe000354370: zstd_uncompress (STB_LOCAL)
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
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff813fa110-ffffffff813fa342: zstd_uncompress (STB_LOCAL)
ffffffff813fa3f3-ffffffff813fa406: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff813eab90-ffffffff813eadc2: zstd_uncompress (STB_LOCAL)
ffffffff813eae73-ffffffff813eae86: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff813f7490-ffffffff813f76c2: zstd_uncompress (STB_LOCAL)
ffffffff813f7773-ffffffff813f7786: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int zstd_uncompress(struct squashfs_sb_info *msblk, void *strm, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:61
Inline: False
```
**Symbols:**

```
ffffffff8140d120-ffffffff8140d352: zstd_uncompress (STB_LOCAL)
ffffffff8140d403-ffffffff8140d416: zstd_uncompress.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
