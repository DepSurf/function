# Function: <code>__next_mem_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, ulong flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181dcc6)
Location: mm/memblock.c:884
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff8181dcc6-ffffffff8181de96: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, ulong flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81898102)
Location: mm/memblock.c:874
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff81898102-ffffffff818982f2: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, ulong flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cc7a4)
Location: mm/memblock.c:874
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff818cc7a4-ffffffff818cc997: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, ulong flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81903c5c)
Location: mm/memblock.c:870
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff81903c5c-ffffffff81903e42: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, ulong flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198dc67)
Location: mm/memblock.c:870
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff8198dc67-ffffffff8198de4a: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, ulong flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819ea50c)
Location: mm/memblock.c:878
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff819ea50c-ffffffff819ea6ef: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a2577b)
Location: mm/memblock.c:991
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff81a2577b-ffffffff81a25954: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a95eb5)
Location: mm/memblock.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff81a95eb5-ffffffff81a96075: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81acd78c)
Location: mm/memblock.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff81acd78c-ffffffff81acd94c: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc618f)
Location: mm/memblock.c:1022
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/page_alloc.c:init_unavailable_mem
  - mm/page_alloc.c:init_unavailable_mem
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:do_one_pass
  - mm/memtest.c:do_one_pass
```
**Symbols:**

```
ffffffff81bc618f-ffffffff81bc632e: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff812c0510)
Location: mm/memblock.c:983
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:do_one_pass
  - mm/memtest.c:do_one_pass
```
**Symbols:**

```
ffffffff812c0510-ffffffff812c0713: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff812c5cc0)
Location: mm/memblock.c:984
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:do_one_pass
  - mm/memtest.c:do_one_pass
```
**Symbols:**

```
ffffffff812c5cc0-ffffffff812c5ea8: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memblock.c (0)
Location: mm/memblock.c:1019
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:do_one_pass
  - mm/memtest.c:do_one_pass
```
**Symbols:**

```
ffffffff81cbe5a3-ffffffff81cbe5be: __next_mem_range.cold (STB_LOCAL)
ffffffff8130a5c0-ffffffff8130a7b9: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memblock.c (0)
Location: mm/memblock.c:1024
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:do_one_pass
```
**Symbols:**

```
ffffffff81e70586-ffffffff81e705ab: __next_mem_range.cold (STB_LOCAL)
ffffffff813730b0-ffffffff813732f2: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memblock.c (0)
Location: mm/memblock.c:1042
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff82065702-ffffffff82065727: __next_mem_range.cold (STB_LOCAL)
ffffffff813f0830-ffffffff813f0a72: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memblock.c (0)
Location: mm/memblock.c:1055
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff820e4ef3-ffffffff820e4f18: __next_mem_range.cold (STB_LOCAL)
ffffffff814243c0-ffffffff81424601: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memblock.c (0)
Location: mm/memblock.c:1113
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff821c1bca-ffffffff821c1bef: __next_mem_range.cold (STB_LOCAL)
ffffffff814511e0-ffffffff81451421: __next_mem_range (STB_GLOBAL)
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
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031b8f8)
Location: mm/memblock.c:1014
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffff80001031b8f8-ffff80001031bb14: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c05357b8)
Location: mm/memblock.c:1014
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
c05357b8-c05359d0: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003ef220)
Location: mm/memblock.c:1014
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
c0000000003ef220-c0000000003ef538: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000047b92)
Location: mm/memblock.c:1014
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffe000047b92-ffffffe000047d0a: __next_mem_range (STB_GLOBAL)
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
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6c5fc)
Location: mm/memblock.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff81a6c5fc-ffffffff81a6c7bc: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a28b43)
Location: mm/memblock.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff81a28b43-ffffffff81a28d03: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad8a0c)
Location: mm/memblock.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff81ad8a0c-ffffffff81ad8bcc: __next_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __next_mem_range(u64 *idx, int nid, enum memblock_flags flags, struct memblock_type *type_a, struct memblock_type *type_b, phys_addr_t *out_start, phys_addr_t *out_end, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae4ec2)
Location: mm/memblock.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/kernel/check.c:setup_bios_corruption_check
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memblock.c:memblock_find_in_range_node
  - mm/memtest.c:early_memtest
  - mm/memtest.c:early_memtest
```
**Symbols:**

```
ffffffff81ae4ec2-ffffffff81ae5082: __next_mem_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>ulong flags</code> ➡️ <code>enum memblock_flags flags</code>
</li>
</ul>
</details>
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
