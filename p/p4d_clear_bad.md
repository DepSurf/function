# Function: <code>p4d_clear_bad</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202a80)
Location: mm/pgtable-generic.c:25
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff81202a80-ffffffff81202ace: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8121b7f0)
Location: mm/pgtable-generic.c:26
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff8121b7f0-ffffffff8121b83e: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d5d0)
Location: mm/pgtable-generic.c:26
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff8123d5d0-ffffffff8123d61e: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81251b20)
Location: mm/pgtable-generic.c:27
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81251b20-ffffffff81251b6e: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81263df0)
Location: mm/pgtable-generic.c:27
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81263df0-ffffffff81263e40: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81272660)
Location: mm/pgtable-generic.c:27
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81272660-ffffffff812726b0: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812a33f0)
Location: mm/pgtable-generic.c:28
Inline: False
Direct callers:
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pmd
  - mm/pagewalk.c:walk_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/swapfile.c:unuse_p4d_range
```
**Symbols:**

```
ffffffff812a33f0-ffffffff812a3442: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812aed00)
Location: mm/pgtable-generic.c:28
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/swapfile.c:unuse_p4d_range
```
**Symbols:**

```
ffffffff812aed00-ffffffff812aed48: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812b4230)
Location: mm/pgtable-generic.c:28
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_p4d_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812b4230-ffffffff812b4278: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812f5e10)
Location: mm/pgtable-generic.c:28
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_p4d_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812f5e10-ffffffff812f5e58: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81359d70)
Location: mm/pgtable-generic.c:29
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81359d70-ffffffff81359dcf: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff813d4770)
Location: mm/pgtable-generic.c:29
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff813d4770-ffffffff813d47cf: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81409140)
Location: mm/pgtable-generic.c:31
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81409140-ffffffff8140919f: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81435930)
Location: mm/pgtable-generic.c:32
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81435930-ffffffff8143598f: p4d_clear_bad (STB_GLOBAL)
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
void p4d_clear_bad(pgd_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffff800010307ed0)
Location: mm/pgtable-generic.c:27
Inline: False
```
**Symbols:**

```
ffff800010307ed0-ffff800010307f2c: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void p4d_clear_bad(pgd_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c05253f0)
Location: mm/pgtable-generic.c:27
Inline: False
```
**Symbols:**

```
c05253f0-c0525408: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void p4d_clear_bad(pgd_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0000000003d7010)
Location: mm/pgtable-generic.c:27
Inline: False
```
**Symbols:**

```
c0000000003d7010-c0000000003d7024: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffe000212db4)
Location: mm/pgtable-generic.c:27
Inline: False
```
**Symbols:**

```
ffffffe000212db4-ffffffe000212df0: p4d_clear_bad (STB_GLOBAL)
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
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8126acb0)
Location: mm/pgtable-generic.c:27
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8126acb0-ffffffff8126ad00: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8125d18f)
Location: mm/pgtable-generic.c:27
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff8125d18f-ffffffff8125d1d3: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268a50)
Location: mm/pgtable-generic.c:27
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff81268a50-ffffffff81268aa0: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812783e0)
Location: mm/pgtable-generic.c:27
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffff812783e0-ffffffff81278430: p4d_clear_bad (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t *p4d</code> ➡️ <code>pgd_t *p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t *p4d</code> ➡️ <code>pgd_t *p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t *p4d</code> ➡️ <code>pgd_t *p4d</code>
</li>
</ul>
</details>
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
