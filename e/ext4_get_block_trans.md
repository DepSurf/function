# Function: <code>ext4_get_block_trans</code>

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
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c6930)
Location: fs/ext4/inode.c:795
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff812c6930-ffffffff812c6a35: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dc1b0)
Location: fs/ext4/inode.c:809
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff812dc1b0-ffffffff812dc2b5: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813009a0)
Location: fs/ext4/inode.c:815
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813009a0-ffffffff81300aa5: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813251f0)
Location: fs/ext4/inode.c:825
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813251f0-ffffffff813252f5: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81353460)
Location: fs/ext4/inode.c:826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff81353460-ffffffff81353565: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136b590)
Location: fs/ext4/inode.c:826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff8136b590-ffffffff8136b697: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81394b00)
Location: fs/ext4/inode.c:834
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff81394b00-ffffffff81394c07: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ad480)
Location: fs/ext4/inode.c:843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813ad480-ffffffff813ad587: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010481c80)
Location: fs/ext4/inode.c:843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffff800010481c80-ffff800010481db4: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0642e5c)
Location: fs/ext4/inode.c:843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
c0642e5c-c0642f80: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a6480)
Location: fs/ext4/inode.c:843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
c0000000005a6480-c0000000005a65fc: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030a82a)
Location: fs/ext4/inode.c:843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffe00030a82a-ffffffe00030a914: ext4_get_block_trans (STB_LOCAL)
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
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5a60)
Location: fs/ext4/inode.c:843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813a5a60-ffffffff813a5b67: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813964f0)
Location: fs/ext4/inode.c:843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813964f0-ffffffff813965f7: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a32c0)
Location: fs/ext4/inode.c:843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813a32c0-ffffffff813a33c7: ext4_get_block_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_get_block_trans(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b79b0)
Location: fs/ext4/inode.c:843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813b79b0-ffffffff813b7ab7: ext4_get_block_trans (STB_LOCAL)
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
