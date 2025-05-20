# Function: <code>iov_iter_fault_in_readable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fcb10)
Location: lib/iov_iter.c:309
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff813fcb10-ffffffff813fcb7c: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814444f0)
Location: lib/iov_iter.c:300
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814444f0-ffffffff81444609: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81462660)
Location: lib/iov_iter.c:393
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81462660-ffffffff81462779: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814654d0)
Location: lib/iov_iter.c:413
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814654d0-ffffffff814655eb: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81493890)
Location: lib/iov_iter.c:413
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81493890-ffffffff814939bb: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c94b0)
Location: lib/iov_iter.c:413
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814c94b0-ffffffff814c95dd: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dea90)
Location: lib/iov_iter.c:417
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814dea90-ffffffff814debbd: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150a6c0)
Location: lib/iov_iter.c:418
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8150a6c0-ffffffff8150a7ed: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815241f0)
Location: lib/iov_iter.c:418
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff815241f0-ffffffff8152431d: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81588040)
Location: lib/iov_iter.c:423
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff81588040-ffffffff8158816a: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a4530)
Location: lib/iov_iter.c:430
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff815a4530-ffffffff815a4648: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ab3a0)
Location: lib/iov_iter.c:472
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff815ab3a0-ffffffff815ab4aa: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int iov_iter_fault_in_readable(const struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81614650)
Location: lib/iov_iter.c:440
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/fuse/file.c:fuse_fill_write_pages
```
**Symbols:**

```
ffffffff81614650-ffffffff816146f9: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
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
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff8000106330e0)
Location: lib/iov_iter.c:418
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffff8000106330e0-ffff800010633178: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d9044)
Location: lib/iov_iter.c:418
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
c07d9044-c07d9264: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d1bd0)
Location: lib/iov_iter.c:418
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
c0000000007d1bd0-c0000000007d1eb4: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045dc62)
Location: lib/iov_iter.c:418
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffe00045dc62-ffffffe00045ddb2: iov_iter_fault_in_readable (STB_GLOBAL)
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
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c7d0)
Location: lib/iov_iter.c:418
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8151c7d0-ffffffff8151c8fd: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150cac0)
Location: lib/iov_iter.c:418
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8150cac0-ffffffff8150cbed: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81518860)
Location: lib/iov_iter.c:418
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81518860-ffffffff8151898d: iov_iter_fault_in_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter *i, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81532050)
Location: lib/iov_iter.c:418
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81532050-ffffffff8153217d: iov_iter_fault_in_readable (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iov_iter *i</code> ➡️ <code>const struct iov_iter *i</code>
</li>
</ul>
</details>
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
