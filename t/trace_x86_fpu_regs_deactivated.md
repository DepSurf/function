# Function: <code>trace_x86_fpu_regs_deactivated</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102c603)
Location: arch/x86/include/asm/trace/fpu.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039926)
Location: arch/x86/include/asm/trace/fpu.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff8102c817)
Location: arch/x86/include/asm/trace/fpu.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039272)
Location: arch/x86/include/asm/trace/fpu.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff8102aa10)
Location: arch/x86/include/asm/trace/fpu.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810371aa)
Location: arch/x86/include/asm/trace/fpu.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff8102b75f)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039489)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff8102c77f)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103a9c5)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff8102d9f6)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103bec5)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff8102f7c4)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e37c)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff81030124)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103eb3c)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f9bd)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff8103292d)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041dd9)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042c3f)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff81033608)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041df2)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042b84)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff8103519d)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810437f2)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104458d)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff8103a47c)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104997f)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff810414ef)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8105378f)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff8104abd8)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106119f)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff8104b418)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81062b9f)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff81052688)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81069d0f)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/process_64.c (ffffffff81030284)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103ecbc)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fb3d)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff8101fcf4)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102e4bc)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f33d)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff810300e4)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103eafc)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f97d)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff81030f34)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103fd7e)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040c8c)
Location: arch/x86/include/asm/trace/fpu.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
</ul>

## Differences
