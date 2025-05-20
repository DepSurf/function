# Function: <code>text_opcode_size</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (0)
Location: arch/x86/include/asm/text-patching.h:67
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d07e)
Location: arch/x86/include/asm/text-patching.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/text-patching.h:67
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
In arch/x86/kernel/jump_label.c (0)
Location: arch/x86/include/asm/text-patching.h:70
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d51b)
Location: arch/x86/include/asm/text-patching.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/static_call.c (0)
Location: arch/x86/include/asm/text-patching.h:70
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/text-patching.h:70
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
In arch/x86/kernel/jump_label.c (0)
Location: arch/x86/include/asm/text-patching.h:70
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ed54)
Location: arch/x86/include/asm/text-patching.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/static_call.c (0)
Location: arch/x86/include/asm/text-patching.h:70
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/text-patching.h:70
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
In arch/x86/kernel/jump_label.c (0)
Location: arch/x86/include/asm/text-patching.h:70
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81044ac4)
Location: arch/x86/include/asm/text-patching.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/static_call.c (0)
Location: arch/x86/include/asm/text-patching.h:70
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/text-patching.h:70
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
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/text-patching.h:72
Inline: True
```
```
In arch/x86/kernel/jump_label.c (0)
Location: arch/x86/include/asm/text-patching.h:72
Inline: True
```
```
In arch/x86/kernel/static_call.c (0)
Location: arch/x86/include/asm/text-patching.h:72
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/text-patching.h:72
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/text-patching.h:72
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
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/jump_label.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/static_call.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/include/asm/text-patching.h:73
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
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/jump_label.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/static_call.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/text-patching.h:73
Inline: True
```
```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/include/asm/text-patching.h:73
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
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
```
```
In arch/x86/kernel/jump_label.c (0)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
```
```
In arch/x86/kernel/static_call.c (0)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
```
```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/include/asm/text-patching.h:61
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
