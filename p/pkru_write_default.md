# Function: <code>pkru_write_default</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81047ea1)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:flush_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81049a3e)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81052a9d)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/process.c (ffffffff81051131)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:flush_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81053bc9)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105e503)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/process.c (ffffffff8105e711)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:flush_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81061669)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106caf9)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/process.c (ffffffff8105fe01)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:flush_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81062f3d)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106e4be)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
In arch/x86/kernel/process.c (ffffffff81066f01)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:flush_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106a229)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81075789)
Location: arch/x86/include/asm/pkru.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
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
