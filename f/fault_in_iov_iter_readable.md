# Function: <code>fault_in_iov_iter_readable</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t fault_in_iov_iter_readable(const struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e1290)
Location: lib/iov_iter.c:444
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff816e1290-ffffffff816e132a: fault_in_iov_iter_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t fault_in_iov_iter_readable(const struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d1700)
Location: lib/iov_iter.c:352
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff817d1700-ffffffff817d17e0: fault_in_iov_iter_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t fault_in_iov_iter_readable(const struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81810510)
Location: lib/iov_iter.c:212
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff81810510-ffffffff818105f0: fault_in_iov_iter_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t fault_in_iov_iter_readable(const struct iov_iter *i, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81855f60)
Location: lib/iov_iter.c:90
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff81855f60-ffffffff81856031: fault_in_iov_iter_readable (STB_GLOBAL)
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
