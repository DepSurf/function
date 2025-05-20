# Function: <code>get_locked_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c197d)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff811c33b6)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd45a)
Location: include/linux/mm.h:1558
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff811df13d)
Location: include/linux/mm.h:1558
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/memory.c (ffffffff811ecf4a)
Location: include/linux/mm.h:1532
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff811eef53)
Location: include/linux/mm.h:1532
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/memory.c (ffffffff811f8005)
Location: include/linux/mm.h:1564
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff811f9efa)
Location: include/linux/mm.h:1564
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In arch/x86/kernel/ldt.c (ffffffff81031db3)
Location: include/linux/mm.h:1638
Inline: True
```
```
In mm/memory.c (ffffffff81210175)
Location: include/linux/mm.h:1638
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8121234a)
Location: include/linux/mm.h:1638
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In arch/x86/kernel/ldt.c (ffffffff81033041)
Location: include/linux/mm.h:1725
Inline: True
```
```
In mm/memory.c (ffffffff8122f881)
Location: include/linux/mm.h:1725
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff812330ff)
Location: include/linux/mm.h:1725
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In arch/x86/kernel/ldt.c (ffffffff81034833)
Location: include/linux/mm.h:1795
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In mm/memory.c (ffffffff8124426e)
Location: include/linux/mm.h:1795
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff812468cd)
Location: include/linux/mm.h:1795
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In arch/x86/kernel/ldt.c (ffffffff810366db)
Location: include/linux/mm.h:1790
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103980c)
Location: include/linux/mm.h:1790
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff828bbb1b)
Location: include/linux/mm.h:1790
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff81256220)
Location: include/linux/mm.h:1790
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff81258b6f)
Location: include/linux/mm.h:1790
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In arch/x86/kernel/ldt.c (ffffffff81036f0b)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff81039fdd)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff828c1fc2)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff812647b0)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8126703f)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In arch/x86/kernel/ldt.c (ffffffff81038b0d)
Location: include/linux/mm.h:1994
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:unmap_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff8103cc44)
Location: include/linux/mm.h:1994
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff82ce5386)
Location: include/linux/mm.h:1994
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff81292a20)
Location: include/linux/mm.h:1994
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
```
In mm/mlock.c (ffffffff812969d0)
Location: include/linux/mm.h:1994
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
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
In arch/x86/kernel/ldt.c (ffffffff81039703)
Location: include/linux/mm.h:2039
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d0f2)
Location: include/linux/mm.h:2039
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff82fd2bdc)
Location: include/linux/mm.h:2039
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff8129d34d)
Location: include/linux/mm.h:2039
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
```
In mm/mlock.c (ffffffff812a1840)
Location: include/linux/mm.h:2039
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
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
In arch/x86/kernel/ldt.c (ffffffff8103b1d0)
Location: include/linux/mm.h:2047
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e937)
Location: include/linux/mm.h:2047
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff831dd82b)
Location: include/linux/mm.h:2047
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff812a2a0d)
Location: include/linux/mm.h:2047
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff812a7000)
Location: include/linux/mm.h:2047
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
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
In arch/x86/kernel/ldt.c (ffffffff81040c1e)
Location: include/linux/mm.h:2076
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff810446a7)
Location: include/linux/mm.h:2076
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff832c0a4b)
Location: include/linux/mm.h:2076
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff812e5e5d)
Location: include/linux/mm.h:2076
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff812e84d0)
Location: include/linux/mm.h:2076
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
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
In arch/x86/kernel/ldt.c (ffffffff81048575)
Location: include/linux/mm.h:2154
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff8104ccc6)
Location: include/linux/mm.h:2154
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff83472fe9)
Location: include/linux/mm.h:2154
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff81345445)
Location: include/linux/mm.h:2154
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
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
In arch/x86/kernel/ldt.c (ffffffff810532d5)
Location: include/linux/mm.h:2318
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff810590d4)
Location: include/linux/mm.h:2318
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff83e9a7bf)
Location: include/linux/mm.h:2318
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff813bd6d5)
Location: include/linux/mm.h:2318
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
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
In arch/x86/kernel/ldt.c (ffffffff810542af)
Location: include/linux/mm.h:2638
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a682)
Location: include/linux/mm.h:2638
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff836be1dd)
Location: include/linux/mm.h:2638
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff813f23b5)
Location: include/linux/mm.h:2638
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
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
In arch/x86/kernel/ldt.c (ffffffff8105b4e3)
Location: include/linux/mm.h:2679
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff810618d7)
Location: include/linux/mm.h:2679
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff838eec9d)
Location: include/linux/mm.h:2679
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff8141d045)
Location: include/linux/mm.h:2679
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
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
In mm/memory.c (ffff8000102fb550)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffff8000102fe2c8)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/memory.c (c0519d68)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_page
```
```
In mm/mlock.c (c051d324)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/memory.c (c0000000003c6428)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (c0000000003c9a3c)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/memory.c (ffffffe00020ac4a)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffe00020c7b2)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In arch/x86/kernel/ldt.c (ffffffff8103706b)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a13d)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff828acf98)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff8125ce00)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8125f68f)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In arch/x86/kernel/ldt.c (ffffffff81026932)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff81029a0c)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff828a525f)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff8124f2bc)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff81251aaf)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In arch/x86/kernel/ldt.c (ffffffff81036ecb)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff81039f9d)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff828bfe97)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff8125aba0)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8125d42f)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
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
In arch/x86/kernel/ldt.c (ffffffff81037ecb)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103af9d)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init.c (ffffffff828c2fe4)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In mm/memory.c (ffffffff8126a570)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8126ce15)
Location: include/linux/mm.h:1762
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
</ul>

## Differences
