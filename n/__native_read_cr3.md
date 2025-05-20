# Function: <code>__native_read_cr3</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066cb9)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
**Symbols:**

```
ffffffff81066930-ffffffff81066939: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b364)
Location: arch/x86/include/asm/special_insns.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c59bf)
Location: arch/x86/include/asm/special_insns.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/mm/mem_encrypt.c:native_read_cr3_pa
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8106ab00-ffffffff8106ab09: __native_read_cr3 (STB_LOCAL)
ffffffff810804f4-ffffffff810804fd: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106e034)
Location: arch/x86/include/asm/special_insns.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efa95)
Location: arch/x86/include/asm/special_insns.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f04a7)
Location: arch/x86/include/asm/special_insns.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8106d7e0-ffffffff8106d7e9: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81074074)
Location: arch/x86/include/asm/special_insns.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6752)
Location: arch/x86/include/asm/special_insns.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a71af)
Location: arch/x86/include/asm/special_insns.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff81073980-ffffffff81073989: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077bf4)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bedee)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf86d)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810774f0-ffffffff810774f4: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078c64)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5267)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5d0c)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff81078580-ffffffff81078584: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f9a0)
Location: arch/x86/include/asm/special_insns.h:43
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba14)
Location: arch/x86/include/asm/special_insns.h:43
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8fa4)
Location: arch/x86/include/asm/special_insns.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8107f9a0-ffffffff8107f9a4: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f5d0)
Location: arch/x86/include/asm/special_insns.h:45
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba64)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6a2a)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8107f5d0-ffffffff8107f5d4: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810806e0)
Location: arch/x86/include/asm/special_insns.h:45
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff8108c649)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e1474)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810806e0-ffffffff810806e4: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108f600)
Location: arch/x86/include/asm/special_insns.h:45
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff8109be89)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4d06)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8108f600-ffffffff8108f604: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a0370)
Location: arch/x86/include/asm/special_insns.h:45
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff810af3f4)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477778)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810a0370-ffffffff810a0378: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b7ed0)
Location: arch/x86/include/asm/special_insns.h:45
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff810c9834)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0e4f)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810b7ed0-ffffffff810b7ed8: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810bb0a0)
Location: arch/x86/include/asm/special_insns.h:45
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff810cceb4)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4f5f)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810bb0a0-ffffffff810bb0a8: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810c24f0)
Location: arch/x86/include/asm/special_insns.h:45
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff810d5584)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5b5f)
Location: arch/x86/include/asm/special_insns.h:45
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810c24f0-ffffffff810c24f8: __native_read_cr3 (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077c64)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b01ff)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0ca4)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff81077580-ffffffff81077584: __native_read_cr3 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff82888240)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/process_64.c (ffffffff8102048a)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/paravirt.c (ffffffff810677d4)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/fault.c (ffffffff8106e2d4)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5e2e)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff81076978)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a83ec)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8e29)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
```
In arch/x86/power/cpu.c (ffffffff81863628)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/power/hibernate.c (ffffffff81865341)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077c14)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c30fe)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3ba3)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff81077530-ffffffff81077534: __native_read_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __native_read_cr3();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079cd0)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c62a4)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6d49)
Location: arch/x86/include/asm/special_insns.h:42
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810795d0-ffffffff810795d4: __native_read_cr3 (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
