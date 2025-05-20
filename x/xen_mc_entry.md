# Function: <code>xen_mc_entry</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101ce3e)
Location: arch/x86/xen/multicalls.h:32
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/mmu.c (ffffffff8101ed73)
Location: arch/x86/xen/multicalls.h:32
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
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
In arch/x86/xen/enlighten.c (ffffffff8101c1ab)
Location: arch/x86/xen/multicalls.h:32
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/mmu.c (ffffffff81020ee7)
Location: arch/x86/xen/multicalls.h:32
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_set_domain_pte
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
In arch/x86/xen/enlighten.c (ffffffff8101c87b)
Location: arch/x86/xen/multicalls.h:32
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/mmu.c (ffffffff8102169a)
Location: arch/x86/xen/multicalls.h:32
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_set_domain_pte
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
In arch/x86/xen/mmu.c (ffffffff8101a6d0)
Location: arch/x86/xen/multicalls.h:32
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f66d)
Location: arch/x86/xen/multicalls.h:32
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023c5b)
Location: arch/x86/xen/multicalls.h:32
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_single
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_set_domain_pte
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
In arch/x86/xen/mmu.c (ffffffff8101afa0)
Location: arch/x86/xen/multicalls.h:33
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102040d)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810247df)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/mmu.c (ffffffff8101b7de)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102105b)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810256fe)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff8102074b)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810224be)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff8102228b)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102346e)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff81022bcb)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023f2e)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff81025407)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810268fc)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff81025ad7)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810270ea)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff81027cd5)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029059)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff8102c355)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102d7a9)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff81030ea5)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81032580)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff810382f5)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81039f80)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff81038255)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a010)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff8103e5c5)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810404d0)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff81022d2b)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102408e)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022b8b)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023eee)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
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
In arch/x86/xen/enlighten_pv.c (ffffffff81022f5b)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810243e5)
Location: arch/x86/xen/multicalls.h:33
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
```
</details>
</li>
</ul>

## Differences
