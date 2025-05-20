# Function: <code>write_gdt_entry</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff81003f0d)
Location: arch/x86/include/asm/paravirt.h:268
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810412db)
Location: arch/x86/include/asm/paravirt.h:268
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064b00)
Location: arch/x86/include/asm/paravirt.h:268
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff816fb1b8)
Location: arch/x86/include/asm/paravirt.h:268
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/entry/vdso/vma.c (ffffffff81003e94)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041204)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810648d3)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81760414)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/entry/vdso/vma.c (ffffffff81003e84)
Location: arch/x86/include/asm/paravirt.h:258
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040c51)
Location: arch/x86/include/asm/paravirt.h:258
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067db3)
Location: arch/x86/include/asm/paravirt.h:258
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8178d414)
Location: arch/x86/include/asm/paravirt.h:258
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/entry/vdso/vma.c (ffffffff81003d10)
Location: arch/x86/include/asm/paravirt.h:258
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/ioport.c (ffffffff8102e979)
Location: arch/x86/include/asm/paravirt.h:258
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81036097)
Location: arch/x86/include/asm/paravirt.h:258
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ebf8)
Location: arch/x86/include/asm/paravirt.h:258
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067102)
Location: arch/x86/include/asm/paravirt.h:258
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff817ab5a6)
Location: arch/x86/include/asm/paravirt.h:258
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/entry/vdso/vma.c (ffffffff81003f60)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/ioport.c (ffffffff81030835)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81038422)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104186a)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b302)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81822a27)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/entry/vdso/vma.c (ffffffff810047cc)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/ioport.c (ffffffff81031ace)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff810398bf)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104314a)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106dfe4)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8186ccb9)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/ioport.c (ffffffff81032dde)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103ac91)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81044604)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81074024)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8188ccc9)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/ioport.c (ffffffff81034bee)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103d251)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046bab)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077b9f)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818d7586)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/ioport.c (ffffffff81035427)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103da11)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104732b)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078c0f)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81909809)
Location: arch/x86/include/asm/paravirt.h:287
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
In arch/x86/kernel/process.c (ffffffff810404e1)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b11b)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107ff0f)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81bba089)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/process.c (ffffffff81040431)
Location: arch/x86/include/asm/paravirt.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a7ec)
Location: arch/x86/include/asm/paravirt.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fb2f)
Location: arch/x86/include/asm/paravirt.h:289
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81bce8f9)
Location: arch/x86/include/asm/paravirt.h:289
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/process.c (ffffffff81041dfb)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c0b6)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080c4f)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81bc22a9)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/process.c (ffffffff810480cb)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81053200)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fb97)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81c928d8)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/process.c (ffffffff810513dd)
Location: arch/x86/include/asm/paravirt.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105ec80)
Location: arch/x86/include/asm/paravirt.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a09d0)
Location: arch/x86/include/asm/paravirt.h:312
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81e42060)
Location: arch/x86/include/asm/paravirt.h:312
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/process.c (ffffffff8105e9d3)
Location: arch/x86/include/asm/paravirt.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d3cf)
Location: arch/x86/include/asm/paravirt.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8690)
Location: arch/x86/include/asm/paravirt.h:312
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8201c860)
Location: arch/x86/include/asm/paravirt.h:312
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/process.c (ffffffff810600c3)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106ed5f)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb890)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8209cef0)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/process.c (ffffffff810668c4)
Location: arch/x86/include/asm/paravirt.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:force_reload_TR
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810760bf)
Location: arch/x86/include/asm/paravirt.h:316
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2ca0)
Location: arch/x86/include/asm/paravirt.h:316
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff82174a60)
Location: arch/x86/include/asm/paravirt.h:316
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/ioport.c (ffffffff81035587)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103db91)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810474ab)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077c0f)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818a8bc9)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
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
In arch/x86/kernel/ioport.c (ffffffff810353e7)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103d9d1)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810472eb)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077bbf)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818fa229)
Location: arch/x86/include/asm/paravirt.h:287
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
In arch/x86/kernel/ioport.c (ffffffff81036384)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103eae8)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810486eb)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079c5f)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8191b389)
Location: arch/x86/include/asm/paravirt.h:287
Inline: True
```
</details>
</li>
</ul>

## Differences
