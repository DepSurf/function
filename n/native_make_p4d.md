# Function: <code>native_make_p4d</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:299
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:299
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
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:323
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
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
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
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
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
In arch/x86/xen/mmu_pv.c (ffffffff81029e7c)
Location: arch/x86/include/asm/pgtable_types.h:334
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:334
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:334
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8102a85c)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81c3cbd6)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pud_table
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8102b44c)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81c2f673)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8102fbac)
Location: arch/x86/include/asm/pgtable_types.h:331
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:331
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81d4dd74)
Location: arch/x86/include/asm/pgtable_types.h:331
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:331
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:331
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable_types.h:331
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8103516c)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81f1daf1)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable_types.h:333
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8103cd7c)
Location: arch/x86/include/asm/pgtable_types.h:314
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:314
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:314
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:314
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:314
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable_types.h:314
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8103cc5d)
Location: arch/x86/include/asm/pgtable_types.h:315
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:315
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:315
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:315
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:315
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable_types.h:315
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8104312d)
Location: arch/x86/include/asm/pgtable_types.h:343
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:343
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:343
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:343
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:343
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable_types.h:343
Inline: True
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
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/kaslr.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
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
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
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
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (0)
Location: arch/x86/include/asm/pgtable_types.h:322
Inline: True
```
</details>
</li>
</ul>

## Differences
