# Function: <code>ext4_dio_get_block_unwritten_sync</code>

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
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c6b00)
Location: fs/ext4/inode.c:877
Inline: True
```
**Symbols:**

```
ffffffff812c6b00-ffffffff812c6b7c: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dc380)
Location: fs/ext4/inode.c:891
Inline: True
```
**Symbols:**

```
ffffffff812dc380-ffffffff812dc3fc: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81300b50)
Location: fs/ext4/inode.c:897
Inline: True
```
**Symbols:**

```
ffffffff81300b50-ffffffff81300ba3: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813253a0)
Location: fs/ext4/inode.c:907
Inline: True
```
**Symbols:**

```
ffffffff813253a0-ffffffff813253f3: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81353610)
Location: fs/ext4/inode.c:908
Inline: True
```
**Symbols:**

```
ffffffff81353610-ffffffff81353663: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136b740)
Location: fs/ext4/inode.c:908
Inline: True
```
**Symbols:**

```
ffffffff8136b740-ffffffff8136b793: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81394cc0)
Location: fs/ext4/inode.c:916
Inline: True
```
**Symbols:**

```
ffffffff81394cc0-ffffffff81394d19: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ad640)
Location: fs/ext4/inode.c:925
Inline: True
```
**Symbols:**

```
ffffffff813ad640-ffffffff813ad699: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
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
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010481eb8)
Location: fs/ext4/inode.c:925
Inline: True
```
**Symbols:**

```
ffff800010481eb8-ffff800010481f48: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c06430b8)
Location: fs/ext4/inode.c:925
Inline: True
```
**Symbols:**

```
c06430b8-c0643184: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a6720)
Location: fs/ext4/inode.c:925
Inline: True
```
**Symbols:**

```
c0000000005a6720-c0000000005a67c8: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030a9b4)
Location: fs/ext4/inode.c:925
Inline: True
```
**Symbols:**

```
ffffffe00030a9b4-ffffffe00030aa14: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
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
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5c20)
Location: fs/ext4/inode.c:925
Inline: True
```
**Symbols:**

```
ffffffff813a5c20-ffffffff813a5c79: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813966b0)
Location: fs/ext4/inode.c:925
Inline: True
```
**Symbols:**

```
ffffffff813966b0-ffffffff81396709: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a3480)
Location: fs/ext4/inode.c:925
Inline: True
```
**Symbols:**

```
ffffffff813a3480-ffffffff813a34d9: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_dio_get_block_unwritten_sync(struct inode *inode, sector_t iblock, struct buffer_head *bh_result, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b7b70)
Location: fs/ext4/inode.c:925
Inline: True
```
**Symbols:**

```
ffffffff813b7b70-ffffffff813b7bc9: ext4_dio_get_block_unwritten_sync (STB_LOCAL)
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
