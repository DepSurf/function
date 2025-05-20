# Function: <code>_ext4_get_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81298ef0)
Location: fs/ext4/inode.c:691
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_write
  - fs/ext4/inode.c:ext4_get_block_write_nolock
  - fs/ext4/inode.c:ext4_get_block_dax
```
**Symbols:**

```
ffffffff81298ef0-ffffffff81299108: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c6210)
Location: fs/ext4/inode.c:743
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff812c6210-ffffffff812c62f3: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dba60)
Location: fs/ext4/inode.c:754
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff812dba60-ffffffff812dbb5c: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81300300)
Location: fs/ext4/inode.c:760
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff81300300-ffffffff813003f9: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81324b20)
Location: fs/ext4/inode.c:770
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff81324b20-ffffffff81324c19: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81352d60)
Location: fs/ext4/inode.c:771
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff81352d60-ffffffff81352e6b: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136ae90)
Location: fs/ext4/inode.c:771
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff8136ae90-ffffffff8136af9c: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813943c0)
Location: fs/ext4/inode.c:779
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff813943c0-ffffffff813944c9: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813acd40)
Location: fs/ext4/inode.c:788
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff813acd40-ffffffff813ace49: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f8fb0)
Location: fs/ext4/inode.c:767
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff813f8fb0-ffffffff813f90b7: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140b680)
Location: fs/ext4/inode.c:781
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff8140b680-ffffffff8140b787: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81411830)
Location: fs/ext4/inode.c:782
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff81411830-ffffffff81411937: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:782
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff814646d0-ffffffff814647e2: _ext4_get_block (STB_LOCAL)
ffffffff81ccabbd-ffffffff81ccabdb: _ext4_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:790
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff814e3cb0-ffffffff814e3de8: _ext4_get_block (STB_LOCAL)
ffffffff81e7d9b5-ffffffff81e7d9d3: _ext4_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:796
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff8157d1c0-ffffffff8157d2f8: _ext4_get_block (STB_LOCAL)
ffffffff8206df1f-ffffffff8206df3d: _ext4_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:751
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff815b4570-ffffffff815b46b0: _ext4_get_block (STB_LOCAL)
ffffffff820edc0d-ffffffff820edc2b: _ext4_get_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:753
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff815ed380-ffffffff815ed4c0: _ext4_get_block (STB_LOCAL)
ffffffff821cad3c-ffffffff821cad5a: _ext4_get_block.cold (STB_LOCAL)
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
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010481470)
Location: fs/ext4/inode.c:788
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffff800010481470-ffff8000104815a8: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c064262c)
Location: fs/ext4/inode.c:788
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
c064262c-c064275c: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a5b30)
Location: fs/ext4/inode.c:788
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
c0000000005a5b30-c0000000005a5c98: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030a162)
Location: fs/ext4/inode.c:788
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffe00030a162-ffffffe00030a252: _ext4_get_block (STB_LOCAL)
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
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5320)
Location: fs/ext4/inode.c:788
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff813a5320-ffffffff813a5429: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395db0)
Location: fs/ext4/inode.c:788
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff81395db0-ffffffff81395eb9: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a2b80)
Location: fs/ext4/inode.c:788
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff813a2b80-ffffffff813a2c89: _ext4_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _ext4_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b7260)
Location: fs/ext4/inode.c:788
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_get_block_trans
  - fs/ext4/inode.c:ext4_get_block_unwritten
```
**Symbols:**

```
ffffffff813b7260-ffffffff813b7369: _ext4_get_block (STB_LOCAL)
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
