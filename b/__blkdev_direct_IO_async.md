# Function: <code>__blkdev_direct_IO_async</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t __blkdev_direct_IO_async(struct kiocb *iocb, struct iov_iter *iter, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/fops.c (0)
Location: block/fops.c:289
Inline: False
```
**Symbols:**

```
ffffffff81670510-ffffffff816706c2: __blkdev_direct_IO_async (STB_LOCAL)
ffffffff81e8b2d3-ffffffff81e8b2e8: __blkdev_direct_IO_async.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t __blkdev_direct_IO_async(struct kiocb *iocb, struct iov_iter *iter, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/fops.c (0)
Location: block/fops.c:309
Inline: False
```
**Symbols:**

```
ffffffff8172bb40-ffffffff8172bd32: __blkdev_direct_IO_async (STB_LOCAL)
ffffffff82075b0a-ffffffff82075b34: __blkdev_direct_IO_async.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t __blkdev_direct_IO_async(struct kiocb *iocb, struct iov_iter *iter, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/fops.c (0)
Location: block/fops.c:309
Inline: False
```
**Symbols:**

```
ffffffff81767c20-ffffffff81767e1f: __blkdev_direct_IO_async (STB_LOCAL)
ffffffff820f594d-ffffffff820f5977: __blkdev_direct_IO_async.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t __blkdev_direct_IO_async(struct kiocb *iocb, struct iov_iter *iter, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/fops.c (0)
Location: block/fops.c:301
Inline: False
```
**Symbols:**

```
ffffffff817a9880-ffffffff817a9a6a: __blkdev_direct_IO_async (STB_LOCAL)
ffffffff821d2bf5-ffffffff821d2c0a: __blkdev_direct_IO_async.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
