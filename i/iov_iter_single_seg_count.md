# Function: <code>iov_iter_single_seg_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fb7c0)
Location: lib/iov_iter.c:518
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff813fb7c0-ffffffff813fb803: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81442b70)
Location: lib/iov_iter.c:467
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81442b70-ffffffff81442bb3: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8145fd80)
Location: lib/iov_iter.c:792
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8145fd80-ffffffff8145fdc8: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464e40)
Location: lib/iov_iter.c:918
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81464e40-ffffffff81464e82: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490dc0)
Location: lib/iov_iter.c:920
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81490dc0-ffffffff81490e02: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c5bd0)
Location: lib/iov_iter.c:1050
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff814c5bd0-ffffffff814c5c0c: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da350)
Location: lib/iov_iter.c:1102
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff814da350-ffffffff814da394: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81505b80)
Location: lib/iov_iter.c:1116
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81505b80-ffffffff81505bca: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81523b60)
Location: lib/iov_iter.c:1116
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81523b60-ffffffff81523baa: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81586c20)
Location: lib/iov_iter.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff81586c20-ffffffff81586c6a: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a3ef0)
Location: lib/iov_iter.c:1157
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff815a3ef0-ffffffff815a3f3a: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815aae00)
Location: lib/iov_iter.c:1259
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff815aae00-ffffffff815aae4d: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81614700)
Location: lib/iov_iter.c:1115
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff81614700-ffffffff8161473f: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e1240)
Location: lib/iov_iter.c:1167
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff816e1240-ffffffff816e128f: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d17f0)
Location: lib/iov_iter.c:985
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff817d17f0-ffffffff817d183f: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81810600)
Location: lib/iov_iter.c:697
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff81810600-ffffffff8181064f: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81856050)
Location: lib/iov_iter.c:598
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff81856050-ffffffff818560a8: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062da70)
Location: lib/iov_iter.c:1116
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffff80001062da70-ffff80001062dad4: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d46a0)
Location: lib/iov_iter.c:1116
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
c07d46a0-c07d46f4: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0fb0)
Location: lib/iov_iter.c:1116
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
c0000000007d0fb0-c0000000007d1028: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d7b4)
Location: lib/iov_iter.c:1116
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffe00045d7b4-ffffffe00045d804: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c140)
Location: lib/iov_iter.c:1116
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8151c140-ffffffff8151c18a: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c430)
Location: lib/iov_iter.c:1116
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8150c430-ffffffff8150c47a: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815181d0)
Location: lib/iov_iter.c:1116
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff815181d0-ffffffff8151821a: iov_iter_single_seg_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t iov_iter_single_seg_count(const struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815319c0)
Location: lib/iov_iter.c:1116
Inline: True
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff815319c0-ffffffff81531a0a: iov_iter_single_seg_count (STB_GLOBAL)
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
