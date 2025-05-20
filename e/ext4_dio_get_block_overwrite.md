# Function: <code>ext4_dio_get_block_overwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c6880)
Location: fs/ext4/inode.c:899
Inline: True
```
**Symbols:**

```
ffffffff812c6880-ffffffff812c6925: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dc100)
Location: fs/ext4/inode.c:913
Inline: True
```
**Symbols:**

```
ffffffff812dc100-ffffffff812dc1a5: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81300950)
Location: fs/ext4/inode.c:919
Inline: True
```
**Symbols:**

```
ffffffff81300950-ffffffff81300996: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813251a0)
Location: fs/ext4/inode.c:929
Inline: False
```
**Symbols:**

```
ffffffff813251a0-ffffffff813251e6: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81353410)
Location: fs/ext4/inode.c:930
Inline: False
```
**Symbols:**

```
ffffffff81353410-ffffffff81353456: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136b540)
Location: fs/ext4/inode.c:930
Inline: False
```
**Symbols:**

```
ffffffff8136b540-ffffffff8136b586: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81394ab0)
Location: fs/ext4/inode.c:938
Inline: True
```
**Symbols:**

```
ffffffff81394ab0-ffffffff81394af6: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ad430)
Location: fs/ext4/inode.c:947
Inline: True
```
**Symbols:**

```
ffffffff813ad430-ffffffff813ad476: ext4_dio_get_block_overwrite (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010481bf8)
Location: fs/ext4/inode.c:947
Inline: True
```
**Symbols:**

```
ffff800010481bf8-ffff800010481c80: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0642d60)
Location: fs/ext4/inode.c:947
Inline: True
```
**Symbols:**

```
c0642d60-c0642e5c: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a63e0)
Location: fs/ext4/inode.c:947
Inline: True
```
**Symbols:**

```
c0000000005a63e0-c0000000005a6478: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030a7c2)
Location: fs/ext4/inode.c:947
Inline: True
```
**Symbols:**

```
ffffffe00030a7c2-ffffffe00030a82a: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5a10)
Location: fs/ext4/inode.c:947
Inline: True
```
**Symbols:**

```
ffffffff813a5a10-ffffffff813a5a56: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813964a0)
Location: fs/ext4/inode.c:947
Inline: True
```
**Symbols:**

```
ffffffff813964a0-ffffffff813964e6: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a3270)
Location: fs/ext4/inode.c:947
Inline: True
```
**Symbols:**

```
ffffffff813a3270-ffffffff813a32b6: ext4_dio_get_block_overwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_overwrite(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b7960)
Location: fs/ext4/inode.c:947
Inline: True
```
**Symbols:**

```
ffffffff813b7960-ffffffff813b79a6: ext4_dio_get_block_overwrite (STB_LOCAL)
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
