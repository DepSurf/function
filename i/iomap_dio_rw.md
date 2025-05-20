# Function: <code>iomap_dio_rw</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, struct iomap_ops *ops, iomap_dio_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b1ea0)
Location: fs/iomap.c:842
Inline: False
```
**Symbols:**

```
ffffffff812b1ea0-ffffffff812b225a: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, iomap_dio_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812bf330)
Location: fs/iomap.c:932
Inline: False
```
**Symbols:**

```
ffffffff812bf330-ffffffff812bf735: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, iomap_dio_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e2df0)
Location: fs/iomap.c:962
Inline: False
```
**Symbols:**

```
ffffffff812e2df0-ffffffff812e313b: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, iomap_dio_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130f790)
Location: fs/iomap.c:1106
Inline: False
```
**Symbols:**

```
ffffffff8130f790-ffffffff8130fb4d: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, iomap_dio_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81326710)
Location: fs/iomap.c:1807
Inline: False
```
**Symbols:**

```
ffffffff81326710-ffffffff81326ade: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, iomap_dio_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134d0d0)
Location: fs/iomap/direct-io.c:398
Inline: False
```
**Symbols:**

```
ffffffff8134d0d0-ffffffff8134d503: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81365380)
Location: fs/iomap/direct-io.c:396
Inline: False
```
**Symbols:**

```
ffffffff81365380-ffffffff813657c7: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, bool wait_for_completion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813ad410)
Location: fs/iomap/direct-io.c:406
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff813ad410-ffffffff813ad877: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, bool wait_for_completion);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813beeb0)
Location: fs/iomap/direct-io.c:599
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff813beeb0-ffffffff813beee1: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813c5bb0)
Location: fs/iomap/direct-io.c:643
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff813c5bb0-ffffffff813c5bdd: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81416040)
Location: fs/iomap/direct-io.c:643
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff81416040-ffffffff8141606d: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags, void *private, size_t done_before);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8148d870)
Location: fs/iomap/direct-io.c:683
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff8148d870-ffffffff8148d8d7: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags, void *private, size_t done_before);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81521020)
Location: fs/iomap/direct-io.c:683
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff81521020-ffffffff81521087: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags, void *private, size_t done_before);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81559060)
Location: fs/iomap/direct-io.c:659
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff81559060-ffffffff815590b1: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops, unsigned int dio_flags, void *private, size_t done_before);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8158f7d0)
Location: fs/iomap/direct-io.c:742
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff8158f7d0-ffffffff8158f821: iomap_dio_rw (STB_GLOBAL)
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
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffff80001042d0a8)
Location: fs/iomap/direct-io.c:396
Inline: False
```
**Symbols:**

```
ffff80001042d0a8-ffff80001042d474: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c05f60c8)
Location: fs/iomap/direct-io.c:396
Inline: False
```
**Symbols:**

```
c05f60c8-c05f660c: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c00000000053d660)
Location: fs/iomap/direct-io.c:396
Inline: False
```
**Symbols:**

```
c00000000053d660-c00000000053db64: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffe0002c9766)
Location: fs/iomap/direct-io.c:396
Inline: False
```
**Symbols:**

```
ffffffe0002c9766-ffffffe0002c9a5c: iomap_dio_rw (STB_GLOBAL)
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
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135d960)
Location: fs/iomap/direct-io.c:396
Inline: False
```
**Symbols:**

```
ffffffff8135d960-ffffffff8135dda7: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134e600)
Location: fs/iomap/direct-io.c:396
Inline: False
```
**Symbols:**

```
ffffffff8134e600-ffffffff8134ea47: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135b430)
Location: fs/iomap/direct-io.c:396
Inline: False
```
**Symbols:**

```
ffffffff8135b430-ffffffff8135b877: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t iomap_dio_rw(struct kiocb *iocb, struct iov_iter *iter, const struct iomap_ops *ops, const struct iomap_dio_ops *dops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8136eb80)
Location: fs/iomap/direct-io.c:396
Inline: False
```
**Symbols:**

```
ffffffff8136eb80-ffffffff8136efc7: iomap_dio_rw (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap_ops *ops</code> ➡️ <code>const struct iomap_ops *ops</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iomap_dio_ops *dops</code>
</li>
<li>
<b>Param removed. </b>
<code>iomap_dio_end_io_t *end_io</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool wait_for_completion</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int dio_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wait_for_completion</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *private</code>
</li>
<li>
<b>Param added. </b>
<code>size_t done_before</code>
</li>
</ul>
</details>
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
