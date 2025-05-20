# Function: <code>kern_pcid</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b21a)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8107a28b)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c59b6)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff8106de90)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8107d90c)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efa8c)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff81073e20)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8108443c)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6749)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff810779c0)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810880db)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bede5)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff81078a30)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81088d7c)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c525e)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ba0a)
Location: arch/x86/mm/tlb.c:104
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ba5a)
Location: arch/x86/mm/tlb.c:103
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108c530)
Location: arch/x86/mm/tlb.c:104
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109bd70)
Location: arch/x86/mm/tlb.c:111
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810af290)
Location: arch/x86/mm/tlb.c:112
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c96a0)
Location: arch/x86/mm/tlb.c:112
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ccd20)
Location: arch/x86/mm/tlb.c:112
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d53ef)
Location: arch/x86/mm/tlb.c:113
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/kernel/paravirt.c (ffffffff81077a30)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087d7c)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b01f6)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff81067710)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810769e7)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a83e3)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff810779e0)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087d2c)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c30f5)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff81079a80)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81089f1c)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c629b)
Location: arch/x86/include/asm/tlbflush.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
</ul>

## Differences
