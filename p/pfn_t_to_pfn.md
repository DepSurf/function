# Function: <code>pfn_t_to_pfn</code>

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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:41
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pfn_t.h:41
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/pfn_t.h:41
Inline: True
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:41
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pfn_t.h:41
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/pfn_t.h:41
Inline: True
```
```
In fs/dax.c (ffffffff8129b8ab)
Location: include/linux/pfn_t.h:41
Inline: True
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:47
Inline: True
```
```
In mm/memory.c (ffffffff811f8068)
Location: include/linux/pfn_t.h:47
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (0)
Location: include/linux/pfn_t.h:47
Inline: True
```
```
In fs/dax.c (ffffffff812aa7e4)
Location: include/linux/pfn_t.h:47
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:50
Inline: True
```
```
In mm/memory.c (ffffffff8121049f)
Location: include/linux/pfn_t.h:50
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (0)
Location: include/linux/pfn_t.h:50
Inline: True
```
```
In fs/dax.c (ffffffff812cc9bd)
Location: include/linux/pfn_t.h:50
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
  - fs/dax.c:dax_writeback_mapping_range
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:50
Inline: True
```
```
In mm/memory.c (ffffffff8122fbbd)
Location: include/linux/pfn_t.h:50
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (0)
Location: include/linux/pfn_t.h:50
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:50
Inline: True
```
```
In drivers/dax/super.c (ffffffff816e2220)
Location: include/linux/pfn_t.h:50
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In mm/memory.c (ffffffff812445fd)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/super.c (ffffffff8170563b)
Location: include/linux/pfn_t.h:52
Inline: True
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In mm/memory.c (ffffffff812565c4)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812a21fa)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/super.c (ffffffff8173f777)
Location: include/linux/pfn_t.h:52
Inline: True
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In mm/memory.c (ffffffff81264b54)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812b35aa)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/super.c (ffffffff81763957)
Location: include/linux/pfn_t.h:52
Inline: True
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
In arch/x86/mm/pat/memtype.c (ffffffff810906b0)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
```
```
In mm/memory.c (ffffffff81292dc2)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812e8efa)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff8138c5d0)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
  - fs/dax.c:dax_insert_entry
```
```
In drivers/dax/super.c (ffffffff8182377e)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
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
In arch/x86/mm/pat/memtype.c (ffffffff810903b0)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
```
```
In mm/memory.c (ffffffff8129d662)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812f436a)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff8139dd00)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
  - fs/dax.c:dax_insert_entry
```
```
In drivers/dax/super.c (ffffffff818324ad)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
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
In arch/x86/mm/pat/memtype.c (ffffffff81090f20)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
```
```
In mm/memory.c (ffffffff812a2c94)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812fa5aa)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
```
```
In fs/dax.c (ffffffff813a4f10)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
  - fs/dax.c:dax_insert_entry
```
```
In drivers/dax/super.c (ffffffff8181529d)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
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
In arch/x86/mm/pat/memtype.c (ffffffff810a0a98)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
```
```
In mm/memory.c (ffffffff812e6104)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff8134440a)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff813f6a58)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_insert_entry
```
```
In drivers/dax/super.c (ffffffff8189fac3)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
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
In arch/x86/mm/pat/memtype.c (ffffffff810b4a88)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
```
```
In mm/memory.c (ffffffff81345704)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff813b9920)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff81469093)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_insert_entry
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
In arch/x86/mm/pat/memtype.c (ffffffff810cf858)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
```
```
In mm/memory.c (ffffffff813bda54)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff8143be04)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff814f7b4d)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_direct_access
  - fs/dax.c:dax_insert_entry
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
In arch/x86/mm/pat/memtype.c (ffffffff810d2e38)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
```
```
In mm/memory.c (ffffffff813f2765)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff81471917)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff8152e99d)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_direct_access
  - fs/dax.c:dax_insert_entry
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
In arch/x86/mm/pat/memtype.c (ffffffff810db5c8)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
```
```
In mm/memory.c (ffffffff8141d4a5)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff814a10c7)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff8156387d)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_direct_access
  - fs/dax.c:dax_insert_entry
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
In mm/memory.c (ffff8000102fb578)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffff800010354670)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/pfn_t.h:52
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
In mm/memory.c (c0519fe4)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In drivers/dax/super.c (0)
Location: include/linux/pfn_t.h:52
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
In mm/memory.c (c0000000003c684c)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (c00000000043b4bc)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/super.c (c000000000a19f90)
Location: include/linux/pfn_t.h:52
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
In mm/memory.c (ffffffe00020ac6e)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/pfn_t.h:52
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In mm/memory.c (ffffffff8125d1a4)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812abb8a)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/super.c (ffffffff81718047)
Location: include/linux/pfn_t.h:52
Inline: True
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In mm/memory.c (ffffffff8124f604)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff8129d475)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/super.c (ffffffff816f0577)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/device.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In mm/memory.c (ffffffff8125af44)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812a999a)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/super.c (ffffffff81756e17)
Location: include/linux/pfn_t.h:52
Inline: True
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
In arch/x86/mm/pat.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In mm/memory.c (ffffffff8126a914)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812b97ee)
Location: include/linux/pfn_t.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:52
Inline: True
```
```
In drivers/dax/super.c (ffffffff81772277)
Location: include/linux/pfn_t.h:52
Inline: True
```
</details>
</li>
</ul>

## Differences
