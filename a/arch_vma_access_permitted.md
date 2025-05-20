# Function: <code>arch_vma_access_permitted</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b336)
Location: arch/x86/include/asm/mmu_context.h:245
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff811d5e96)
Location: arch/x86/include/asm/mmu_context.h:245
Inline: True
Inline callers:
  - mm/gup.c:vma_permits_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811daad9)
Location: arch/x86/include/asm/mmu_context.h:245
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106efa9)
Location: arch/x86/include/asm/mmu_context.h:259
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff811e46d4)
Location: arch/x86/include/asm/mmu_context.h:259
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811ea64d)
Location: arch/x86/include/asm/mmu_context.h:259
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e71a)
Location: arch/x86/include/asm/mmu_context.h:269
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff811eeb34)
Location: arch/x86/include/asm/mmu_context.h:269
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f66c4)
Location: arch/x86/include/asm/mmu_context.h:269
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810737c1)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8120505d)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8120eb64)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810760fb)
Location: arch/x86/include/asm/mmu_context.h:315
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81225f56)
Location: arch/x86/include/asm/mmu_context.h:315
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81230321)
Location: arch/x86/include/asm/mmu_context.h:315
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107c3c9)
Location: arch/x86/include/asm/mmu_context.h:328
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff812396c6)
Location: arch/x86/include/asm/mmu_context.h:328
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81242cd1)
Location: arch/x86/include/asm/mmu_context.h:328
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f9ac)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8124a762)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81254b5a)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080a3c)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81258c32)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812630ba)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81087a05)
Location: arch/x86/include/asm/mmu_context.h:204
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8128773f)
Location: arch/x86/include/asm/mmu_context.h:204
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81294e9a)
Location: arch/x86/include/asm/mmu_context.h:204
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81088123)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81291583)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8129f723)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81088beb)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81296aa3)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812a4726)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81098024)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff812d74a3)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff812e59d6)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810aac60)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8133713f)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff81347cc8)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c4950)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff813aeacf)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813c00ed)
Location: arch/x86/include/asm/mmu_context.h:207
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c6bc8)
Location: arch/x86/include/asm/mmu_context.h:248
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff813e2b89)
Location: arch/x86/include/asm/mmu_context.h:248
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813f4de0)
Location: arch/x86/include/asm/mmu_context.h:248
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810cf048)
Location: arch/x86/include/asm/mmu_context.h:249
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8140d3c9)
Location: arch/x86/include/asm/mmu_context.h:249
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff81421476)
Location: arch/x86/include/asm/mmu_context.h:249
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/asm-generic/mm_hooks.h:30
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/mm_hooks.h:30
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/asm-generic/mm_hooks.h:30
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/mm_hooks.h:30
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: arch/powerpc/include/asm/mmu_context.h:251
Inline: True
```
```
In mm/memory.c (0)
Location: arch/powerpc/include/asm/mmu_context.h:251
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/asm-generic/mm_hooks.h:30
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/mm_hooks.h:30
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107fa3c)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81251282)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125b70a)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106eaab)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81244172)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124dcd4)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f9ec)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8124f022)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812594aa)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81081ae3)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8125e992)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81268eb4)
Location: arch/x86/include/asm/mmu_context.h:329
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
</ul>

## Differences
