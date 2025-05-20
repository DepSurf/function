# Function: <code>pagecache_write_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118c5f0)
Location: mm/filemap.c:2377
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff8118c5f0-ffffffff8118c60e: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119f440)
Location: mm/filemap.c:2554
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff8119f440-ffffffff8119f45e: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811aee60)
Location: mm/filemap.c:2670
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff811aee60-ffffffff811aee7e: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b5990)
Location: mm/filemap.c:2807
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff811b5990-ffffffff811b59a5: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811c9ab0)
Location: mm/filemap.c:2977
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff811c9ab0-ffffffff811c9acb: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eac10)
Location: mm/filemap.c:2977
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff811eac10-ffffffff811eac2b: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fb780)
Location: mm/filemap.c:3046
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff811fb780-ffffffff811fb79b: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81212e10)
Location: mm/filemap.c:3165
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff81212e10-ffffffff81212e2b: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220630)
Location: mm/filemap.c:3122
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff81220630-ffffffff8122064b: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124d9d0)
Location: mm/filemap.c:3131
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:generic_cont_expand_simple
```
**Symbols:**

```
ffffffff8124d9d0-ffffffff8124d9eb: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81257f20)
Location: mm/filemap.c:3226
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:generic_cont_expand_simple
```
**Symbols:**

```
ffffffff81257f20-ffffffff81257f3b: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125c500)
Location: mm/filemap.c:3473
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:generic_cont_expand_simple
```
**Symbols:**

```
ffffffff8125c500-ffffffff8125c51b: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812983c0)
Location: mm/filemap.c:3590
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:generic_cont_expand_simple
```
**Symbols:**

```
ffffffff812983c0-ffffffff812983de: pagecache_write_begin (STB_GLOBAL)
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
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102ad898)
Location: mm/filemap.c:3122
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffff8000102ad898-ffff8000102ad914: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04da1d4)
Location: mm/filemap.c:3122
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
c04da1d4-c04da220: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c0000000003617b0)
Location: mm/filemap.c:3122
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:generic_cont_expand_simple
```
**Symbols:**

```
c0000000003617b0-c0000000003617f4: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d3dbe)
Location: mm/filemap.c:3122
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffe0001d3dbe-ffffffe0001d3e18: pagecache_write_begin (STB_GLOBAL)
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
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218c80)
Location: mm/filemap.c:3122
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff81218c80-ffffffff81218c9b: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120be90)
Location: mm/filemap.c:3122
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff8120be90-ffffffff8120beab: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81216a20)
Location: mm/filemap.c:3122
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff81216a20-ffffffff81216a3b: pagecache_write_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pagecache_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81225aa0)
Location: mm/filemap.c:3122
Inline: False
Direct callers:
  - fs/namei.c:__page_symlink
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff81225aa0-ffffffff81225abb: pagecache_write_begin (STB_GLOBAL)
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
