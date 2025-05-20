# Function: <code>native_store_gdt</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066f5f)
Location: arch/x86/include/asm/desc.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
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
In arch/x86/kernel/paravirt.c (ffffffff8106b08f)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff81983094)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/kernel/paravirt.c (ffffffff8106dd1f)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff819df5e6)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/kernel/paravirt.c (ffffffff81073d8f)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff8107ca10)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1a526)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/kernel/paravirt.c (ffffffff81077921)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff81080345)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a8a20b)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/kernel/paravirt.c (ffffffff81078991)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff810813ef)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ac14cb)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/kernel/paravirt.c (ffffffff8107fdd1)
Location: arch/x86/include/asm/desc.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff81088332)
Location: arch/x86/include/asm/desc.h:217
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/lib/insn-eval.c (ffffffff815fd92b)
Location: arch/x86/include/asm/desc.h:217
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
In arch/x86/kernel/paravirt.c (ffffffff8107f9f1)
Location: arch/x86/include/asm/desc.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff81bd9512)
Location: arch/x86/include/asm/desc.h:217
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/lib/insn-eval.c (ffffffff816227ab)
Location: arch/x86/include/asm/desc.h:217
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
In arch/x86/kernel/paravirt.c (ffffffff81080b11)
Location: arch/x86/include/asm/desc.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff81bcb49f)
Location: arch/x86/include/asm/desc.h:217
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/lib/insn-eval.c (ffffffff81605f7b)
Location: arch/x86/include/asm/desc.h:217
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
In arch/x86/kernel/paravirt.c (ffffffff8108fa61)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff81ca0b71)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/lib/insn-eval.c (ffffffff8167496b)
Location: arch/x86/include/asm/desc.h:218
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
In arch/x86/kernel/paravirt.c (ffffffff810a076d)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff81e50102)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/lib/insn-eval.c (ffffffff8178f1bb)
Location: arch/x86/include/asm/desc.h:218
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
In arch/x86/kernel/paravirt.c (ffffffff810b83fd)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff810c3c92)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/lib/insn-eval.c (ffffffff8204ccbb)
Location: arch/x86/include/asm/desc.h:218
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
In arch/x86/kernel/paravirt.c (ffffffff810bb52d)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff810c74d2)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/lib/insn-eval.c (ffffffff820cb589)
Location: arch/x86/include/asm/desc.h:218
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
In arch/x86/hyperv/ivm.c (ffffffff8104f2f1)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c293d)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff810cf9a2)
Location: arch/x86/include/asm/desc.h:218
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a5db9)
Location: arch/x86/include/asm/desc.h:218
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
In arch/x86/kernel/paravirt.c (ffffffff81077991)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff810803ef)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a6031b)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/kernel/ioport.c (ffffffff81024ebd)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8102d30e)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036813)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/fault.c (ffffffff8106f33f)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff8186389d)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1d3eb)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/kernel/paravirt.c (ffffffff81077941)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff8108039f)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/lib/insn-eval.c (ffffffff81acc70b)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/kernel/paravirt.c (ffffffff810799e1)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
```
In arch/x86/mm/fault.c (ffffffff810824bf)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ad8c1b)
Location: arch/x86/include/asm/desc.h:222
Inline: True
```
</details>
</li>
</ul>

## Differences
