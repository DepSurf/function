# Function: <code>delete_from_page_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e690)
Location: mm/filemap.c:230
Inline: True
Direct callers:
  - mm/truncate.c:truncate_inode_page
  - mm/shmem.c:shmem_getpage_gfp
  - fs/dax.c:__dax_fault
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8118e690-ffffffff8118e710: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a2180)
Location: mm/filemap.c:306
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_page
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff811a2180-ffffffff811a2251: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b1fd0)
Location: mm/filemap.c:271
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_page
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff811b1fd0-ffffffff811b20a1: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b8cb0)
Location: mm/filemap.c:265
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_page
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff811b8cb0-ffffffff811b8d66: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd2f0)
Location: mm/filemap.c:294
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff811cd2f0-ffffffff811cd35e: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eee40)
Location: mm/filemap.c:294
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff811eee40-ffffffff811eeeae: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200760)
Location: mm/filemap.c:262
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff81200760-ffffffff812007ce: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218390)
Location: mm/filemap.c:264
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff81218390-ffffffff812183fd: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81225c20)
Location: mm/filemap.c:266
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff81225c20-ffffffff81225c8d: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124fd90)
Location: mm/filemap.c:266
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff8124fd90-ffffffff8124fe65: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81259c00)
Location: mm/filemap.c:267
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff81259c00-ffffffff81259cba: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812613c0)
Location: mm/filemap.c:258
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff812613c0-ffffffff8126142d: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129e020)
Location: mm/filemap.c:260
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff8129e020-ffffffff8129e08f: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813012c0)
Location: mm/folio-compat.c:143
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff813012c0-ffffffff8130131b: delete_from_page_cache (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b2cd0)
Location: mm/filemap.c:266
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffff8000102b2cd0-ffff8000102b2db4: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dfefc)
Location: mm/filemap.c:266
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
c04dfefc-c04dffc4: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c0000000003697c0)
Location: mm/filemap.c:266
Inline: False
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
c0000000003697c0-c000000000369878: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8572)
Location: mm/filemap.c:266
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffe0001d8572-ffffffe0001d8634: delete_from_page_cache (STB_GLOBAL)
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
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e270)
Location: mm/filemap.c:266
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff8121e270-ffffffff8121e2dd: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81211430)
Location: mm/filemap.c:266
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff81211430-ffffffff8121149d: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c010)
Location: mm/filemap.c:266
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff8121c010-ffffffff8121c07d: delete_from_page_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void delete_from_page_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b080)
Location: mm/filemap.c:266
Inline: True
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - fs/hugetlbfs/inode.c:remove_huge_page
```
**Symbols:**

```
ffffffff8122b080-ffffffff8122b0ed: delete_from_page_cache (STB_GLOBAL)
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
