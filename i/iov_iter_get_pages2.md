# Function: <code>iov_iter_get_pages2</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages2(struct iov_iter *i, struct page **pages, size_t maxsize, unsigned int maxpages, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d2ea0)
Location: lib/iov_iter.c:1509
Inline: False
Direct callers:
  - fs/splice.c:iter_to_pipe
  - fs/direct-io.c:do_direct_IO
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff817d2ea0-ffffffff817d2efe: iov_iter_get_pages2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages2(struct iov_iter *i, struct page **pages, size_t maxsize, unsigned int maxpages, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff818137d0)
Location: lib/iov_iter.c:1144
Inline: False
Direct callers:
  - fs/splice.c:iter_to_pipe
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff818137d0-ffffffff81813814: iov_iter_get_pages2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages2(struct iov_iter *i, struct page **pages, size_t maxsize, unsigned int maxpages, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff818593b0)
Location: lib/iov_iter.c:1041
Inline: False
Direct callers:
  - fs/splice.c:iter_to_pipe
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/file.c:fuse_direct_io
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
```
**Symbols:**

```
ffffffff818593b0-ffffffff818593f4: iov_iter_get_pages2 (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
