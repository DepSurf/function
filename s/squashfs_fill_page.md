# Function: <code>squashfs_fill_page</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff8139fe40)
Location: fs/squashfs/file.c:377
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8139fe40-ffffffff8139fed3: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff813b8bd0)
Location: fs/squashfs/file.c:377
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813b8bd0-ffffffff813b8c63: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff813e39f0)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813e39f0-ffffffff813e3a81: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff813fda20)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813fda20-ffffffff813fdabf: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff8144b470)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_read_cache
```
**Symbols:**

```
ffffffff8144b470-ffffffff8144b50f: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81467b50)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_read_cache
```
**Symbols:**

```
ffffffff81467b50-ffffffff81467bef: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff8146d160)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8146d160-ffffffff8146d1ff: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff814c39e0)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff814c39e0-ffffffff814c3a7f: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff8154e5d0)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8154e5d0-ffffffff8154e6c8: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff815eea60)
Location: fs/squashfs/file.c:365
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
**Symbols:**

```
ffffffff815eea60-ffffffff815eeb5b: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81626a50)
Location: fs/squashfs/file.c:365
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
**Symbols:**

```
ffffffff81626a50-ffffffff81626b4b: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff8165fbc0)
Location: fs/squashfs/file.c:365
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
**Symbols:**

```
ffffffff8165fbc0-ffffffff8165fcb8: squashfs_fill_page (STB_GLOBAL)
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
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffff8000104dba60)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffff8000104dba60-ffff8000104dbb8c: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (c069d25c)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
c069d25c-c069d2f4: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (c000000000616ba0)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
c000000000616ba0-c000000000616cd8: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffe000350774)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffe000350774-ffffffe000350840: squashfs_fill_page (STB_GLOBAL)
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
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff813f6000)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813f6000-ffffffff813f609f: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff813e6a80)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813e6a80-ffffffff813e6b1f: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff813f3380)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813f3380-ffffffff813f341f: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void squashfs_fill_page(struct page *page, struct squashfs_cache_entry *buffer, int offset, int avail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81408f70)
Location: fs/squashfs/file.c:364
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81408f70-ffffffff81409026: squashfs_fill_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
