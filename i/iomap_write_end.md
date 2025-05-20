# Function: <code>iomap_write_end</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8129c3e0)
Location: fs/iomap.c:137
Inline: True
Direct callers:
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8129c3e0-ffffffff8129c455: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b1100)
Location: fs/iomap.c:138
Inline: True
Direct callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff812b1100-ffffffff812b1175: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812be4c0)
Location: fs/iomap.c:140
Inline: True
Direct callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff812be4c0-ffffffff812be530: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e1e60)
Location: fs/iomap.c:140
Inline: True
Direct callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff812e1e60-ffffffff812e1ed0: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130e760)
Location: fs/iomap.c:150
Inline: True
Direct callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8130e760-ffffffff8130e7d0: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813242a0)
Location: fs/iomap.c:768
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff813242a0-ffffffff813244a8: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c350)
Location: fs/iomap/buffered-io.c:699
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8134c350-ffffffff8134c5c9: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81364620)
Location: fs/iomap/buffered-io.c:699
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff81364620-ffffffff81364899: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813ac190)
Location: fs/iomap/buffered-io.c:730
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff813ac190-ffffffff813ac37e: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t iomap_write_end(struct inode *inode, loff_t pos, size_t len, size_t copied, struct page *page, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bd780)
Location: fs/iomap/buffered-io.c:709
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff813bd780-ffffffff813bd951: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t iomap_write_end(struct inode *inode, loff_t pos, size_t len, size_t copied, struct page *page, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c48d0)
Location: fs/iomap/buffered-io.c:709
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff813c48d0-ffffffff813c4b2f: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t iomap_write_end(struct iomap_iter *iter, loff_t pos, size_t len, size_t copied, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81414070)
Location: fs/iomap/buffered-io.c:695
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
```
**Symbols:**

```
ffffffff81414070-ffffffff814142c0: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t iomap_write_end(struct iomap_iter *iter, loff_t pos, size_t len, size_t copied, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:698
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff8148a1a0-ffffffff8148a47e: iomap_write_end (STB_LOCAL)
ffffffff81e7a181-ffffffff81e7a1b3: iomap_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t iomap_write_end(struct iomap_iter *iter, loff_t pos, size_t len, size_t copied, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:712
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff8151db90-ffffffff8151de4f: iomap_write_end (STB_LOCAL)
ffffffff8206b0c3-ffffffff8206b11e: iomap_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t iomap_write_end(struct iomap_iter *iter, loff_t pos, size_t len, size_t copied, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:734
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff81555d10-ffffffff81555ff5: iomap_write_end (STB_LOCAL)
ffffffff820eb040-ffffffff820eb078: iomap_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t iomap_write_end(struct iomap_iter *iter, loff_t pos, size_t len, size_t copied, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:837
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff8158c1d0-ffffffff8158c4b5: iomap_write_end (STB_LOCAL)
ffffffff821c811d-ffffffff821c8173: iomap_write_end.cold (STB_LOCAL)
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
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042b138)
Location: fs/iomap/buffered-io.c:699
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffff80001042b138-ffff80001042b3dc: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f4424)
Location: fs/iomap/buffered-io.c:699
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
c05f4424-c05f46fc: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053b9a0)
Location: fs/iomap/buffered-io.c:699
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
c00000000053b9a0-c00000000053bd74: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c8828)
Location: fs/iomap/buffered-io.c:699
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffe0002c8828-ffffffe0002c8a50: iomap_write_end (STB_LOCAL)
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
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135cc00)
Location: fs/iomap/buffered-io.c:699
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8135cc00-ffffffff8135ce79: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134d8a0)
Location: fs/iomap/buffered-io.c:699
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8134d8a0-ffffffff8134db19: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135a6d0)
Location: fs/iomap/buffered-io.c:699
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8135a6d0-ffffffff8135a949: iomap_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iomap_write_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136de20)
Location: fs/iomap/buffered-io.c:699
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8136de20-ffffffff8136e0b0: iomap_write_end (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iomap *iomap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iomap *srcmap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>size_t len</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int copied</code> ➡️ <code>size_t copied</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>size_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iomap_iter *iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap *iomap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap *srcmap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
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
