# Function: <code>load_TR_desc</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff810412f2)
Location: arch/x86/include/asm/paravirt.h:225
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff816fb240)
Location: arch/x86/include/asm/paravirt.h:225
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/common.c (ffffffff81041215)
Location: arch/x86/include/asm/paravirt.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff817604a7)
Location: arch/x86/include/asm/paravirt.h:224
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/common.c (ffffffff81040c62)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff8178d4a7)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
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
In arch/x86/kernel/ioport.c (ffffffff8102e9a3)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff810360c1)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ec0d)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff817ab61d)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
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
In arch/x86/kernel/ioport.c (ffffffff8103085f)
Location: arch/x86/include/asm/paravirt.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103844c)
Location: arch/x86/include/asm/paravirt.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104187e)
Location: arch/x86/include/asm/paravirt.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff81822ad2)
Location: arch/x86/include/asm/paravirt.h:211
Inline: True
Inline callers:
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
In arch/x86/kernel/ioport.c (ffffffff81031ad5)
Location: arch/x86/include/asm/paravirt.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff810398c6)
Location: arch/x86/include/asm/paravirt.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043151)
Location: arch/x86/include/asm/paravirt.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff8186ccfa)
Location: arch/x86/include/asm/paravirt.h:211
Inline: True
Inline callers:
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
In arch/x86/kernel/ioport.c (ffffffff81032de5)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103ac98)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810447b9)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff8188cd0a)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
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
In arch/x86/kernel/ioport.c (ffffffff81034bf5)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103d258)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046d8d)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff818d75c5)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
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
In arch/x86/kernel/ioport.c (ffffffff8103542e)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103da18)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104750d)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff81909848)
Location: arch/x86/include/asm/paravirt.h:247
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
In arch/x86/kernel/process.c (ffffffff810404e8)
Location: arch/x86/include/asm/paravirt.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b2d6)
Location: arch/x86/include/asm/paravirt.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff81bba0ca)
Location: arch/x86/include/asm/paravirt.h:253
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff81040438)
Location: arch/x86/include/asm/paravirt.h:251
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a9a8)
Location: arch/x86/include/asm/paravirt.h:251
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/power/cpu.c (ffffffff81bce93a)
Location: arch/x86/include/asm/paravirt.h:251
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff81041e02)
Location: arch/x86/include/asm/paravirt.h:268
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c272)
Location: arch/x86/include/asm/paravirt.h:268
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/power/cpu.c (ffffffff81bc22ea)
Location: arch/x86/include/asm/paravirt.h:268
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff810480d2)
Location: arch/x86/include/asm/paravirt.h:268
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81053319)
Location: arch/x86/include/asm/paravirt.h:268
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/power/cpu.c (ffffffff81c92918)
Location: arch/x86/include/asm/paravirt.h:268
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff810513e3)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105ed96)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/power/cpu.c (ffffffff81e420a0)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8105e9d9)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d4e5)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/power/cpu.c (ffffffff8201c8a0)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff810600c9)
Location: arch/x86/include/asm/paravirt.h:276
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106ee75)
Location: arch/x86/include/asm/paravirt.h:276
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/power/cpu.c (ffffffff8209cf30)
Location: arch/x86/include/asm/paravirt.h:276
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff810668ca)
Location: arch/x86/include/asm/paravirt.h:278
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:force_reload_TR
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810761d5)
Location: arch/x86/include/asm/paravirt.h:278
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
```
In arch/x86/power/cpu.c (ffffffff82174aa0)
Location: arch/x86/include/asm/paravirt.h:278
Inline: True
Inline callers:
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
In arch/x86/kernel/ioport.c (ffffffff8103558e)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103db98)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104768d)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff818a8c08)
Location: arch/x86/include/asm/paravirt.h:247
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
In arch/x86/kernel/ioport.c (ffffffff810353ee)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103d9d8)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810474cd)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff818fa268)
Location: arch/x86/include/asm/paravirt.h:247
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
In arch/x86/kernel/ioport.c (ffffffff8103638b)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103eaef)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810488cd)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff8191b3c8)
Location: arch/x86/include/asm/paravirt.h:247
Inline: True
```
</details>
</li>
</ul>

## Differences
