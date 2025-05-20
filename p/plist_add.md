# Function: <code>plist_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff813ede10)
Location: lib/plist.c:74
Inline: False
Direct callers:
  - kernel/sched/rt.c:put_prev_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_entry_free
```
**Symbols:**

```
ffffffff813ede10-ffffffff813edef3: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81433f40)
Location: lib/plist.c:74
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_entry_free
```
**Symbols:**

```
ffffffff81433f40-ffffffff8143402e: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff814501d0)
Location: lib/plist.c:74
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_entry_free
```
**Symbols:**

```
ffffffff814501d0-ffffffff814502be: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff818eff70)
Location: lib/plist.c:74
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff818eff70-ffffffff818f0014: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff819763c0)
Location: lib/plist.c:74
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff819763c0-ffffffff81976464: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff819d2b80)
Location: lib/plist.c:74
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff819d2b80-ffffffff819d2c37: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81a0c200)
Location: lib/plist.c:74
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff81a0c200-ffffffff81a0c2b7: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/plist.c (0)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff81a7bd29-ffffffff81a7bd5f: plist_add.cold (STB_LOCAL)
ffffffff81a7bb60-ffffffff81a7bc17: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81ab2ec0)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff81ab2ec0-ffffffff81ab2f72: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff815ed770)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff815ed770-ffffffff815ed806: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81611ea0)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff81611ea0-ffffffff81611f36: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff815f5590)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff815f5590-ffffffff815f5626: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff816629f0)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff816629f0-ffffffff81662a86: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff8177c8a0)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex/core.c:__futex_queue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff8177c8a0-ffffffff8177c95b: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff820392d0)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex/core.c:__futex_queue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff820392d0-ffffffff8203938b: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff820b75f0)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex/core.c:__futex_queue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff820b75f0-ffffffff820b76ab: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff82191f00)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex/core.c:__futex_queue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff82191f00-ffffffff82191fbb: plist_add (STB_GLOBAL)
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
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffff800010d8d140)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffff800010d8d140-ffff800010d8d228: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (c0e87614)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
c0e87614-c0e8771c: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (c000000000ecf3b0)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
c000000000ecf3b0-c000000000ecf484: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffe0008b5e34)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffe0008b5e34-ffffffe0008b5ed8: plist_add (STB_GLOBAL)
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
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81a51d10)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff81a51d10-ffffffff81a51dc2: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81a0ee10)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff81a0ee10-ffffffff81a0eec2: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81abe100)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff81abe100-ffffffff81abe1b2: plist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void plist_add(struct plist_node *node, struct plist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/plist.c (ffffffff81aca5a0)
Location: lib/plist.c:73
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - mm/swapfile.c:add_to_avail_list
```
**Symbols:**

```
ffffffff81aca5a0-ffffffff81aca652: plist_add (STB_GLOBAL)
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
