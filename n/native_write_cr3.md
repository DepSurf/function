# Function: <code>native_write_cr3</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f6345c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064540)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
**Symbols:**

```
ffffffff81064540-ffffffff81064549: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f8b020)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106455c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
**Symbols:**

```
ffffffff81064190-ffffffff81064199: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81fc640e)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067a3c)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
**Symbols:**

```
ffffffff81067680-ffffffff81067689: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066cbc)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
**Symbols:**

```
ffffffff81066940-ffffffff81066949: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b367)
Location: arch/x86/include/asm/special_insns.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c59c2)
Location: arch/x86/include/asm/special_insns.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8106ab10-ffffffff8106ab19: native_write_cr3 (STB_LOCAL)
ffffffff810804fd-ffffffff81080506: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106e037)
Location: arch/x86/include/asm/special_insns.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efa98)
Location: arch/x86/include/asm/special_insns.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f04ee)
Location: arch/x86/include/asm/special_insns.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8106d7f0-ffffffff8106d7f9: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81074077)
Location: arch/x86/include/asm/special_insns.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6755)
Location: arch/x86/include/asm/special_insns.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a71f6)
Location: arch/x86/include/asm/special_insns.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff81073990-ffffffff81073999: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077bf7)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bedf1)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf8b4)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff81077500-ffffffff81077504: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078c67)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c526a)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5d53)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff81078590-ffffffff81078594: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f9b0)
Location: arch/x86/include/asm/special_insns.h:50
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba17)
Location: arch/x86/include/asm/special_insns.h:50
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8fe1)
Location: arch/x86/include/asm/special_insns.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8107f9b0-ffffffff8107f9b4: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f5e0)
Location: arch/x86/include/asm/special_insns.h:52
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba67)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6a67)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8107f5e0-ffffffff8107f5e4: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810806f0)
Location: arch/x86/include/asm/special_insns.h:52
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff8108c64c)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e14b1)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810806f0-ffffffff810806f4: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108f610)
Location: arch/x86/include/asm/special_insns.h:52
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff8109be8c)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4d43)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8108f610-ffffffff8108f614: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a0380)
Location: arch/x86/include/asm/special_insns.h:52
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff810af3f7)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff834777b5)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810a0380-ffffffff810a038a: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b7ef0)
Location: arch/x86/include/asm/special_insns.h:52
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff810c9837)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0e91)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810b7ef0-ffffffff810b7efa: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810bb0c0)
Location: arch/x86/include/asm/special_insns.h:52
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff810cceb7)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4fa1)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810bb0c0-ffffffff810bb0ca: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810c2510)
Location: arch/x86/include/asm/special_insns.h:52
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff810d5587)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5ba1)
Location: arch/x86/include/asm/special_insns.h:52
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810c2510-ffffffff810c251a: native_write_cr3 (STB_LOCAL)
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
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077c67)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0202)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0ceb)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff81077590-ffffffff81077594: native_write_cr3 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff828881ab)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/kernel/tboot.c (ffffffff8103343a)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81052b4a)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/paravirt.c (ffffffff810677d7)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/init.c (ffffffff828a56fc)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff810769ee)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a83ef)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8e70)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
```
In arch/x86/power/cpu.c (ffffffff81863798)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077c17)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3101)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3bea)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff81077540-ffffffff81077544: native_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_cr3(long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079cd3)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c62a7)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6d90)
Location: arch/x86/include/asm/special_insns.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff810795e0-ffffffff810795e4: native_write_cr3 (STB_LOCAL)
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
