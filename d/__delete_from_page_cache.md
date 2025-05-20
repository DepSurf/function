# Function: <code>__delete_from_page_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e3a0)
Location: mm/filemap.c:181
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffff8118e3a0-ffffffff8118e687: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1da0)
Location: mm/filemap.c:229
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_fault
```
**Symbols:**

```
ffffffff811a1da0-ffffffff811a217a: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b1c00)
Location: mm/filemap.c:194
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_mapping_entry
```
**Symbols:**

```
ffffffff811b1c00-ffffffff811b1fcd: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b8910)
Location: mm/filemap.c:186
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811b8910-ffffffff811b8ca6: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd150)
Location: mm/filemap.c:259
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811cd150-ffffffff811cd2e5: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eecb0)
Location: mm/filemap.c:259
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811eecb0-ffffffff811eee3d: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200590)
Location: mm/filemap.c:227
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81200590-ffffffff8120075c: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812181c0)
Location: mm/filemap.c:229
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff812181c0-ffffffff81218387: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81225a50)
Location: mm/filemap.c:231
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81225a50-ffffffff81225c1a: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124fde1)
Location: mm/filemap.c:231
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache
Direct callers:
  - mm/truncate.c:invalidate_complete_page2
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81250f20-ffffffff81250f9d: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81259c4c)
Location: mm/filemap.c:232
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache
Direct callers:
  - mm/truncate.c:invalidate_complete_page2
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8125c5e0-ffffffff8125c64c: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81261210)
Location: mm/filemap.c:223
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81261210-ffffffff812613b5: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129de70)
Location: mm/filemap.c:225
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8129de70-ffffffff8129e01b: __delete_from_page_cache (STB_GLOBAL)
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
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b2ad8)
Location: mm/filemap.c:231
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffff8000102b2ad8-ffff8000102b2cd0: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dfd54)
Location: mm/filemap.c:231
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
c04dfd54-c04dfefc: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000369520)
Location: mm/filemap.c:231
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
c000000000369520-c0000000003697c0: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8404)
Location: mm/filemap.c:231
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
```
**Symbols:**

```
ffffffe0001d8404-ffffffe0001d8572: __delete_from_page_cache (STB_GLOBAL)
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
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e0a0)
Location: mm/filemap.c:231
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8121e0a0-ffffffff8121e26a: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81211260)
Location: mm/filemap.c:231
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81211260-ffffffff8121142a: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121be40)
Location: mm/filemap.c:231
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8121be40-ffffffff8121c00a: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __delete_from_page_cache(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122ae90)
Location: mm/filemap.c:231
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8122ae90-ffffffff8122b073: __delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup *memcg</code>
</li>
</ul>
</details>
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
