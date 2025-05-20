# Function: <code>plist_node_init</code>

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
In kernel/sched/core.c (ffffffff810acb5c)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810c035e)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/rt.c:put_prev_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810cc346)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff81100088)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_lock_pi
```
```
In mm/swapfile.c (ffffffff811d62b8)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
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
In kernel/sched/core.c (ffffffff810af599)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810c4360)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810d0e51)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff81108f4f)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff811f438a)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
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
In kernel/sched/core.c (ffffffff810b56d6)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810ca3b7)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810d78c1)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff8111073f)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff81204eba)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
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
In kernel/sched/core.c (ffffffff810b18fd)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810c3ee4)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810d696a)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff81111c3f)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff81210570)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
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
In kernel/sched/core.c (ffffffff810b8d38)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810cb6b4)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810de8fd)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff8111db30)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff812279ca)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
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
In kernel/sched/core.c (ffffffff810c08ad)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810d2ffa)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810e6f2f)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff8112a564)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff8124d262)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (ffffffff810c9c0d)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810dd23a)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810f252f)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff811360d4)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff8126166e)
Location: include/linux/plist.h:134
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (ffffffff810d1857)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810e41ff)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810faa0a)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff811419aa)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff8127c596)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (ffffffff810db82b)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810eec4a)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff811068aa)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff8114da20)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff8128c076)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (ffffffff810e46a4)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810f8485)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff8111158e)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff8115cfd7)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff812bb63a)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
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
In kernel/sched/core.c (ffffffff810e20ea)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810f6695)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff8110e6f7)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff811591dd)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff812c70cc)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
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
In kernel/sched/core.c (ffffffff810e3efa)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810f86b5)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff8110f1d7)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff8115b42a)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff812cda1f)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
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
In kernel/sched/core.c (ffffffff810faa9a)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff81113b8e)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff8112ead5)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff8117ff40)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff81312e0e)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
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
In kernel/sched/core.c (ffffffff81116e64)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/build_policy.c (ffffffff811312a6)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff8114ff53)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex/core.c (ffffffff811b32fd)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/futex/core.c:__futex_queue
```
```
In mm/swapfile.c (ffffffff8137da30)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
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
In kernel/sched/core.c (ffffffff8113e314)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/build_policy.c (ffffffff8115b226)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff8117e823)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex/core.c (ffffffff811f424d)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/futex/core.c:__futex_queue
```
```
In mm/swapfile.c (ffffffff813facf0)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
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
In kernel/sched/core.c (ffffffff8114ae14)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/build_policy.c (ffffffff8116b3df)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff8118f38d)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex/core.c (ffffffff812089dd)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - kernel/futex/core.c:__futex_queue
```
```
In mm/swapfile.c (ffffffff8142dd40)
Location: include/linux/plist.h:135
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
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
In kernel/sched/core.c (ffffffff81156a14)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/build_policy.c (ffffffff8117699f)
Location: include/linux/plist.h:125
Inline: True
```
```
In kernel/power/qos.c (ffffffff8119dd3d)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex/core.c (ffffffff8121f86d)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - kernel/futex/core.c:__futex_queue
```
```
In mm/swapfile.c (ffffffff81467800)
Location: include/linux/plist.h:125
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:alloc_swap_info
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
In kernel/sched/core.c (ffff80001013b4e8)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffff800010150354)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffff80001016d39c)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffff8000101ba104)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffff8000103277bc)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (c038adcc)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (c039d7e0)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (c03b83c0)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (c0403d64)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (c053ebe8)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (c000000000189260)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (c0000000001a3888)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (c0000000001c4a70)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (c000000000221a38)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (c0000000003fe4a8)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (ffffffe0000ea9c2)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffe0000f8ae8)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffe00010cc38)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffe00013fbd0)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffe000227650)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (ffffffff810d5cb7)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810e85ed)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810ffbba)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff81146040)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff81284656)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (ffffffff810c432b)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810d800a)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810efdaa)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff81139350)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff812764c6)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (ffffffff810d2b0a)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810e517a)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff810fcd7a)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff81143ef0)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff81282466)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
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
In kernel/sched/core.c (ffffffff810dd5a7)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810f134b)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/power/qos.c (ffffffff81107faa)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/futex.c (ffffffff8114ff80)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/swapfile.c (ffffffff81292156)
Location: include/linux/plist.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
```
</details>
</li>
</ul>

## Differences
