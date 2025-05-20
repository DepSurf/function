# Function: <code>int3_emulate_ret</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81c369da)
Location: arch/x86/include/asm/text-patching.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
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
In arch/x86/kernel/alternative.c (ffffffff81c28e7d)
Location: arch/x86/include/asm/text-patching.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a765)
Location: arch/x86/include/asm/text-patching.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
In arch/x86/kernel/alternative.c (ffffffff81d4700d)
Location: arch/x86/include/asm/text-patching.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810888b5)
Location: arch/x86/include/asm/text-patching.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
In arch/x86/kernel/alternative.c (ffffffff81f155ef)
Location: arch/x86/include/asm/text-patching.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81098ab5)
Location: arch/x86/include/asm/text-patching.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
In arch/x86/kernel/alternative.c (ffffffff820bcae8)
Location: arch/x86/include/asm/text-patching.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810af255)
Location: arch/x86/include/asm/text-patching.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
In arch/x86/kernel/alternative.c (ffffffff8213e3e6)
Location: arch/x86/include/asm/text-patching.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810b2255)
Location: arch/x86/include/asm/text-patching.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
In arch/x86/kernel/alternative.c (ffffffff822203d6)
Location: arch/x86/include/asm/text-patching.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810b9685)
Location: arch/x86/include/asm/text-patching.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
