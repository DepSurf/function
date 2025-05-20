# Function: <code>__do_page_cache_readahead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8119bdd0)
Location: mm/readahead.c:152
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff8119bdd0-ffffffff8119bffa: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811b0f70)
Location: mm/readahead.c:150
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff811b0f70-ffffffff811b11f6: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811c1560)
Location: mm/readahead.c:150
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff811c1560-ffffffff811c17d4: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811c9800)
Location: mm/readahead.c:150
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff811c9800-ffffffff811c9a78: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811de680)
Location: mm/readahead.c:150
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff811de680-ffffffff811de936: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811ffef0)
Location: mm/readahead.c:150
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff811ffef0-ffffffff8120007e: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812127c0)
Location: mm/readahead.c:152
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff812127c0-ffffffff8121294b: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812221b0)
Location: mm/readahead.c:155
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff812221b0-ffffffff81222343: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8122fc60)
Location: mm/readahead.c:155
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff8122fc60-ffffffff8122fdf3: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __do_page_cache_readahead(struct address_space *mapping, struct file *file, long unsigned int index, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8125d130)
Location: mm/readahead.c:255
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
Direct callers:
  - mm/filemap.c:do_sync_mmap_readahead
```
**Symbols:**

```
ffffffff8125d3f0-ffffffff8125d428: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
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
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffff8000102bf4e0)
Location: mm/readahead.c:155
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffff8000102bf4e0-ffff8000102bf6a4: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c04eaf2c)
Location: mm/readahead.c:155
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
c04eaf2c-c04eb148: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c000000000378150)
Location: mm/readahead.c:155
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
c000000000378150-c000000000378410: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffe0001e165a)
Location: mm/readahead.c:155
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffe0001e165a-ffffffe0001e1796: __do_page_cache_readahead (STB_GLOBAL)
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
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812282b0)
Location: mm/readahead.c:155
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff812282b0-ffffffff81228443: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8121b3f0)
Location: mm/readahead.c:155
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff8121b3f0-ffffffff8121b583: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81226050)
Location: mm/readahead.c:155
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff81226050-ffffffff812261e3: __do_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int __do_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read, long unsigned int lookahead_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81235350)
Location: mm/readahead.c:155
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:force_page_cache_readahead
```
**Symbols:**

```
ffffffff81235350-ffffffff812354e3: __do_page_cache_readahead (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *filp</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int offset</code>
</li>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>void</code>
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
