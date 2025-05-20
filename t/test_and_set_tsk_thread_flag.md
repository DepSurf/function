# Function: <code>test_and_set_tsk_thread_flag</code>

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
In kernel/task_work.c (ffffffff8109e836)
Location: include/linux/sched.h:2864
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff81190a36)
Location: include/linux/sched.h:2864
Inline: True
```
```
In mm/memcontrol.c (ffffffff811fbf35)
Location: include/linux/sched.h:2864
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In kernel/task_work.c (ffffffff810a1f76)
Location: include/linux/sched.h:3141
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff811a4f26)
Location: include/linux/sched.h:3141
Inline: True
```
```
In mm/memcontrol.c (ffffffff8122001c)
Location: include/linux/sched.h:3141
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In kernel/task_work.c (ffffffff810a7036)
Location: include/linux/sched.h:3297
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff811b4def)
Location: include/linux/sched.h:3297
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff812326b8)
Location: include/linux/sched.h:3297
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In kernel/task_work.c (ffffffff810a3f86)
Location: include/linux/sched.h:1492
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff811bc0d9)
Location: include/linux/sched.h:1492
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff8123d7a3)
Location: include/linux/sched.h:1492
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In kernel/task_work.c (ffffffff810aa5ac)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff811d0d10)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff8125d324)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In arch/x86/kernel/cpu/bugs.c (ffffffff810436d6)
Location: include/linux/sched.h:1648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In kernel/task_work.c (ffffffff810b11dc)
Location: include/linux/sched.h:1648
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff811f1fb0)
Location: include/linux/sched.h:1648
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff81281d57)
Location: include/linux/sched.h:1648
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In kernel/task_work.c (ffffffff810ba25c)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff81203e10)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff81298e17)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffffffff814c347b)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810c0166)
Location: include/linux/sched.h:1734
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff8121b253)
Location: include/linux/sched.h:1734
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff812b41fa)
Location: include/linux/sched.h:1734
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffffffff814f1b7b)
Location: include/linux/sched.h:1734
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810c6526)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff81228d13)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff812c5b0c)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffffffff8150b15b)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810ce586)
Location: include/linux/sched.h:1777
Inline: True
```
```
In mm/oom_kill.c (ffffffff81255b63)
Location: include/linux/sched.h:1777
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff812fb532)
Location: include/linux/sched.h:1777
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffffffff8156c0bb)
Location: include/linux/sched.h:1777
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810c907f)
Location: include/linux/sched.h:1838
Inline: True
```
```
In mm/oom_kill.c (ffffffff812607f1)
Location: include/linux/sched.h:1838
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff8130738f)
Location: include/linux/sched.h:1838
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffffffff81586deb)
Location: include/linux/sched.h:1838
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810caa7b)
Location: include/linux/sched.h:1860
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81137e7d)
Location: include/linux/sched.h:1860
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In mm/oom_kill.c (ffffffff81264f91)
Location: include/linux/sched.h:1860
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff8130db05)
Location: include/linux/sched.h:1860
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In fs/io-wq.c (ffffffff813a1fc8)
Location: include/linux/sched.h:1860
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_wake
```
```
In block/blk-cgroup.c (ffffffff8158dc2a)
Location: include/linux/sched.h:1860
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810ddbfb)
Location: include/linux/sched.h:1977
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8115abd0)
Location: include/linux/sched.h:1977
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In mm/oom_kill.c (ffffffff812a17c4)
Location: include/linux/sched.h:1977
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff813589fb)
Location: include/linux/sched.h:1977
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
```
```
In fs/io-wq.c (ffffffff813f1373)
Location: include/linux/sched.h:1977
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_wake
```
```
In block/blk-cgroup.c (ffffffff815f369a)
Location: include/linux/sched.h:1977
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810f773c)
Location: include/linux/sched.h:1999
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81184497)
Location: include/linux/sched.h:1999
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In mm/oom_kill.c (ffffffff812f94c4)
Location: include/linux/sched.h:1999
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff813d2890)
Location: include/linux/sched.h:1999
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
```
```
In block/blk-cgroup.c (ffffffff816a4caa)
Location: include/linux/sched.h:1999
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In io_uring/io-wq.c (ffffffff816da1a4)
Location: include/linux/sched.h:1999
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
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
In kernel/task_work.c (ffffffff81119ed9)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/livepatch/transition.c (ffffffff811bf741)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In mm/oom_kill.c (ffffffff81363244)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff8145801c)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
```
```
In block/blk-cgroup.c (ffffffff81763a50)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In io_uring/io-wq.c (ffffffff817a6234)
Location: include/linux/sched.h:2026
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
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
In kernel/task_work.c (ffffffff81127149)
Location: include/linux/sched.h:2034
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/livepatch/transition.c (ffffffff811d2221)
Location: include/linux/sched.h:2034
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In mm/oom_kill.c (ffffffff81395674)
Location: include/linux/sched.h:2034
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff8148dd63)
Location: include/linux/sched.h:2034
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
```
```
In block/blk-cgroup.c (ffffffff817a2afd)
Location: include/linux/sched.h:2034
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In io_uring/io-wq.c (ffffffff817e7194)
Location: include/linux/sched.h:2034
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
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
In kernel/task_work.c (ffffffff81131729)
Location: include/linux/sched.h:1936
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/livepatch/transition.c (ffffffff811e6ea1)
Location: include/linux/sched.h:1936
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In mm/oom_kill.c (ffffffff813bf434)
Location: include/linux/sched.h:1936
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff814bd6d6)
Location: include/linux/sched.h:1936
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
```
```
In block/blk-cgroup.c (ffffffff817e663d)
Location: include/linux/sched.h:1936
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In io_uring/io-wq.c (ffffffff8182cf54)
Location: include/linux/sched.h:1936
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
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
In kernel/task_work.c (ffff800010124fbc)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffff8000102b7150)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffff8000103688ac)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffff80001060eaf4)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (c0377f08)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (c04e37b0)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (c0559fc8)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (c07b9384)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (c00000000016ec20)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (c00000000036e170)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (c000000000456854)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (c0000000007ac124)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffe0000dcee4)
Location: include/linux/sched.h:1727
Inline: True
```
```
In mm/oom_kill.c (ffffffe0001daf40)
Location: include/linux/sched.h:1727
Inline: True
```
```
In mm/memcontrol.c (ffffffe0002466e4)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffffffe000446ed2)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810c08a6)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff81221363)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff812be0ec)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffffffff8150373b)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810af0a6)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff81214513)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff812af209)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffffffff814f3bfb)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810bfdf6)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff8121f103)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff812bbefc)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffffffff814ff7cb)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
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
In kernel/task_work.c (ffffffff810c82d6)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In mm/oom_kill.c (ffffffff8122e153)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/memcontrol.c (ffffffff812cc6c9)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In block/blk-cgroup.c (ffffffff8151899b)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
</details>
</li>
</ul>

## Differences
