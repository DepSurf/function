# Function: <code>test_tsk_need_resched</code>

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
In kernel/sched/core.c (ffffffff810aa2d5)
Location: include/linux/sched.h:2889
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810b4f21)
Location: include/linux/sched.h:2889
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810befdc)
Location: include/linux/sched.h:2889
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c1377)
Location: include/linux/sched.h:2889
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810ada62)
Location: include/linux/sched.h:3166
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810b7a47)
Location: include/linux/sched.h:3166
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810c28dc)
Location: include/linux/sched.h:3166
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c4e37)
Location: include/linux/sched.h:3166
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810b3b62)
Location: include/linux/sched.h:3322
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810bfd57)
Location: include/linux/sched.h:3322
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810c895c)
Location: include/linux/sched.h:3322
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cae87)
Location: include/linux/sched.h:3322
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810afaa0)
Location: include/linux/sched.h:1517
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810bb787)
Location: include/linux/sched.h:1517
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810c3924)
Location: include/linux/sched.h:1517
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c52a7)
Location: include/linux/sched.h:1517
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810b6e76)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810c34e7)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810cb0e4)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cc9c7)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810be9db)
Location: include/linux/sched.h:1673
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810c99e7)
Location: include/linux/sched.h:1673
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810d27de)
Location: include/linux/sched.h:1673
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d492f)
Location: include/linux/sched.h:1673
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810c7c7b)
Location: include/linux/sched.h:1686
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810d43d7)
Location: include/linux/sched.h:1686
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810dc14e)
Location: include/linux/sched.h:1686
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810de35f)
Location: include/linux/sched.h:1686
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810ceffe)
Location: include/linux/sched.h:1759
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810db28c)
Location: include/linux/sched.h:1759
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810e311c)
Location: include/linux/sched.h:1759
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e5444)
Location: include/linux/sched.h:1759
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810d8dbe)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810e519c)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810ed488)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f0864)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810e24ac)
Location: include/linux/sched.h:1802
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810ee705)
Location: include/linux/sched.h:1802
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810f9489)
Location: include/linux/sched.h:1802
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa204)
Location: include/linux/sched.h:1802
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810df864)
Location: include/linux/sched.h:1863
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810ec545)
Location: include/linux/sched.h:1863
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810f7779)
Location: include/linux/sched.h:1863
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f8654)
Location: include/linux/sched.h:1863
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810e1654)
Location: include/linux/sched.h:1885
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810eeee8)
Location: include/linux/sched.h:1885
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810f9c89)
Location: include/linux/sched.h:1885
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa7b4)
Location: include/linux/sched.h:1885
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810f7784)
Location: include/linux/sched.h:2002
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff81109675)
Location: include/linux/sched.h:2002
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff81112bd9)
Location: include/linux/sched.h:2002
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff81115564)
Location: include/linux/sched.h:2002
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff811139a2)
Location: include/linux/sched.h:2024
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff8112503c)
Location: include/linux/sched.h:2024
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/build_policy.c (ffffffff81134e1b)
Location: include/linux/sched.h:2024
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:check_preempt_curr_rt
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
In kernel/sched/core.c (ffffffff8113ab62)
Location: include/linux/sched.h:2051
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff8114e2ac)
Location: include/linux/sched.h:2051
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/build_policy.c (ffffffff8115f33b)
Location: include/linux/sched.h:2051
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:check_preempt_curr_rt
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
In kernel/sched/core.c (ffffffff81149ec2)
Location: include/linux/sched.h:2059
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff8115cb5f)
Location: include/linux/sched.h:2059
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/build_policy.c (ffffffff8116fa2b)
Location: include/linux/sched.h:2059
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:check_preempt_curr_rt
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
In kernel/sched/core.c (ffffffff811559c2)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - kernel/sched/core.c:wakeup_preempt
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff81167fa8)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup_fair
```
```
In kernel/sched/build_policy.c (ffffffff8117cf7b)
Location: include/linux/sched.h:1961
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:wakeup_preempt_dl
  - kernel/sched/build_policy.c:wakeup_preempt_rt
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
In kernel/sched/core.c (ffff800010139044)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffff800010144d20)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffff80001014e0c8)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffff800010152464)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (c03883b0)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (c0392ae4)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (c039ca60)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (c039f240)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (c0000000001856f0)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (c000000000196344)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (c0000000001a0cd0)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (c0000000001a59d0)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffe0000e8dbe)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffe0000f1af8)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffe0000f6d7e)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fa0f0)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810d328e)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810df34c)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810e794c)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e9c64)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810c18be)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810ce35c)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810d6788)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d9c24)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810d096e)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810db6cc)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810e39b8)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e6d94)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
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
In kernel/sched/core.c (ffffffff810daa0e)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810e73bc)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810f015c)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f1cf4)
Location: include/linux/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
</details>
</li>
</ul>

## Differences
