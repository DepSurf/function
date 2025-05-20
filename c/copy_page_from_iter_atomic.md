# Function: <code>copy_page_from_iter_atomic</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t copy_page_from_iter_atomic(struct page *page, unsigned int offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:911
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff81cda8ab-ffffffff81cda8d4: copy_page_from_iter_atomic.cold (STB_LOCAL)
ffffffff81614d80-ffffffff81615458: copy_page_from_iter_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t copy_page_from_iter_atomic(struct page *page, unsigned int offset, size_t bytes, struct iov_iter *i);
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
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff81e92f98-ffffffff81e92fe4: copy_page_from_iter_atomic.cold (STB_LOCAL)
ffffffff816e2cf0-ffffffff816e343c: copy_page_from_iter_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t copy_page_from_iter_atomic(struct page *page, unsigned int offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:809
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff820782fc-ffffffff82078345: copy_page_from_iter_atomic.cold (STB_LOCAL)
ffffffff817d5490-ffffffff817d5b02: copy_page_from_iter_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t copy_page_from_iter_atomic(struct page *page, unsigned int offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:569
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff820f8770-ffffffff820f87ed: copy_page_from_iter_atomic.cold (STB_LOCAL)
ffffffff81813ec0-ffffffff81814478: copy_page_from_iter_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t copy_page_from_iter_atomic(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:460
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff821d6297-ffffffff821d62ca: copy_page_from_iter_atomic.cold (STB_LOCAL)
ffffffff818582a0-ffffffff8185892f: copy_page_from_iter_atomic (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int offset</code> ➡️ <code>size_t offset</code>
</li>
</ul>
</details>
</li>
</ul>
