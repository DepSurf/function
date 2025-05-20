# Function: <code>sas_ss_reset</code>

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
In arch/x86/kernel/signal.c (ffffffff8102d924)
Location: include/linux/sched.h:2804
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In kernel/fork.c (ffffffff810811f0)
Location: include/linux/sched.h:2804
Inline: True
```
```
In kernel/signal.c (ffffffff81094b3c)
Location: include/linux/sched.h:2804
Inline: True
Inline callers:
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff8102d794)
Location: include/linux/sched.h:2904
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107dae1)
Location: include/linux/sched.h:2904
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff81085bf1)
Location: include/linux/sched.h:2904
Inline: True
```
```
In kernel/signal.c (ffffffff81099e3b)
Location: include/linux/sched.h:2904
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff8102bb65)
Location: include/linux/sched/signal.h:475
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107c17d)
Location: include/linux/sched/signal.h:475
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff81082609)
Location: include/linux/sched/signal.h:475
Inline: True
```
```
In kernel/signal.c (ffffffff81096edb)
Location: include/linux/sched/signal.h:475
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff8102c88b)
Location: include/linux/sched/signal.h:476
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108287d)
Location: include/linux/sched/signal.h:476
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff81089418)
Location: include/linux/sched/signal.h:476
Inline: True
```
```
In kernel/signal.c (ffffffff8109dc7b)
Location: include/linux/sched/signal.h:476
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff8102d826)
Location: include/linux/sched/signal.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085f3d)
Location: include/linux/sched/signal.h:504
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff8108ce37)
Location: include/linux/sched/signal.h:504
Inline: True
```
```
In kernel/signal.c (ffffffff810a2d5b)
Location: include/linux/sched/signal.h:504
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff8102ea6a)
Location: include/linux/sched/signal.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108cccd)
Location: include/linux/sched/signal.h:515
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff81094962)
Location: include/linux/sched/signal.h:515
Inline: True
```
```
In kernel/signal.c (ffffffff810ab953)
Location: include/linux/sched/signal.h:515
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff81030679)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090b90)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff81099102)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b0e4b)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff8103117b)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81091890)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff8109f6fa)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b759b)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff81033588)
Location: include/linux/sched/signal.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81097211)
Location: include/linux/sched/signal.h:561
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff810a6825)
Location: include/linux/sched/signal.h:561
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810bf4eb)
Location: include/linux/sched/signal.h:561
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff81033ddc)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109626f)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff810a22d1)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810ba6e9)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff81035ace)
Location: include/linux/sched/signal.h:580
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096d57)
Location: include/linux/sched/signal.h:580
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff810a2fbf)
Location: include/linux/sched/signal.h:580
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810bc019)
Location: include/linux/sched/signal.h:580
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In kernel/fork.c (ffffffff810b4733)
Location: include/linux/sched/signal.h:578
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810ccce3)
Location: include/linux/sched/signal.h:578
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
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
In kernel/fork.c (ffffffff810cac3a)
Location: include/linux/sched/signal.h:618
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810e47a8)
Location: include/linux/sched/signal.h:618
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
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
In kernel/fork.c (ffffffff810e81cf)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff81104e31)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
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
In kernel/fork.c (ffffffff810f3e31)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff811110b1)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
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
In kernel/fork.c (ffffffff810fd200)
Location: include/linux/sched/signal.h:610
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8111aa21)
Location: include/linux/sched/signal.h:610
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
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
In kernel/fork.c (ffff8000100f3de8)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffff800010113a14)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In kernel/fork.c (c03527bc)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c036a3bc)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/signal.c:__save_altstack
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
In kernel/fork.c (c00000000013a12c)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c00000000015b674)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In kernel/fork.c (ffffffe0000c0602)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffe0000d1d90)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff810312db)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090850)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff8109901a)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b190b)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff81020ce8)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107f360)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff81087a6a)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810a022b)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff8103113b)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090800)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff81098fca)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b0e6b)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
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
In arch/x86/kernel/signal.c (ffffffff81031fe8)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092be0)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/fork.c (ffffffff810a0bec)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b913b)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
```
</details>
</li>
</ul>

## Differences
