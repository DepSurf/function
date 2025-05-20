# Function: <code>vma_pkey</code>

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
In arch/x86/kernel/setup.c (ffffffff810323c2)
Location: arch/x86/include/asm/mmu_context.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:arch_show_smap
```
```
In arch/x86/mm/fault.c (ffffffff8106b44f)
Location: arch/x86/include/asm/mmu_context.h:198
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:force_sig_info_fault
```
```
In arch/x86/mm/pkeys.c (ffffffff81077958)
Location: arch/x86/include/asm/mmu_context.h:198
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff811d5ed4)
Location: arch/x86/include/asm/mmu_context.h:198
Inline: True
Inline callers:
  - mm/gup.c:vma_permits_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811dad07)
Location: arch/x86/include/asm/mmu_context.h:198
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
In arch/x86/kernel/setup.c (ffffffff81032042)
Location: arch/x86/include/asm/mmu_context.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:arch_show_smap
```
```
In arch/x86/mm/fault.c (ffffffff8106f0fc)
Location: arch/x86/include/asm/mmu_context.h:209
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:force_sig_info_fault
```
```
In arch/x86/mm/pkeys.c (ffffffff8107b713)
Location: arch/x86/include/asm/mmu_context.h:209
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff811e47a6)
Location: arch/x86/include/asm/mmu_context.h:209
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811ea8cc)
Location: arch/x86/include/asm/mmu_context.h:209
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
In arch/x86/kernel/setup.c (ffffffff81030283)
Location: arch/x86/include/asm/mmu_context.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:arch_show_smap
```
```
In arch/x86/mm/fault.c (ffffffff8106e8f6)
Location: arch/x86/include/asm/mmu_context.h:231
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:force_sig_info_fault
```
```
In arch/x86/mm/pkeys.c (ffffffff81079ed3)
Location: arch/x86/include/asm/mmu_context.h:231
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff811eec04)
Location: arch/x86/include/asm/mmu_context.h:231
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f67a9)
Location: arch/x86/include/asm/mmu_context.h:231
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
In arch/x86/kernel/setup.c (ffffffff81032613)
Location: arch/x86/include/asm/mmu_context.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:arch_show_smap
```
```
In arch/x86/mm/fault.c (ffffffff810739a0)
Location: arch/x86/include/asm/mmu_context.h:291
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81080143)
Location: arch/x86/include/asm/mmu_context.h:291
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff812050dc)
Location: arch/x86/include/asm/mmu_context.h:291
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8120ec4e)
Location: arch/x86/include/asm/mmu_context.h:291
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
In arch/x86/mm/fault.c (ffffffff8107629e)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
```
```
In mm/gup.c (ffffffff8122601b)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81230384)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff81317b81)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
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
In arch/x86/mm/fault.c (ffffffff8107c562)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
```
```
In mm/gup.c (ffffffff8123978b)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81242d34)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff8132ef5b)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff8107faf7)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
```
```
In mm/gup.c (ffffffff8124a814)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81254bbd)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff813569cc)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff81080b87)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
```
```
In mm/gup.c (ffffffff81258ce4)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8126318a)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff8136ec8c)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff81087b5f)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81094949)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff812877f1)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81294ef9)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff813b6215)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff8108826d)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81093d39)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff81291652)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8129f7e8)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff813c7e4e)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff81088d98)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810946f9)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff81296b6f)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812a47eb)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff813ceb0e)
Location: arch/x86/include/asm/pkeys.h:129
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff81098216)
Location: arch/x86/include/asm/pkeys.h:126
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810a46a9)
Location: arch/x86/include/asm/pkeys.h:126
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff812d7562)
Location: arch/x86/include/asm/pkeys.h:126
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff812e5a9d)
Location: arch/x86/include/asm/pkeys.h:126
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff8141fdcd)
Location: arch/x86/include/asm/pkeys.h:126
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff810aae7b)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810b8f01)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff8133720e)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff81347d85)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff81497d0d)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff810c4b71)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810d4821)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff813aeba7)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813c01db)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff8152c1ce)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff810c6c1e)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810d7d31)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff813e2c5c)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813f4ece)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff8156458e)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff810cf0b3)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810e05b1)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
```
```
In mm/gup.c (ffffffff8140d49c)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff81421564)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff8159abf4)
Location: arch/x86/include/asm/pkeys.h:118
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: include/linux/pkeys.h:16
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: include/linux/pkeys.h:16
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: include/linux/pkeys.h:16
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: include/linux/pkeys.h:16
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
In arch/x86/mm/fault.c (ffffffff8107fb87)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
```
```
In mm/gup.c (ffffffff81251334)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125b7da)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff8136726c)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff8106ebea)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
```
```
In mm/gup.c (ffffffff81244224)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124dda4)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff81357f0c)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff8107fb37)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
```
```
In mm/gup.c (ffffffff8124f0d4)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125957a)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff81364d3c)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
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
In arch/x86/mm/fault.c (ffffffff81081c2f)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
```
```
In mm/gup.c (ffffffff8125ea44)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81268f84)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/proc/task_mmu.c (ffffffff813787ac)
Location: arch/x86/include/asm/pkeys.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
```
</details>
</li>
</ul>

## Differences
