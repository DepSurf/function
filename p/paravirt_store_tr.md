# Function: <code>paravirt_store_tr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff816faf5c)
Location: arch/x86/include/asm/paravirt.h:245
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81760180)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff8178d180)
Location: arch/x86/include/asm/paravirt.h:235
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff817ab2f0)
Location: arch/x86/include/asm/paravirt.h:235
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818227d9)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff8186ca19)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/mm/fault.c (ffffffff8107ca55)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff8188ca29)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/mm/fault.c (ffffffff8108037e)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff818d7399)
Location: arch/x86/include/asm/paravirt.h:275
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
In arch/x86/mm/fault.c (ffffffff81081428)
Location: arch/x86/include/asm/paravirt.h:263
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff81909a29)
Location: arch/x86/include/asm/paravirt.h:263
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/mm/fault.c (ffffffff8108836b)
Location: arch/x86/include/asm/paravirt.h:269
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81bba159)
Location: arch/x86/include/asm/paravirt.h:269
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
In arch/x86/mm/fault.c (ffffffff81bd954b)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81bce9ce)
Location: arch/x86/include/asm/paravirt.h:267
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
In arch/x86/mm/fault.c (ffffffff81bcb4d8)
Location: arch/x86/include/asm/paravirt.h:284
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81bc237e)
Location: arch/x86/include/asm/paravirt.h:284
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
In arch/x86/mm/fault.c (ffffffff81ca0baa)
Location: arch/x86/include/asm/paravirt.h:284
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81c929ea)
Location: arch/x86/include/asm/paravirt.h:284
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
In arch/x86/mm/fault.c (ffffffff81e5013a)
Location: arch/x86/include/asm/paravirt.h:290
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81e4233a)
Location: arch/x86/include/asm/paravirt.h:290
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
In arch/x86/mm/fault.c (ffffffff810c3ccb)
Location: arch/x86/include/asm/paravirt.h:290
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff8201cd0a)
Location: arch/x86/include/asm/paravirt.h:290
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
In arch/x86/mm/fault.c (ffffffff810c750b)
Location: arch/x86/include/asm/paravirt.h:292
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff8209d39a)
Location: arch/x86/include/asm/paravirt.h:292
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
In arch/x86/mm/fault.c (ffffffff810cf9db)
Location: arch/x86/include/asm/paravirt.h:294
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff82174b9a)
Location: arch/x86/include/asm/paravirt.h:294
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
In arch/x86/mm/fault.c (ffffffff81080428)
Location: arch/x86/include/asm/paravirt.h:263
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff818a8de9)
Location: arch/x86/include/asm/paravirt.h:263
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/mm/fault.c (ffffffff810803d8)
Location: arch/x86/include/asm/paravirt.h:263
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff818fa449)
Location: arch/x86/include/asm/paravirt.h:263
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/mm/fault.c (ffffffff810824f8)
Location: arch/x86/include/asm/paravirt.h:263
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff8191b5a9)
Location: arch/x86/include/asm/paravirt.h:263
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
</ul>

## Differences
