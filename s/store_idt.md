# Function: <code>store_idt</code>

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
In arch/x86/power/cpu.c (ffffffff816faf23)
Location: arch/x86/include/asm/paravirt.h:241
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
In arch/x86/power/cpu.c (ffffffff81760147)
Location: arch/x86/include/asm/paravirt.h:240
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
In arch/x86/power/cpu.c (ffffffff8178d147)
Location: arch/x86/include/asm/paravirt.h:231
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
In arch/x86/power/cpu.c (ffffffff817ab2b7)
Location: arch/x86/include/asm/paravirt.h:231
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
In arch/x86/power/cpu.c (ffffffff818227a7)
Location: arch/x86/include/asm/desc.h:227
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
In arch/x86/power/cpu.c (ffffffff8186c9e7)
Location: arch/x86/include/asm/desc.h:227
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
In arch/x86/mm/fault.c (ffffffff8107ca09)
Location: arch/x86/include/asm/desc.h:227
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff8188c9f7)
Location: arch/x86/include/asm/desc.h:227
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
In arch/x86/mm/fault.c (ffffffff81080341)
Location: arch/x86/include/asm/desc.h:227
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff818d7367)
Location: arch/x86/include/asm/desc.h:227
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
In arch/x86/mm/fault.c (ffffffff810813eb)
Location: arch/x86/include/asm/desc.h:227
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff819099f7)
Location: arch/x86/include/asm/desc.h:227
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
In arch/x86/mm/fault.c (ffffffff8108832e)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81bba127)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/mm/fault.c (ffffffff81bd950e)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81bce99c)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/mm/fault.c (ffffffff81bcb49b)
Location: arch/x86/include/asm/desc.h:222
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81bc234c)
Location: arch/x86/include/asm/desc.h:222
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
In arch/x86/mm/fault.c (ffffffff81ca0b6d)
Location: arch/x86/include/asm/desc.h:223
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81c929ac)
Location: arch/x86/include/asm/desc.h:223
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
In arch/x86/mm/fault.c (ffffffff81e500fe)
Location: arch/x86/include/asm/desc.h:223
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81e422fc)
Location: arch/x86/include/asm/desc.h:223
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
In arch/x86/mm/fault.c (ffffffff810c3c8e)
Location: arch/x86/include/asm/desc.h:223
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff8201cccc)
Location: arch/x86/include/asm/desc.h:223
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
In arch/x86/mm/fault.c (ffffffff810c74ce)
Location: arch/x86/include/asm/desc.h:223
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff8209d35c)
Location: arch/x86/include/asm/desc.h:223
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
In arch/x86/mm/fault.c (ffffffff810cf99e)
Location: arch/x86/include/asm/desc.h:223
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff82174b5c)
Location: arch/x86/include/asm/desc.h:223
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
In arch/x86/mm/fault.c (ffffffff810803eb)
Location: arch/x86/include/asm/desc.h:227
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff818a8db7)
Location: arch/x86/include/asm/desc.h:227
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/mm/fault.c (ffffffff8106f33b)
Location: arch/x86/include/asm/desc.h:227
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff81863535)
Location: arch/x86/include/asm/desc.h:227
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/mm/fault.c (ffffffff8108039b)
Location: arch/x86/include/asm/desc.h:227
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff818fa417)
Location: arch/x86/include/asm/desc.h:227
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
In arch/x86/mm/fault.c (ffffffff810824bb)
Location: arch/x86/include/asm/desc.h:227
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff8191b577)
Location: arch/x86/include/asm/desc.h:227
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
</ul>

## Differences
