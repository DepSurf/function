# Function: <code>iov_iter_copy_from_user_atomic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fc7d0)
Location: lib/iov_iter.c:493
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff813fc7d0-ffffffff813fc9ef: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81444610)
Location: lib/iov_iter.c:442
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81444610-ffffffff81444913: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81462780)
Location: lib/iov_iter.c:712
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81462780-ffffffff81462ab4: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81465be0)
Location: lib/iov_iter.c:771
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81465be0-ffffffff81465ebc: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81491cb0)
Location: lib/iov_iter.c:773
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81491cb0-ffffffff81491fb5: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c7810)
Location: lib/iov_iter.c:903
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814c7810-ffffffff814c7b24: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814db450)
Location: lib/iov_iter.c:949
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814db450-ffffffff814db794: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:963
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8150ad54-ffffffff8150ad88: iov_iter_copy_from_user_atomic.cold (STB_LOCAL)
ffffffff81506d50-ffffffff815070c6: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81524e60)
Location: lib/iov_iter.c:963
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81524e60-ffffffff815251d2: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81589680)
Location: lib/iov_iter.c:987
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff81589680-ffffffff81589a3a: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a5a00)
Location: lib/iov_iter.c:994
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff815a5a00-ffffffff815a5ce4: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ad860)
Location: lib/iov_iter.c:1065
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff815ad860-ffffffff815adf4a: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062f298)
Location: lib/iov_iter.c:963
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffff80001062f298-ffff80001062f608: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d5c24)
Location: lib/iov_iter.c:963
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
c07d5c24-c07d5fc0: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d6fc0)
Location: lib/iov_iter.c:963
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
c0000000007d6fc0-c0000000007d74b8: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045e77e)
Location: lib/iov_iter.c:963
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffe00045e77e-ffffffe00045ea76: iov_iter_copy_from_user_atomic (STB_GLOBAL)
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
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151d440)
Location: lib/iov_iter.c:963
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8151d440-ffffffff8151d7b2: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150d730)
Location: lib/iov_iter.c:963
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8150d730-ffffffff8150daa2: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815194d0)
Location: lib/iov_iter.c:963
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff815194d0-ffffffff81519842: iov_iter_copy_from_user_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t iov_iter_copy_from_user_atomic(struct page *page, struct iov_iter *i, long unsigned int offset, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81532cc0)
Location: lib/iov_iter.c:963
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81532cc0-ffffffff8153305a: iov_iter_copy_from_user_atomic (STB_GLOBAL)
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
