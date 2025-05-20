# Function: <code>vfs_iter_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120c000)
Location: fs/read_write.c:332
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff8120c000-ffffffff8120c0bb: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81232200)
Location: fs/read_write.c:361
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff81232200-ffffffff81232303: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81244b70)
Location: fs/read_write.c:361
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff81244b70-ffffffff81244c73: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81250f50)
Location: fs/read_write.c:925
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff81250f50-ffffffff81250f73: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272b50)
Location: fs/read_write.c:930
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff81272b50-ffffffff81272b73: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81298a40)
Location: fs/read_write.c:957
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff81298a40-ffffffff81298a63: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ad8c0)
Location: fs/read_write.c:954
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff812ad8c0-ffffffff812ad8e3: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ca550)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff812ca550-ffffffff812ca573: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dbf70)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff812dbf70-ffffffff812dbf93: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81312b50)
Location: fs/read_write.c:1024
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
```
**Symbols:**

```
ffffffff81312b50-ffffffff81312b73: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131e220)
Location: fs/read_write.c:840
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
```
**Symbols:**

```
ffffffff8131e220-ffffffff8131e243: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81323c60)
Location: fs/read_write.c:838
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_read_transfer
```
**Symbols:**

```
ffffffff81323c60-ffffffff81323c83: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81371880)
Location: fs/read_write.c:829
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_read_transfer
```
**Symbols:**

```
ffffffff81371880-ffffffff813718a3: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813ef880)
Location: fs/read_write.c:840
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_read_simple
```
**Symbols:**

```
ffffffff813ef880-ffffffff813ef8bb: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81477e40)
Location: fs/read_write.c:833
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_read_simple
```
**Symbols:**

```
ffffffff81477e40-ffffffff81477e7b: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ac3d0)
Location: fs/read_write.c:832
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_read_simple
```
**Symbols:**

```
ffffffff814ac3d0-ffffffff814ac40e: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ddbc0)
Location: fs/read_write.c:810
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_read_simple
```
**Symbols:**

```
ffffffff814ddbc0-ffffffff814ddd09: vfs_iter_read (STB_GLOBAL)
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
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff8000103819e0)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffff8000103819e0-ffff800010381a40: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056c178)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
c056c178-c056c1ac: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000477f00)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
c000000000477f00-c000000000477f2c: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002568f8)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffe0002568f8-ffffffe000256944: vfs_iter_read (STB_GLOBAL)
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
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4550)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff812d4550-ffffffff812d4573: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c51d0)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff812c51d0-ffffffff812c51f3: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2360)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff812d2360-ffffffff812d2383: vfs_iter_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vfs_iter_read(struct file *file, struct iov_iter *iter, loff_t *ppos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e31c0)
Location: fs/read_write.c:968
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff812e31c0-ffffffff812e31e3: vfs_iter_read (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int flags</code> ➡️ <code>rwf_t flags</code>
</li>
</ul>
</details>
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
