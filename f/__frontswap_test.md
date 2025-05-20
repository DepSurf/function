# Function: <code>__frontswap_test</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff811d7430)
Location: mm/frontswap.c:212
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff811d7430-ffffffff811d7456: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff811f5b0a)
Location: mm/frontswap.c:216
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff811f55f0-ffffffff811f5612: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff8120663a)
Location: mm/frontswap.c:216
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81206120-ffffffff81206142: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81211dca)
Location: mm/frontswap.c:216
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff812118c0-ffffffff812118e0: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff8122c79a)
Location: mm/frontswap.c:216
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8122c260-ffffffff8122c281: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff8124f445)
Location: mm/frontswap.c:216
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8124eef0-ffffffff8124ef11: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff812638d5)
Location: mm/frontswap.c:216
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff812633d0-ffffffff812633f1: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff8127e4f5)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff8127e320-ffffffff8127e340: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff8128df55)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff8128dd80-ffffffff8128dda0: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff812c0bc5)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812c0960-ffffffff812c0982: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff812cc5ec)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812cc380-ffffffff812cc3a2: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff812d301c)
Location: mm/frontswap.c:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812d2f00-ffffffff812d2f22: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81318a2c)
Location: mm/frontswap.c:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81318900-ffffffff81318922: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff813840d5)
Location: mm/frontswap.c:131
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81401940)
Location: mm/frontswap.c:134
Inline: False
Direct callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
**Symbols:**

```
ffffffff81401940-ffffffff8140196a: __frontswap_test (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81434820)
Location: mm/frontswap.c:134
Inline: False
Direct callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
**Symbols:**

```
ffffffff81434820-ffffffff8143484a: __frontswap_test (STB_LOCAL)
```
</details>
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
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffff80001032a454)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffff80001032a058-ffff80001032a0ac: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (c0540ffc)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
c05408c8-c054090c: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (c000000000401028)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
c000000000400d90-c000000000400dd8: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffe0002294c0)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffe0002292fe-ffffffe00022934c: __frontswap_test (STB_GLOBAL)
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
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81286535)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81286360-ffffffff81286380: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81278395)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff812781c0-ffffffff812781e0: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81284345)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81284170-ffffffff81284190: __frontswap_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool __frontswap_test(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81294325)
Location: mm/frontswap.c:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
Direct callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81293e50-ffffffff81293e70: __frontswap_test (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
