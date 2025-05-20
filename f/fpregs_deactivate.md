# Function: <code>fpregs_deactivate</code>

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
In arch/x86/kernel/fpu/core.c (ffffffff8103a20f)
Location: arch/x86/include/asm/fpu/internal.h:570
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/fpu/core.c (ffffffff81039916)
Location: arch/x86/include/asm/fpu/internal.h:569
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/fpu/core.c (ffffffff81039262)
Location: arch/x86/include/asm/fpu/internal.h:517
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/fpu/core.c (ffffffff81037192)
Location: arch/x86/include/asm/fpu/internal.h:527
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/fpu/core.c (ffffffff8103947d)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/fpu/core.c (ffffffff8103a9b9)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103beb9)
Location: arch/x86/include/asm/fpu/internal.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e370)
Location: arch/x86/include/asm/fpu/internal.h:519
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
In arch/x86/kernel/fpu/core.c (ffffffff8103eb30)
Location: arch/x86/include/asm/fpu/internal.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f9b1)
Location: arch/x86/include/asm/fpu/internal.h:519
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
In arch/x86/kernel/fpu/core.c (ffffffff81041dcd)
Location: arch/x86/include/asm/fpu/internal.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042c33)
Location: arch/x86/include/asm/fpu/internal.h:523
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
In arch/x86/kernel/fpu/core.c (ffffffff81041de6)
Location: arch/x86/include/asm/fpu/internal.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042b78)
Location: arch/x86/include/asm/fpu/internal.h:490
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
In arch/x86/kernel/fpu/core.c (ffffffff810437e6)
Location: arch/x86/include/asm/fpu/internal.h:481
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044581)
Location: arch/x86/include/asm/fpu/internal.h:481
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81049973)
Location: arch/x86/include/asm/fpu/internal.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81053783)
Location: arch/x86/kernel/fpu/context.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81061193)
Location: arch/x86/kernel/fpu/context.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81062b93)
Location: arch/x86/kernel/fpu/context.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81069d03)
Location: arch/x86/kernel/fpu/context.h:41
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ecb0)
Location: arch/x86/include/asm/fpu/internal.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fb31)
Location: arch/x86/include/asm/fpu/internal.h:519
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
In arch/x86/kernel/fpu/core.c (ffffffff8102e4b0)
Location: arch/x86/include/asm/fpu/internal.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f331)
Location: arch/x86/include/asm/fpu/internal.h:519
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
In arch/x86/kernel/fpu/core.c (ffffffff8103eaf0)
Location: arch/x86/include/asm/fpu/internal.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f971)
Location: arch/x86/include/asm/fpu/internal.h:519
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
In arch/x86/kernel/fpu/core.c (ffffffff8103fd72)
Location: arch/x86/include/asm/fpu/internal.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040c80)
Location: arch/x86/include/asm/fpu/internal.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
</ul>

## Differences
