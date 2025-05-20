# Function: <code>shmem_uncharge</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c3a60)
Location: mm/shmem.c:284
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811c3a60-ffffffff811c3aff: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d3ad0)
Location: mm/shmem.c:280
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811d3ad0-ffffffff811d3b6e: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dc280)
Location: mm/shmem.c:296
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811dc280-ffffffff811dc31f: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f2110)
Location: mm/shmem.c:313
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811f2110-ffffffff811f21ab: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812135b0)
Location: mm/shmem.c:313
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff812135b0-ffffffff81213658: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812264e0)
Location: mm/shmem.c:317
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff812264e0-ffffffff81226588: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812363c0)
Location: mm/shmem.c:322
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff812363c0-ffffffff81236468: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244600)
Location: mm/shmem.c:337
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81244600-ffffffff812446a8: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81272280)
Location: mm/shmem.c:336
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81272280-ffffffff81272328: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127c730)
Location: mm/shmem.c:395
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8127c730-ffffffff8127c7d7: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81281900)
Location: mm/shmem.c:395
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81281900-ffffffff812819a7: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bcf00)
Location: mm/shmem.c:392
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff812bcf00-ffffffff812bcfa7: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131c0d0)
Location: mm/shmem.c:390
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8131c0d0-ffffffff8131c192: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138fc80)
Location: mm/shmem.c:387
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8138fc80-ffffffff8138fd42: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813c25d0)
Location: mm/shmem.c:388
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff813c25d0-ffffffff813c2692: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813ed2b0)
Location: mm/shmem.c:462
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff813ed2b0-ffffffff813ed339: shmem_uncharge (STB_GLOBAL)
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
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d6ae0)
Location: mm/shmem.c:337
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffff8000102d6ae0-ffff8000102d6c00: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fea4c)
Location: mm/shmem.c:337
Inline: False
```
**Symbols:**

```
c04fea4c-c04feb34: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000396b50)
Location: mm/shmem.c:337
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
c000000000396b50-c000000000396c74: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001f1f76)
Location: mm/shmem.c:337
Inline: False
```
**Symbols:**

```
ffffffe0001f1f76-ffffffe0001f2046: shmem_uncharge (STB_GLOBAL)
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
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123cc50)
Location: mm/shmem.c:337
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8123cc50-ffffffff8123ccf8: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122fc50)
Location: mm/shmem.c:337
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8122fc50-ffffffff8122fcf8: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123a9f0)
Location: mm/shmem.c:337
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8123a9f0-ffffffff8123aa98: shmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void shmem_uncharge(struct inode *inode, long int pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8124a0f0)
Location: mm/shmem.c:337
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8124a0f0-ffffffff8124a198: shmem_uncharge (STB_GLOBAL)
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
