# Function: <code>__blkdev_direct_IO</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8128387c)
Location: fs/block_dev.c:326
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81290f40)
Location: fs/block_dev.c:332
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b3c81)
Location: fs/block_dev.c:320
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dc4ae)
Location: fs/block_dev.c:323
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f1c07)
Location: fs/block_dev.c:340
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81312570)
Location: fs/block_dev.c:338
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
```
**Symbols:**

```
ffffffff81312570-ffffffff813129b1: __blkdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813254c0)
Location: fs/block_dev.c:338
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
```
**Symbols:**

```
ffffffff813254c0-ffffffff813258f5: __blkdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8135fa40)
Location: fs/block_dev.c:337
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
```
**Symbols:**

```
ffffffff8135fa40-ffffffff8135fe78: __blkdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136d2c0)
Location: fs/block_dev.c:369
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
```
**Symbols:**

```
ffffffff8136d2c0-ffffffff8136d6f0: __blkdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81373b30)
Location: fs/block_dev.c:369
Inline: False
```
**Symbols:**

```
ffffffff81373b30-ffffffff81373fbc: __blkdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/fops.c (0)
Location: block/fops.c:191
Inline: False
```
**Symbols:**

```
ffffffff815c5d60-ffffffff815c61a3: __blkdev_direct_IO (STB_LOCAL)
ffffffff81cd7eea-ffffffff81cd7eff: __blkdev_direct_IO.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/fops.c (0)
Location: block/fops.c:164
Inline: False
```
**Symbols:**

```
ffffffff81670920-ffffffff81670c83: __blkdev_direct_IO (STB_LOCAL)
ffffffff81e8b329-ffffffff81e8b33e: __blkdev_direct_IO.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/fops.c (0)
Location: block/fops.c:170
Inline: False
```
**Symbols:**

```
ffffffff8172bfe0-ffffffff8172c397: __blkdev_direct_IO (STB_LOCAL)
ffffffff82075b8e-ffffffff82075bb8: __blkdev_direct_IO.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/fops.c (0)
Location: block/fops.c:170
Inline: True
```
**Symbols:**

```
ffffffff817680c0-ffffffff8176847a: __blkdev_direct_IO.constprop.0 (STB_LOCAL)
ffffffff820f59d2-ffffffff820f59fb: __blkdev_direct_IO.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/fops.c (0)
Location: block/fops.c:162
Inline: True
```
**Symbols:**

```
ffffffff817a9d00-ffffffff817aa0ad: __blkdev_direct_IO.constprop.0 (STB_LOCAL)
ffffffff821d2c50-ffffffff821d2c64: __blkdev_direct_IO.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e0d10)
Location: fs/block_dev.c:338
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b7ef0)
Location: fs/block_dev.c:338
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
```
**Symbols:**

```
c05b7ef0-c05b83f0: __blkdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e6d3c)
Location: fs/block_dev.c:338
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002976c8)
Location: fs/block_dev.c:338
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
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
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131daa0)
Location: fs/block_dev.c:338
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
```
**Symbols:**

```
ffffffff8131daa0-ffffffff8131ded5: __blkdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130e640)
Location: fs/block_dev.c:338
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
```
**Symbols:**

```
ffffffff8130e640-ffffffff8130ea75: __blkdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131b570)
Location: fs/block_dev.c:338
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
```
**Symbols:**

```
ffffffff8131b570-ffffffff8131b9a5: __blkdev_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t __blkdev_direct_IO(struct kiocb *iocb, struct iov_iter *iter, int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132d350)
Location: fs/block_dev.c:338
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
```
**Symbols:**

```
ffffffff8132d350-ffffffff8132d785: __blkdev_direct_IO (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nr_pages</code> ➡️ <code>unsigned int nr_pages</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
