# Function: <code>__get_locked_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c1760)
Location: mm/memory.c:1419
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff811c1760-ffffffff811c18fd: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd230)
Location: mm/memory.c:1452
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff811dd230-ffffffff811dd3d0: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ecd20)
Location: mm/memory.c:1448
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff811ecd20-ffffffff811ecebf: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f7c40)
Location: mm/memory.c:1570
Inline: False
Direct callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff811f7c40-ffffffff811f7df1: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120fd50)
Location: mm/memory.c:1673
Inline: False
Direct callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff8120fd50-ffffffff8120ff6e: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122f450)
Location: mm/memory.c:1684
Inline: False
Direct callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff8122f450-ffffffff8122f63f: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81243e40)
Location: mm/memory.c:1416
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff81243e40-ffffffff8124402c: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81255cd0)
Location: mm/memory.c:1388
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff81255cd0-ffffffff81255ebc: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264260)
Location: mm/memory.c:1393
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff81264260-ffffffff8126444c: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292780)
Location: mm/memory.c:1443
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:unmap_ldt_struct
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/mlock.c:__munlock_pagevec_fill
```
**Symbols:**

```
ffffffff81292780-ffffffff812929df: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d0e0)
Location: mm/memory.c:1617
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/mlock.c:__munlock_pagevec_fill
```
**Symbols:**

```
ffffffff8129d0e0-ffffffff8129d307: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a27d0)
Location: mm/memory.c:1635
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:__munlock_pagevec_fill
```
**Symbols:**

```
ffffffff812a27d0-ffffffff812a29c9: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e5d50)
Location: mm/memory.c:1730
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:__munlock_pagevec_fill
```
**Symbols:**

```
ffffffff812e5d50-ffffffff812e5e1f: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81345040)
Location: mm/memory.c:1824
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
**Symbols:**

```
ffffffff81345040-ffffffff8134516b: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bd290)
Location: mm/memory.c:1795
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
**Symbols:**

```
ffffffff813bd290-ffffffff813bd3bb: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f1fe0)
Location: mm/memory.c:1811
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
**Symbols:**

```
ffffffff813f1fe0-ffffffff813f2063: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141cc60)
Location: mm/memory.c:1844
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
**Symbols:**

```
ffffffff8141cc60-ffffffff8141cce3: __get_locked_pte (STB_GLOBAL)
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
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fafb8)
Location: mm/memory.c:1393
Inline: False
Direct callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffff8000102fafb8-ffff8000102fb13c: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519920)
Location: mm/memory.c:1393
Inline: False
Direct callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
c0519920-c05199c4: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c5ba0)
Location: mm/memory.c:1393
Inline: False
Direct callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
c0000000003c5ba0-c0000000003c5e7c: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020a842)
Location: mm/memory.c:1393
Inline: False
Direct callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffe00020a842-ffffffe00020a918: __get_locked_pte (STB_GLOBAL)
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
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125c8b0)
Location: mm/memory.c:1393
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff8125c8b0-ffffffff8125ca9c: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124edb0)
Location: mm/memory.c:1393
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff8124edb0-ffffffff8124ef80: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125a650)
Location: mm/memory.c:1393
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff8125a650-ffffffff8125a83c: __get_locked_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pte_t *__get_locked_pte(struct mm_struct *mm, long unsigned int addr, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a030)
Location: mm/memory.c:1393
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/init.c:poking_init
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/mlock.c:munlock_vma_pages_range
```
**Symbols:**

```
ffffffff8126a030-ffffffff8126a21c: __get_locked_pte (STB_GLOBAL)
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
