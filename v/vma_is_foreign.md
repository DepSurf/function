# Function: <code>vma_is_foreign</code>

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
In arch/x86/mm/fault.c (ffffffff8106b33d)
Location: arch/x86/include/asm/mmu_context.h:230
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff811d5ea3)
Location: arch/x86/include/asm/mmu_context.h:230
Inline: True
Inline callers:
  - mm/gup.c:vma_permits_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811daae7)
Location: arch/x86/include/asm/mmu_context.h:230
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
In arch/x86/mm/fault.c (ffffffff8106efb0)
Location: arch/x86/include/asm/mmu_context.h:244
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff811e46d4)
Location: arch/x86/include/asm/mmu_context.h:244
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811ea65b)
Location: arch/x86/include/asm/mmu_context.h:244
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
In arch/x86/mm/fault.c (ffffffff8106e721)
Location: arch/x86/include/asm/mmu_context.h:254
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff811eeb34)
Location: arch/x86/include/asm/mmu_context.h:254
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f676e)
Location: arch/x86/include/asm/mmu_context.h:254
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
In arch/x86/mm/fault.c (ffffffff810737c8)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81205067)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8120ec13)
Location: arch/x86/include/asm/mmu_context.h:314
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
In arch/x86/mm/fault.c (ffffffff81076102)
Location: arch/x86/include/asm/mmu_context.h:300
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81225f60)
Location: arch/x86/include/asm/mmu_context.h:300
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81230363)
Location: arch/x86/include/asm/mmu_context.h:300
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
In arch/x86/mm/fault.c (ffffffff8107c3d0)
Location: arch/x86/include/asm/mmu_context.h:313
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff812396d0)
Location: arch/x86/include/asm/mmu_context.h:313
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81242d13)
Location: arch/x86/include/asm/mmu_context.h:313
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
In arch/x86/mm/fault.c (ffffffff8107f9b3)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8124a76c)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81254b9d)
Location: arch/x86/include/asm/mmu_context.h:314
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
In arch/x86/mm/fault.c (ffffffff81080a43)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81258c3c)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81263162)
Location: arch/x86/include/asm/mmu_context.h:314
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
In arch/x86/mm/fault.c (ffffffff81087a0c)
Location: include/linux/mm.h:636
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81287749)
Location: include/linux/mm.h:636
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81294ed9)
Location: include/linux/mm.h:636
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
In arch/x86/mm/fault.c (ffffffff8108812a)
Location: include/linux/mm.h:669
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8129158d)
Location: include/linux/mm.h:669
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8129f7bf)
Location: include/linux/mm.h:669
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
In arch/x86/mm/fault.c (ffffffff81088bf2)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81296aad)
Location: include/linux/mm.h:692
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812a47c2)
Location: include/linux/mm.h:692
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
In arch/x86/mm/fault.c (ffffffff8109802b)
Location: include/linux/mm.h:693
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff812d74a8)
Location: include/linux/mm.h:693
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff812e5a74)
Location: include/linux/mm.h:693
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
In arch/x86/mm/fault.c (ffffffff810aac67)
Location: include/linux/mm.h:645
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81337144)
Location: include/linux/mm.h:645
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff81347d5c)
Location: include/linux/mm.h:645
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
In arch/x86/mm/fault.c (ffffffff810c4957)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff813aead4)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813c01b2)
Location: include/linux/mm.h:655
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
In arch/x86/mm/fault.c (ffffffff810c6bce)
Location: include/linux/mm.h:856
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff813e2b8e)
Location: include/linux/mm.h:856
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813f4ea6)
Location: include/linux/mm.h:856
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
In arch/x86/mm/fault.c (ffffffff810cf04e)
Location: include/linux/mm.h:922
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8140d3ce)
Location: include/linux/mm.h:922
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff8142153c)
Location: include/linux/mm.h:922
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/mm/fault.c (ffffffff8107fa43)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8125128c)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125b7b2)
Location: arch/x86/include/asm/mmu_context.h:314
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
In arch/x86/mm/fault.c (ffffffff8106eab2)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8124417c)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124dd7c)
Location: arch/x86/include/asm/mmu_context.h:314
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
In arch/x86/mm/fault.c (ffffffff8107f9f3)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8124f02c)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81259552)
Location: arch/x86/include/asm/mmu_context.h:314
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
In arch/x86/mm/fault.c (ffffffff81081aea)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8125e99c)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81268f5c)
Location: arch/x86/include/asm/mmu_context.h:314
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
</ul>

## Differences
