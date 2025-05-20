# Function: <code>sas_ss_flags</code>

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
In arch/x86/kernel/signal.c (ffffffff8102e759)
Location: include/linux/sched.h:2553
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81078153)
Location: include/linux/sched.h:2553
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/signal.c (ffffffff8108d1b6)
Location: include/linux/sched.h:2553
Inline: True
Inline callers:
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
In arch/x86/kernel/signal.c (ffffffff8102da5b)
Location: include/linux/sched.h:2796
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81079ba0)
Location: include/linux/sched.h:2796
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/signal.c (ffffffff81094df7)
Location: include/linux/sched.h:2796
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
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
In arch/x86/kernel/signal.c (ffffffff8102d0ba)
Location: include/linux/sched.h:2896
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d423)
Location: include/linux/sched.h:2896
Inline: True
```
```
In kernel/signal.c (ffffffff810955f2)
Location: include/linux/sched.h:2896
Inline: True
Inline callers:
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
In arch/x86/kernel/signal.c (ffffffff8102b31a)
Location: include/linux/sched/signal.h:467
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107bc23)
Location: include/linux/sched/signal.h:467
Inline: True
```
```
In kernel/signal.c (ffffffff81092346)
Location: include/linux/sched/signal.h:467
Inline: True
Inline callers:
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
In arch/x86/kernel/signal.c (ffffffff8102c04a)
Location: include/linux/sched/signal.h:468
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81082323)
Location: include/linux/sched/signal.h:468
Inline: True
```
```
In kernel/signal.c (ffffffff810991d6)
Location: include/linux/sched/signal.h:468
Inline: True
Inline callers:
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
In arch/x86/kernel/signal.c (ffffffff8102d31a)
Location: include/linux/sched/signal.h:496
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810859e3)
Location: include/linux/sched/signal.h:496
Inline: True
```
```
In kernel/signal.c (ffffffff8109c97d)
Location: include/linux/sched/signal.h:496
Inline: True
Inline callers:
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
In arch/x86/kernel/signal.c (ffffffff8102e56a)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c753)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In kernel/signal.c (ffffffff810a4d3d)
Location: include/linux/sched/signal.h:507
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
In arch/x86/kernel/signal.c (ffffffff81030329)
Location: include/linux/sched/signal.h:538
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109052b)
Location: include/linux/sched/signal.h:538
Inline: True
```
```
In kernel/signal.c (ffffffff810a99e9)
Location: include/linux/sched/signal.h:538
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
In arch/x86/kernel/signal.c (ffffffff81030c69)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109108b)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In kernel/signal.c (ffffffff810affd9)
Location: include/linux/sched/signal.h:530
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
In arch/x86/kernel/signal.c (ffffffff8103310c)
Location: include/linux/sched/signal.h:553
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096c2d)
Location: include/linux/sched/signal.h:553
Inline: True
```
```
In kernel/signal.c (ffffffff810b7b9d)
Location: include/linux/sched/signal.h:553
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
In arch/x86/kernel/signal.c (ffffffff81033b5c)
Location: include/linux/sched/signal.h:566
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81095e6d)
Location: include/linux/sched/signal.h:566
Inline: True
```
```
In kernel/signal.c (ffffffff810b2e4d)
Location: include/linux/sched/signal.h:566
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
In arch/x86/kernel/signal.c (ffffffff8103569e)
Location: include/linux/sched/signal.h:572
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109678d)
Location: include/linux/sched/signal.h:572
Inline: True
```
```
In kernel/signal.c (ffffffff810b4480)
Location: include/linux/sched/signal.h:572
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
In arch/x86/kernel/signal.c (ffffffff8103a97e)
Location: include/linux/sched/signal.h:570
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a672d)
Location: include/linux/sched/signal.h:570
Inline: True
```
```
In kernel/signal.c (ffffffff810c6650)
Location: include/linux/sched/signal.h:570
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
In arch/x86/kernel/signal.c (ffffffff81041be7)
Location: include/linux/sched/signal.h:610
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bb9ce)
Location: include/linux/sched/signal.h:610
Inline: True
```
```
In kernel/signal.c (ffffffff810de0ac)
Location: include/linux/sched/signal.h:610
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
In arch/x86/kernel/signal.c (ffffffff8104b3c5)
Location: include/linux/sched/signal.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (ffffffff810fe52c)
Location: include/linux/sched/signal.h:611
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
In arch/x86/kernel/signal.c (ffffffff8104bc5b)
Location: include/linux/sched/signal.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (ffffffff8110a59c)
Location: include/linux/sched/signal.h:611
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
In arch/x86/kernel/signal.c (ffffffff81052edb)
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (ffffffff81113f3c)
Location: include/linux/sched/signal.h:602
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
In arch/arm64/kernel/signal.c (ffff800010091d5c)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:setup_rt_frame
```
```
In arch/arm64/kernel/signal32.c (ffff80001009e0a0)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In kernel/signal.c (ffff80001010ac24)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
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
In arch/arm/kernel/signal.c (c030ec2c)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
```
```
In kernel/signal.c (c03643cc)
Location: include/linux/sched/signal.h:530
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
In arch/powerpc/kernel/signal.c (c000000000023650)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal.c:get_sigframe
```
```
In kernel/signal.c (c0000000001527dc)
Location: include/linux/sched/signal.h:530
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
In arch/riscv/kernel/signal.c (ffffffe0000b67fe)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:handle_signal
```
```
In kernel/signal.c (ffffffe0000cda26)
Location: include/linux/sched/signal.h:530
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
In arch/x86/kernel/signal.c (ffffffff81030dc9)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109004b)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In kernel/signal.c (ffffffff810aa349)
Location: include/linux/sched/signal.h:530
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
In arch/x86/kernel/signal.c (ffffffff810207e9)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107eb5b)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In kernel/signal.c (ffffffff81098cf9)
Location: include/linux/sched/signal.h:530
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
In arch/x86/kernel/signal.c (ffffffff81030c29)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108fffb)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In kernel/signal.c (ffffffff810a98a9)
Location: include/linux/sched/signal.h:530
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
In arch/x86/kernel/signal.c (ffffffff81031ab9)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810923db)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In kernel/signal.c (ffffffff810b1cf9)
Location: include/linux/sched/signal.h:530
Inline: True
```
</details>
</li>
</ul>

## Differences
