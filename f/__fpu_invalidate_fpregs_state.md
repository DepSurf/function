# Function: <code>__fpu_invalidate_fpregs_state</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103911f)
Location: arch/x86/include/asm/fpu/internal.h:503
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_begin
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
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
In arch/x86/kernel/fpu/core.c (ffffffff8103708f)
Location: arch/x86/include/asm/fpu/internal.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_begin
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
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
In arch/x86/kernel/fpu/core.c (ffffffff8103934a)
Location: arch/x86/include/asm/fpu/internal.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
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
In arch/x86/kernel/fpu/core.c (ffffffff8103a88a)
Location: arch/x86/include/asm/fpu/internal.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
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
In arch/x86/kernel/fpu/core.c (ffffffff8103bd8a)
Location: arch/x86/include/asm/fpu/internal.h:494
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e2ed)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f163)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff8103eaad)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f7cc)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
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
In arch/x86/kernel/fpu/core.c (ffffffff81041d4d)
Location: arch/x86/include/asm/fpu/internal.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042b4e)
Location: arch/x86/include/asm/fpu/internal.h:509
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
In arch/x86/kernel/fpu/core.c (ffffffff81041d7d)
Location: arch/x86/include/asm/fpu/internal.h:476
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042a99)
Location: arch/x86/include/asm/fpu/internal.h:476
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81044184)
Location: arch/x86/include/asm/fpu/internal.h:476
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:update_pasid
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
In arch/x86/kernel/fpu/core.c (ffffffff8104377d)
Location: arch/x86/include/asm/fpu/internal.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044487)
Location: arch/x86/include/asm/fpu/internal.h:467
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
In arch/x86/kernel/fpu/regset.c (ffffffff8104a452)
Location: arch/x86/include/asm/fpu/internal.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a96e)
Location: arch/x86/include/asm/fpu/internal.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
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
In arch/x86/kernel/fpu/regset.c (ffffffff810545f2)
Location: arch/x86/kernel/fpu/context.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054e68)
Location: arch/x86/kernel/fpu/context.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
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
In arch/x86/kernel/fpu/regset.c (ffffffff81062202)
Location: arch/x86/kernel/fpu/context.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810629be)
Location: arch/x86/kernel/fpu/context.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff8106202d)
Location: arch/x86/kernel/fpu/context.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81063ab5)
Location: arch/x86/kernel/fpu/context.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810643c2)
Location: arch/x86/kernel/fpu/context.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff81068ffd)
Location: arch/x86/kernel/fpu/context.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8106afe5)
Location: arch/x86/kernel/fpu/context.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:ssp_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b8b8)
Location: arch/x86/kernel/fpu/context.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ec2d)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f94c)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
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
In arch/x86/kernel/fpu/core.c (ffffffff8102e42d)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f14c)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ea6d)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f78c)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
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
In arch/x86/kernel/fpu/core.c (ffffffff8103fccd)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040a7c)
Location: arch/x86/include/asm/fpu/internal.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
</ul>

## Differences
