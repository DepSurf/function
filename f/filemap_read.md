# Function: <code>filemap_read</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t filemap_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t already_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81262380)
Location: mm/filemap.c:2519
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff81262380-ffffffff81262711: filemap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t filemap_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t already_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129e980)
Location: mm/filemap.c:2600
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff8129e980-ffffffff8129ed57: filemap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t filemap_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t already_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2654
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - block/fops.c:blkdev_read_iter
```
**Symbols:**

```
ffffffff81e6b513-ffffffff81e6b5c0: filemap_read.cold (STB_LOCAL)
ffffffff812f3000-ffffffff812f3492: filemap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t filemap_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t already_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2661
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - block/fops.c:blkdev_read_iter
```
**Symbols:**

```
ffffffff82062180-ffffffff8206222d: filemap_read.cold (STB_LOCAL)
ffffffff8135d3d0-ffffffff8135d7dd: filemap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t filemap_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t already_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2626
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - block/fops.c:blkdev_read_iter
```
**Symbols:**

```
ffffffff820e197f-ffffffff820e19f0: filemap_read.cold (STB_LOCAL)
ffffffff8138f450-ffffffff8138f86c: filemap_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t filemap_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t already_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2561
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - block/fops.c:blkdev_read_iter
```
**Symbols:**

```
ffffffff821be38e-ffffffff821be3fa: filemap_read.cold (STB_LOCAL)
ffffffff813b8b00-ffffffff813b8f65: filemap_read (STB_GLOBAL)
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
