# Function: <code>plist_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff813edf00)
Location: lib/plist.c:113
Inline: False
Direct callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:put_prev_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:__unqueue_futex
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff813edf00-ffffffff813edf65: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81434030)
Location: lib/plist.c:113
Inline: False
Direct callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:scan_swap_map
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81434030-ffffffff814340a1: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff814502c0)
Location: lib/plist.c:113
Inline: False
Direct callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:scan_swap_map
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff814502c0-ffffffff81450331: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff818f0020)
Location: lib/plist.c:113
Inline: False
Direct callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:get_swap_pages
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff818f0020-ffffffff818f0091: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81976470)
Location: lib/plist.c:113
Inline: False
Direct callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:SYSC_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81976470-ffffffff819764e1: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff819d2c40)
Location: lib/plist.c:113
Inline: False
Direct callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff819d2c40-ffffffff819d2cac: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81a0c2c0)
Location: lib/plist.c:113
Inline: False
Direct callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81a0c2c0-ffffffff81a0c32c: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81a7bc20)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81a7bc20-ffffffff81a7bc8c: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81ab2f80)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81ab2f80-ffffffff81ab2fec: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff815ed810)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff815ed810-ffffffff815ed87b: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81611f40)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81611f40-ffffffff81611fab: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff815f5630)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff815f5630-ffffffff815f569b: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81662a90)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81662a90-ffffffff81662afb: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff8177c960)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex/core.c:__futex_unqueue
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff8177c960-ffffffff8177c9dc: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff820393a0)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex/core.c:__futex_unqueue
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff820393a0-ffffffff8203941c: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff820b76c0)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex/core.c:__futex_unqueue
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff820b76c0-ffffffff820b773c: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff82191fd0)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex/core.c:__futex_unqueue
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff82191fd0-ffffffff8219204c: plist_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffff800010d8d228)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffff800010d8d228-ffff800010d8d2a0: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (c0e8771c)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
c0e8771c-c0e87798: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (c000000000ecf490)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
c000000000ecf490-c000000000ecf518: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffe0008b5ed8)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffe0008b5ed8-ffffffe0008b5f2c: plist_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81a51dd0)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81a51dd0-ffffffff81a51e3c: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81a0eed0)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81a0eed0-ffffffff81a0ef3c: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81abe1c0)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81abe1c0-ffffffff81abe22c: plist_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void plist_del(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81aca660)
Location: lib/plist.c:112
Inline: False
Direct callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__del_from_avail_list
  - lib/plist.c:plist_requeue
```
**Symbols:**

```
ffffffff81aca660-ffffffff81aca6cc: plist_del (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
