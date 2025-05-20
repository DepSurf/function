# Function: <code>__import_iovec</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t __import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i, bool compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a8e50)
Location: lib/iov_iter.c:1740
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:__io_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
  - lib/iov_iter.c:import_iovec
```
**Symbols:**

```
ffffffff815a8e50-ffffffff815a8f98: __import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t __import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i, bool compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b3a80)
Location: lib/iov_iter.c:2028
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:__io_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
  - lib/iov_iter.c:import_iovec
```
**Symbols:**

```
ffffffff815b3a80-ffffffff815b3bd4: __import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t __import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i, bool compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81619bf0)
Location: lib/iov_iter.c:1886
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:__io_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
  - lib/iov_iter.c:import_iovec
```
**Symbols:**

```
ffffffff81619bf0-ffffffff81619d45: __import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t __import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i, bool compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e7090)
Location: lib/iov_iter.c:1935
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - io_uring/io_uring.c:__io_compat_recvmsg_copy_hdr
  - io_uring/io_uring.c:__io_recvmsg_copy_hdr
  - io_uring/io_uring.c:__io_import_iovec
  - lib/iov_iter.c:import_iovec
```
**Symbols:**

```
ffffffff816e7090-ffffffff816e7216: __import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t __import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i, bool compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d6890)
Location: lib/iov_iter.c:1787
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - io_uring/net.c:__io_compat_recvmsg_copy_hdr
  - io_uring/net.c:__io_recvmsg_copy_hdr
  - io_uring/rw.c:__io_import_iovec
  - lib/iov_iter.c:import_iovec
```
**Symbols:**

```
ffffffff817d6890-ffffffff817d6a1b: __import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t __import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i, bool compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81815840)
Location: lib/iov_iter.c:1443
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - io_uring/net.c:__io_compat_recvmsg_copy_hdr
  - io_uring/net.c:__io_recvmsg_copy_hdr
  - io_uring/rw.c:__io_import_iovec
  - lib/iov_iter.c:import_iovec
```
**Symbols:**

```
ffffffff81815840-ffffffff81815a38: __import_iovec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t __import_iovec(int type, const struct iovec *uvec, unsigned int nr_segs, unsigned int fast_segs, struct iovec **iovp, struct iov_iter *i, bool compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8185a990)
Location: lib/iov_iter.c:1268
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - io_uring/rw.c:__io_import_iovec
  - lib/iov_iter.c:import_iovec
```
**Symbols:**

```
ffffffff8185a990-ffffffff8185ab7d: __import_iovec (STB_GLOBAL)
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
