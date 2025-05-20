# Function: <code>plist_first</code>

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
In kernel/sched/rt.c (0)
Location: include/linux/plist.h:282
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/plist.h:282
Inline: True
```
```
In lib/plist.c (ffffffff813ede4b)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (0)
Location: include/linux/plist.h:282
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/plist.h:282
Inline: True
```
```
In lib/plist.c (ffffffff81433f81)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (0)
Location: include/linux/plist.h:282
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/plist.h:282
Inline: True
```
```
In lib/plist.c (ffffffff81450211)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (0)
Location: include/linux/plist.h:282
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/plist.h:282
Inline: True
```
```
In lib/plist.c (ffffffff818eff9d)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (0)
Location: include/linux/plist.h:282
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/linux/plist.h:282
Inline: True
```
```
In lib/plist.c (ffffffff819763ed)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810d2c28)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810e6da4)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In lib/plist.c (ffffffff819d2bb1)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810dc678)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810f23a4)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (ffffffff81a0c231)
Location: include/linux/plist.h:282
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810e3618)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810fa854)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (ffffffff81a7bb9f)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810ed413)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff811066f4)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (ffffffff81ab2eed)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810f722c)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8111139a)
Location: include/linux/plist.h:280
Inline: True
```
```
In lib/plist.c (ffffffff815ed795)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810f53bc)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8110e51a)
Location: include/linux/plist.h:280
Inline: True
```
```
In lib/plist.c (ffffffff81611ec5)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810f748c)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8110effa)
Location: include/linux/plist.h:280
Inline: True
```
```
In lib/plist.c (ffffffff815f55b5)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff811119fc)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8112e8db)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
```
In lib/plist.c (ffffffff81662a15)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/build_policy.c (ffffffff8112df3c)
Location: include/linux/plist.h:283
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8114fd15)
Location: include/linux/plist.h:283
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
```
In lib/plist.c (ffffffff8177c8cd)
Location: include/linux/plist.h:283
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/build_policy.c (ffffffff81157ecc)
Location: include/linux/plist.h:283
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8117e5c5)
Location: include/linux/plist.h:283
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
```
In lib/plist.c (ffffffff820392fd)
Location: include/linux/plist.h:283
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/build_policy.c (ffffffff81167fcc)
Location: include/linux/plist.h:283
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8118f225)
Location: include/linux/plist.h:283
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
```
In lib/plist.c (ffffffff820b761d)
Location: include/linux/plist.h:283
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/build_policy.c (ffffffff81174d7c)
Location: include/linux/plist.h:273
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8119dbd5)
Location: include/linux/plist.h:273
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
```
In lib/plist.c (ffffffff82191f2d)
Location: include/linux/plist.h:273
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffff80001014dffc)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffff80001016ce98)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (ffff800010d8d170)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (c039b41c)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (c03b8234)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (c0e8765c)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (c0000000001a0bf0)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (c0000000001c4820)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (c000000000ecf3ec)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffe0000f6cea)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffe00010cad8)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (ffffffe0008b5e56)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810e74c3)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810ffa04)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (ffffffff81a51d3d)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810d6713)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810efbf4)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (ffffffff81a0ee3d)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810e3943)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810fcbc4)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (ffffffff81abe12d)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810ef483)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff81107df4)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In lib/plist.c (ffffffff81aca5cd)
Location: include/linux/plist.h:280
Inline: True
Inline callers:
  - lib/plist.c:plist_add
```
</details>
</li>
</ul>

## Differences
