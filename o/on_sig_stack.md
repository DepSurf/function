# Function: <code>on_sig_stack</code>

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
In arch/x86/kernel/signal.c (ffffffff8102e0e3)
Location: include/linux/sched.h:2542
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81078203)
Location: include/linux/sched.h:2542
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/signal.c (ffffffff8108d1e0)
Location: include/linux/sched.h:2542
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__compat_save_altstack
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
In arch/x86/kernel/signal.c (ffffffff8102da6a)
Location: include/linux/sched.h:2773
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81079baf)
Location: include/linux/sched.h:2773
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/signal.c (ffffffff81094e07)
Location: include/linux/sched.h:2773
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
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
In arch/x86/kernel/signal.c (ffffffff8102d040)
Location: include/linux/sched.h:2873
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d4d3)
Location: include/linux/sched.h:2873
Inline: True
```
```
In kernel/signal.c (ffffffff81095681)
Location: include/linux/sched.h:2873
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
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
In arch/x86/kernel/signal.c (ffffffff8102b2a0)
Location: include/linux/sched/signal.h:444
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107bc2d)
Location: include/linux/sched/signal.h:444
Inline: True
```
```
In kernel/signal.c (ffffffff81092398)
Location: include/linux/sched/signal.h:444
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
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
In arch/x86/kernel/signal.c (ffffffff8102bfd0)
Location: include/linux/sched/signal.h:445
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108232d)
Location: include/linux/sched/signal.h:445
Inline: True
```
```
In kernel/signal.c (ffffffff81099228)
Location: include/linux/sched/signal.h:445
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
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
In arch/x86/kernel/signal.c (ffffffff8102d2dc)
Location: include/linux/sched/signal.h:473
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810859ed)
Location: include/linux/sched/signal.h:473
Inline: True
```
```
In kernel/signal.c (ffffffff8109c9eb)
Location: include/linux/sched/signal.h:473
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
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
In arch/x86/kernel/signal.c (ffffffff8102e52c)
Location: include/linux/sched/signal.h:484
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c75d)
Location: include/linux/sched/signal.h:484
Inline: True
```
```
In kernel/signal.c (ffffffff810a4d47)
Location: include/linux/sched/signal.h:484
Inline: True
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
In arch/x86/kernel/signal.c (ffffffff81030291)
Location: include/linux/sched/signal.h:515
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109053e)
Location: include/linux/sched/signal.h:515
Inline: True
```
```
In kernel/signal.c (ffffffff810a99f3)
Location: include/linux/sched/signal.h:515
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
In arch/x86/kernel/signal.c (ffffffff81030bd1)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109109e)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In kernel/signal.c (ffffffff810affe3)
Location: include/linux/sched/signal.h:507
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
In arch/x86/kernel/signal.c (ffffffff810330f1)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096c40)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In kernel/signal.c (ffffffff810bf325)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:restore_altstack
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
In arch/x86/kernel/signal.c (ffffffff81033b41)
Location: include/linux/sched/signal.h:543
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81095e80)
Location: include/linux/sched/signal.h:543
Inline: True
```
```
In kernel/signal.c (ffffffff810ba545)
Location: include/linux/sched/signal.h:543
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:restore_altstack
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
In arch/x86/kernel/signal.c (ffffffff8103565d)
Location: include/linux/sched/signal.h:555
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810967a0)
Location: include/linux/sched/signal.h:555
Inline: True
```
```
In kernel/signal.c (ffffffff810bbe83)
Location: include/linux/sched/signal.h:555
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
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
In arch/x86/kernel/signal.c (ffffffff8103a93d)
Location: include/linux/sched/signal.h:553
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a6740)
Location: include/linux/sched/signal.h:553
Inline: True
```
```
In kernel/signal.c (ffffffff810ce8e3)
Location: include/linux/sched/signal.h:553
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
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
In arch/x86/kernel/signal.c (ffffffff81041ba8)
Location: include/linux/sched/signal.h:593
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bb9e1)
Location: include/linux/sched/signal.h:593
Inline: True
```
```
In kernel/signal.c (ffffffff810de0b6)
Location: include/linux/sched/signal.h:593
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
In arch/x86/kernel/signal.c (ffffffff8104b2f6)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (ffffffff810fe536)
Location: include/linux/sched/signal.h:594
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
In arch/x86/kernel/signal.c (ffffffff8104bba3)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (ffffffff8110a5a6)
Location: include/linux/sched/signal.h:594
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
In arch/x86/kernel/signal.c (ffffffff81052e23)
Location: include/linux/sched/signal.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:get_sigframe
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (ffffffff81113f46)
Location: include/linux/sched/signal.h:585
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/signal.c (ffff800010091d68)
Location: include/linux/sched/signal.h:507
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:setup_rt_frame
```
```
In arch/arm64/kernel/signal32.c (ffff80001009e0ac)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In kernel/signal.c (ffff80001010ac78)
Location: include/linux/sched/signal.h:507
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/signal.c (c030ec3c)
Location: include/linux/sched/signal.h:507
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
```
```
In kernel/signal.c (c03643e4)
Location: include/linux/sched/signal.h:507
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/signal.c (c000000000023660)
Location: include/linux/sched/signal.h:507
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (c0000000001527e8)
Location: include/linux/sched/signal.h:507
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/signal.c (ffffffe0000b6614)
Location: include/linux/sched/signal.h:507
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:handle_signal
  - arch/riscv/kernel/signal.c:handle_signal
  - arch/riscv/kernel/signal.c:handle_signal
  - arch/riscv/kernel/signal.c:handle_signal
  - arch/riscv/kernel/signal.c:handle_signal
  - arch/riscv/kernel/signal.c:handle_signal
```
```
In kernel/signal.c (ffffffe0000cda36)
Location: include/linux/sched/signal.h:507
Inline: True
```
</details>
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
In arch/x86/kernel/signal.c (ffffffff81030d31)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109005e)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In kernel/signal.c (ffffffff810aa353)
Location: include/linux/sched/signal.h:507
Inline: True
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
In arch/x86/kernel/signal.c (ffffffff81020751)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107eb6e)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In kernel/signal.c (ffffffff81098d03)
Location: include/linux/sched/signal.h:507
Inline: True
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
In arch/x86/kernel/signal.c (ffffffff81030b91)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109000e)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In kernel/signal.c (ffffffff810a98b3)
Location: include/linux/sched/signal.h:507
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
In arch/x86/kernel/signal.c (ffffffff81031a21)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810923ee)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In kernel/signal.c (ffffffff810b1d03)
Location: include/linux/sched/signal.h:507
Inline: True
```
</details>
</li>
</ul>

## Differences
