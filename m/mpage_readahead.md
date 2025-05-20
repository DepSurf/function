# Function: <code>mpage_readahead</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mpage_readahead(struct readahead_control *rac, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813654f0)
Location: fs/mpage.c:379
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readahead
  - fs/fat/inode.c:fat_readahead
```
**Symbols:**

```
ffffffff813654f0-ffffffff8136568f: mpage_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mpage_readahead(struct readahead_control *rac, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813723c0)
Location: fs/mpage.c:379
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readahead
  - fs/fat/inode.c:fat_readahead
```
**Symbols:**

```
ffffffff813723c0-ffffffff8137255c: mpage_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpage_readahead(struct readahead_control *rac, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813784a0)
Location: fs/mpage.c:377
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_readahead
  - fs/fat/inode.c:fat_readahead
```
**Symbols:**

```
ffffffff813784a0-ffffffff8137863c: mpage_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpage_readahead(struct readahead_control *rac, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813c4d80)
Location: fs/mpage.c:377
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_readahead
  - block/fops.c:blkdev_readahead
```
**Symbols:**

```
ffffffff813c4d80-ffffffff813c4f1c: mpage_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpage_readahead(struct readahead_control *rac, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff8144bbc0)
Location: fs/mpage.c:344
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_readahead
  - block/fops.c:blkdev_readahead
```
**Symbols:**

```
ffffffff8144bbc0-ffffffff8144bdc7: mpage_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpage_readahead(struct readahead_control *rac, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff814da1f0)
Location: fs/mpage.c:349
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_readahead
  - block/fops.c:blkdev_readahead
```
**Symbols:**

```
ffffffff814da1f0-ffffffff814da323: mpage_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpage_readahead(struct readahead_control *rac, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff8150e130)
Location: fs/mpage.c:370
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_readahead
  - block/fops.c:blkdev_readahead
```
**Symbols:**

```
ffffffff8150e130-ffffffff8150e263: mpage_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpage_readahead(struct readahead_control *rac, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81542c10)
Location: fs/mpage.c:369
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_readahead
  - block/fops.c:blkdev_readahead
```
**Symbols:**

```
ffffffff81542c10-ffffffff81542d40: mpage_readahead (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
