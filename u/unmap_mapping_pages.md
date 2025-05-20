# Function: <code>unmap_mapping_pages</code>

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
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122d040)
Location: mm/memory.c:2862
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8122d040-ffffffff8122d169: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812405d0)
Location: mm/memory.c:2599
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff812405d0-ffffffff812406f9: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81252880)
Location: mm/memory.c:2667
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81252880-ffffffff812529a2: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81260de0)
Location: mm/memory.c:2692
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81260de0-ffffffff81260f02: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81291260)
Location: mm/memory.c:3040
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81291260-ffffffff81291380: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129bbd0)
Location: mm/memory.c:3203
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8129bbd0-ffffffff8129bcf0: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0e60)
Location: mm/memory.c:3294
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff812a0e60-ffffffff812a0f83: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e17e0)
Location: mm/memory.c:3391
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff812e17e0-ffffffff812e1903: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81342606)
Location: mm/memory.c:3549
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/memory.c:__do_fault
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81342370-ffffffff8134249e: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ba796)
Location: mm/memory.c:3521
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/memory.c:__do_fault
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff813ba4b0-ffffffff813ba5db: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ef156)
Location: mm/memory.c:3524
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/memory.c:__do_fault
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff813eee70-ffffffff813eef9c: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141aac6)
Location: mm/memory.c:3603
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8141a940-ffffffff8141aa6c: unmap_mapping_pages (STB_GLOBAL)
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
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f8180)
Location: mm/memory.c:2692
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffff8000102f8180-ffff8000102f82b0: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051a954)
Location: mm/memory.c:2692
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
```
**Symbols:**

```
c051a954-c051aa78: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c14a0)
Location: mm/memory.c:2692
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
c0000000003c14a0-c0000000003c1620: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000208746)
Location: mm/memory.c:2692
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
```
**Symbols:**

```
ffffffe000208746-ffffffe00020884c: unmap_mapping_pages (STB_GLOBAL)
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
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81259430)
Location: mm/memory.c:2692
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81259430-ffffffff81259552: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124b8b0)
Location: mm/memory.c:2692
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8124b8b0-ffffffff8124b9d2: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812571d0)
Location: mm/memory.c:2692
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff812571d0-ffffffff812572f2: unmap_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unmap_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int nr, bool even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81266bc0)
Location: mm/memory.c:2692
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/memory.c:unmap_mapping_range
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81266bc0-ffffffff81266ce2: unmap_mapping_pages (STB_GLOBAL)
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
