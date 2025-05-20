# Function: <code>block_write_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81244590)
Location: fs/buffer.c:2054
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81244590-ffffffff812445ff: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126c240)
Location: fs/buffer.c:2110
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8126c240-ffffffff8126c2be: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127f590)
Location: fs/buffer.c:2151
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8127f590-ffffffff8127f60e: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128d620)
Location: fs/buffer.c:2148
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8128d620-ffffffff8128d69e: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b0170)
Location: fs/buffer.c:2108
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff812b0170-ffffffff812b01ee: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d7a30)
Location: fs/buffer.c:2079
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff812d7a30-ffffffff812d7aae: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ed3f0)
Location: fs/buffer.c:2122
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff812ed3f0-ffffffff812ed46e: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130ebb0)
Location: fs/buffer.c:2089
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8130ebb0-ffffffff8130ec34: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81321bd0)
Location: fs/buffer.c:2089
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81321bd0-ffffffff81321c54: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135ceb4)
Location: fs/buffer.c:2133
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
Direct callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8135cdf0-ffffffff8135ce74: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369054)
Location: fs/buffer.c:2132
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
Direct callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81368e70-ffffffff81368ef4: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136f594)
Location: fs/buffer.c:2153
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
Direct callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8136ef00-ffffffff8136ef87: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813be3e4)
Location: fs/buffer.c:2132
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
  - block/fops.c:blkdev_write_end
```
**Symbols:**

```
ffffffff813bdb40-ffffffff813bdbc7: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81446f65)
Location: fs/buffer.c:2129
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
  - block/fops.c:blkdev_write_end
```
**Symbols:**

```
ffffffff81446e70-ffffffff81446f2f: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d5d55)
Location: fs/buffer.c:2114
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
  - block/fops.c:blkdev_write_end
```
**Symbols:**

```
ffffffff814d5c50-ffffffff814d5d0f: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150a550)
Location: fs/buffer.c:2251
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
  - block/fops.c:blkdev_write_end
```
**Symbols:**

```
ffffffff8150a550-ffffffff8150a61b: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153f2f0)
Location: fs/buffer.c:2223
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_write_end
  - block/fops.c:blkdev_write_end
```
**Symbols:**

```
ffffffff8153f2f0-ffffffff8153f3b5: block_write_end (STB_GLOBAL)
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
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d9738)
Location: fs/buffer.c:2089
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffff8000103d9738-ffff8000103d97ec: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b3be8)
Location: fs/buffer.c:2089
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
c05b3be8-c05b3c7c: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004df800)
Location: fs/buffer.c:2089
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
c0000000004df800-c0000000004df91c: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000293374)
Location: fs/buffer.c:2089
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffe000293374-ffffffe000293426: block_write_end (STB_GLOBAL)
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
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131a1b0)
Location: fs/buffer.c:2089
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8131a1b0-ffffffff8131a234: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130ad50)
Location: fs/buffer.c:2089
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8130ad50-ffffffff8130add4: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81317c80)
Location: fs/buffer.c:2089
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81317c80-ffffffff81317d04: block_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int block_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81329890)
Location: fs/buffer.c:2089
Inline: False
Direct callers:
  - fs/buffer.c:generic_write_end
  - fs/block_dev.c:blkdev_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81329890-ffffffff81329914: block_write_end (STB_GLOBAL)
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
