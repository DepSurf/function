# Function: <code>trace_x86_fpu_init_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810396f1)
Location: arch/x86/include/asm/trace/fpu.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a710)
Location: arch/x86/include/asm/trace/fpu.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff81039041)
Location: arch/x86/include/asm/trace/fpu.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a028)
Location: arch/x86/include/asm/trace/fpu.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff81036fcd)
Location: arch/x86/include/asm/trace/fpu.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81037e8a)
Location: arch/x86/include/asm/trace/fpu.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff81039361)
Location: arch/x86/include/asm/trace/fpu.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a153)
Location: arch/x86/include/asm/trace/fpu.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff8103a8a1)
Location: arch/x86/include/asm/trace/fpu.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b72b)
Location: arch/x86/include/asm/trace/fpu.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff8103bda1)
Location: arch/x86/include/asm/trace/fpu.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103cb9a)
Location: arch/x86/include/asm/trace/fpu.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e42e)
Location: arch/x86/include/asm/trace/fpu.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103ebee)
Location: arch/x86/include/asm/trace/fpu.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103ed6e)
Location: arch/x86/include/asm/trace/fpu.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8102e56e)
Location: arch/x86/include/asm/trace/fpu.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103ebae)
Location: arch/x86/include/asm/trace/fpu.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103fe4e)
Location: arch/x86/include/asm/trace/fpu.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
</details>
</li>
</ul>

## Differences
