# Function: <code>squashfs_decompress</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff81325760)
Location: fs/squashfs/decompressor_multi_percpu.c:77
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81325760-ffffffff813257c0: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_single.c (ffffffff8133b4e0)
Location: fs/squashfs/decompressor_single.c:64
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8133b4e0-ffffffff8133b57d: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_single.c (ffffffff8134fff0)
Location: fs/squashfs/decompressor_single.c:64
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8134fff0-ffffffff8135008c: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_single.c (ffffffff81374770)
Location: fs/squashfs/decompressor_single.c:64
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81374770-ffffffff81374811: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:64
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff813a3220-ffffffff813a3238: squashfs_decompress.cold.0 (STB_LOCAL)
ffffffff813a3180-ffffffff813a320f: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:64
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff813bc020-ffffffff813bc038: squashfs_decompress.cold.0 (STB_LOCAL)
ffffffff813bbf80-ffffffff813bc00f: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff813e68d0-ffffffff813e68e8: squashfs_decompress.cold (STB_LOCAL)
ffffffff813e6820-ffffffff813e68b1: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81400950-ffffffff81400968: squashfs_decompress.cold (STB_LOCAL)
ffffffff814008a0-ffffffff81400931: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8144e350-ffffffff8144e368: squashfs_decompress.cold (STB_LOCAL)
ffffffff8144e2b0-ffffffff8144e333: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81bed609-ffffffff81bed621: squashfs_decompress.cold (STB_LOCAL)
ffffffff8146a850-ffffffff8146a8d3: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81bdf70b-ffffffff81bdf723: squashfs_decompress.cold (STB_LOCAL)
ffffffff8146ff10-ffffffff8146ff93: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81ccf23a-ffffffff81ccf252: squashfs_decompress.cold (STB_LOCAL)
ffffffff814c6980-ffffffff814c6a03: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: fs/squashfs/decompressor_multi_percpu.c:78
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81e822dd-ffffffff81e822f5: squashfs_decompress.cold (STB_LOCAL)
ffffffff81551c70-ffffffff81551ce8: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_single.c (ffffffff815f28c0)
Location: fs/squashfs/decompressor_single.c:62
Inline: True
```
```
In fs/squashfs/decompressor_multi.c (ffffffff815f2aa0)
Location: fs/squashfs/decompressor_multi.c:182
Inline: False
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff815f2e60)
Location: fs/squashfs/decompressor_multi_percpu.c:78
Inline: False
```
**Symbols:**

```
ffffffff815f28c0-ffffffff815f2962: squashfs_decompress (STB_LOCAL)
ffffffff815f2aa0-ffffffff815f2d02: squashfs_decompress (STB_LOCAL)
ffffffff815f2e60-ffffffff815f2f01: squashfs_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_single.c (ffffffff8162a9b0)
Location: fs/squashfs/decompressor_single.c:62
Inline: True
```
```
In fs/squashfs/decompressor_multi.c (ffffffff8162ab90)
Location: fs/squashfs/decompressor_multi.c:182
Inline: False
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff8162af50)
Location: fs/squashfs/decompressor_multi_percpu.c:77
Inline: False
```
**Symbols:**

```
ffffffff8162a9b0-ffffffff8162aa52: squashfs_decompress (STB_LOCAL)
ffffffff8162ab90-ffffffff8162adf2: squashfs_decompress (STB_LOCAL)
ffffffff8162af50-ffffffff8162aff1: squashfs_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct bio *bio, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_single.c (ffffffff81663d00)
Location: fs/squashfs/decompressor_single.c:62
Inline: True
```
```
In fs/squashfs/decompressor_multi.c (ffffffff81663ee0)
Location: fs/squashfs/decompressor_multi.c:182
Inline: False
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff81664320)
Location: fs/squashfs/decompressor_multi_percpu.c:77
Inline: False
```
**Symbols:**

```
ffffffff81663d00-ffffffff81663da2: squashfs_decompress (STB_LOCAL)
ffffffff81663ee0-ffffffff81664171: squashfs_decompress (STB_LOCAL)
ffffffff81664320-ffffffff816643c1: squashfs_decompress (STB_LOCAL)
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
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_single.c (ffff8000104de9a8)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffff8000104de9a8-ffff8000104dea5c: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_single.c (c06a0440)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
c06a0440-c06a04e0: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_single.c (c00000000061a910)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
c00000000061a910-c00000000061aa0c: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/decompressor_single.c (ffffffe0003531ca)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffe0003531ca-ffffffe000353262: squashfs_decompress (STB_GLOBAL)
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
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff813f8f30-ffffffff813f8f48: squashfs_decompress.cold (STB_LOCAL)
ffffffff813f8e80-ffffffff813f8f11: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff813e99b0-ffffffff813e99c8: squashfs_decompress.cold (STB_LOCAL)
ffffffff813e9900-ffffffff813e9991: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff813f62b0-ffffffff813f62c8: squashfs_decompress.cold (STB_LOCAL)
ffffffff813f6200-ffffffff813f6291: squashfs_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int squashfs_decompress(struct squashfs_sb_info *msblk, struct buffer_head **bh, int b, int offset, int length, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/decompressor_single.c (0)
Location: fs/squashfs/decompressor_single.c:62
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8140bf40-ffffffff8140bf58: squashfs_decompress.cold (STB_LOCAL)
ffffffff8140be90-ffffffff8140bf21: squashfs_decompress (STB_GLOBAL)
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
<code>msblk, bh, b, offset, length, output</code> ➡️ <code>msblk, bio, offset, length, output</code>
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
