# Function: <code>blkdev_get_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812470d0)
Location: fs/block_dev.c:150
Inline: False
```
**Symbols:**

```
ffffffff812470d0-ffffffff812470f0: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8126f9d0)
Location: fs/block_dev.c:163
Inline: False
```
**Symbols:**

```
ffffffff8126f9d0-ffffffff8126f9f0: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81282bd0)
Location: fs/block_dev.c:165
Inline: False
```
**Symbols:**

```
ffffffff81282bd0-ffffffff81282bf0: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812905b0)
Location: fs/block_dev.c:165
Inline: False
```
**Symbols:**

```
ffffffff812905b0-ffffffff812905d0: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b3270)
Location: fs/block_dev.c:153
Inline: False
```
**Symbols:**

```
ffffffff812b3270-ffffffff812b3290: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dbd00)
Location: fs/block_dev.c:153
Inline: True
```
**Symbols:**

```
ffffffff812dbd00-ffffffff812dbd2a: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f13f0)
Location: fs/block_dev.c:167
Inline: True
```
**Symbols:**

```
ffffffff812f13f0-ffffffff812f141a: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81313850)
Location: fs/block_dev.c:167
Inline: False
```
**Symbols:**

```
ffffffff81313850-ffffffff8131387b: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326760)
Location: fs/block_dev.c:167
Inline: False
```
**Symbols:**

```
ffffffff81326760-ffffffff8132678b: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8135f980)
Location: fs/block_dev.c:166
Inline: False
```
**Symbols:**

```
ffffffff8135f980-ffffffff8135f9ab: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136d190)
Location: fs/block_dev.c:198
Inline: False
```
**Symbols:**

```
ffffffff8136d190-ffffffff8136d1bb: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81373a00)
Location: fs/block_dev.c:197
Inline: False
```
**Symbols:**

```
ffffffff81373a00-ffffffff81373a2b: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff815c59d0)
Location: block/fops.c:25
Inline: False
```
**Symbols:**

```
ffffffff815c59d0-ffffffff815c5a08: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff81670400)
Location: block/fops.c:26
Inline: True
```
**Symbols:**

```
ffffffff81670400-ffffffff8167043b: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff8172b350)
Location: block/fops.c:26
Inline: False
```
**Symbols:**

```
ffffffff8172b350-ffffffff8172b38b: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff817673c0)
Location: block/fops.c:26
Inline: False
```
**Symbols:**

```
ffffffff817673c0-ffffffff817673fb: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff817a90e0)
Location: block/fops.c:404
Inline: False
```
**Symbols:**

```
ffffffff817a90e0-ffffffff817a911b: blkdev_get_block (STB_LOCAL)
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
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e0c00)
Location: fs/block_dev.c:167
Inline: False
```
**Symbols:**

```
ffff8000103e0c00-ffff8000103e0c8c: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b865c)
Location: fs/block_dev.c:167
Inline: False
```
**Symbols:**

```
c05b865c-c05b86a4: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e4010)
Location: fs/block_dev.c:167
Inline: False
```
**Symbols:**

```
c0000000004e4010-c0000000004e405c: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000296150)
Location: fs/block_dev.c:167
Inline: False
```
**Symbols:**

```
ffffffe000296150-ffffffe0002961aa: blkdev_get_block (STB_LOCAL)
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
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131ed40)
Location: fs/block_dev.c:167
Inline: False
```
**Symbols:**

```
ffffffff8131ed40-ffffffff8131ed6b: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130f8e0)
Location: fs/block_dev.c:167
Inline: False
```
**Symbols:**

```
ffffffff8130f8e0-ffffffff8130f90b: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131c810)
Location: fs/block_dev.c:167
Inline: False
```
**Symbols:**

```
ffffffff8131c810-ffffffff8131c83b: blkdev_get_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_get_block(struct inode *inode, sector_t iblock, struct buffer_head *bh, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132eb10)
Location: fs/block_dev.c:167
Inline: False
```
**Symbols:**

```
ffffffff8132eb10-ffffffff8132eb3b: blkdev_get_block (STB_LOCAL)
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
