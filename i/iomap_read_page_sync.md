# Function: <code>iomap_read_page_sync</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81325160)
Location: fs/iomap.c:609
Inline: False
```
**Symbols:**

```
ffffffff81325160-ffffffff81325302: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134be10)
Location: fs/iomap/buffered-io.c:528
Inline: False
```
**Symbols:**

```
ffffffff8134be10-ffffffff8134bfbe: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813640e0)
Location: fs/iomap/buffered-io.c:528
Inline: False
```
**Symbols:**

```
ffffffff813640e0-ffffffff8136428e: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_read_page_sync(loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813a9f30)
Location: fs/iomap/buffered-io.c:554
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
**Symbols:**

```
ffffffff813a9f30-ffffffff813aa01c: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_read_page_sync(loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bb580)
Location: fs/iomap/buffered-io.c:535
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
**Symbols:**

```
ffffffff813bb580-ffffffff813bb66f: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_read_page_sync(loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c26a0)
Location: fs/iomap/buffered-io.c:535
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
**Symbols:**

```
ffffffff813c26a0-ffffffff813c2790: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iomap_read_page_sync(loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, const struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81411fc0)
Location: fs/iomap/buffered-io.c:532
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
**Symbols:**

```
ffffffff81411fc0-ffffffff814120b0: iomap_read_page_sync (STB_LOCAL)
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
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042b3e0)
Location: fs/iomap/buffered-io.c:528
Inline: False
```
**Symbols:**

```
ffff80001042b3e0-ffff80001042b590: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f3e0c)
Location: fs/iomap/buffered-io.c:528
Inline: False
```
**Symbols:**

```
c05f3e0c-c05f4000: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053c430)
Location: fs/iomap/buffered-io.c:528
Inline: False
```
**Symbols:**

```
c00000000053c430-c00000000053c63c: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c8d02)
Location: fs/iomap/buffered-io.c:528
Inline: False
```
**Symbols:**

```
ffffffe0002c8d02-ffffffe0002c8e9e: iomap_read_page_sync (STB_LOCAL)
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
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135c6c0)
Location: fs/iomap/buffered-io.c:528
Inline: False
```
**Symbols:**

```
ffffffff8135c6c0-ffffffff8135c86e: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134d360)
Location: fs/iomap/buffered-io.c:528
Inline: False
```
**Symbols:**

```
ffffffff8134d360-ffffffff8134d50e: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135a190)
Location: fs/iomap/buffered-io.c:528
Inline: False
```
**Symbols:**

```
ffffffff8135a190-ffffffff8135a33e: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iomap_read_page_sync(struct inode *inode, loff_t block_start, struct page *page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136d8c0)
Location: fs/iomap/buffered-io.c:528
Inline: False
```
**Symbols:**

```
ffffffff8136d8c0-ffffffff8136da8c: iomap_read_page_sync (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int from</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int to</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, block_start, page, poff, plen, from, to, iomap</code> ➡️ <code>block_start, page, poff, plen, iomap</code>
</li>
</ul>
</details>
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
<code>struct iomap *iomap</code> ➡️ <code>const struct iomap *iomap</code>
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
