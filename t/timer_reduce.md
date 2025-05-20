# Function: <code>timer_reduce</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811088a0)
Location: kernel/time/timer.c:1107
Inline: False
```
**Symbols:**

```
ffffffff811088a0-ffffffff81108c99: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81114300)
Location: kernel/time/timer.c:1115
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff81114300-ffffffff811146ec: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111fb80)
Location: kernel/time/timer.c:1114
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff8111fb80-ffffffff8111ff6c: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a2d0)
Location: kernel/time/timer.c:1109
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff8112a2d0-ffffffff8112a5f9: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81136270)
Location: kernel/time/timer.c:1113
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff81136270-ffffffff81136599: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811449d0)
Location: kernel/time/timer.c:1125
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff811449d0-ffffffff811449e5: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141d90)
Location: kernel/time/timer.c:1119
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff81141d90-ffffffff81141da5: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81142b90)
Location: kernel/time/timer.c:1121
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff81142b90-ffffffff81142ba5: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811660d0)
Location: kernel/time/timer.c:1121
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff811660d0-ffffffff811660e5: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199c50)
Location: kernel/time/timer.c:1174
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff81199c50-ffffffff81199c6f: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d82c0)
Location: kernel/time/timer.c:1214
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_key_add
```
**Symbols:**

```
ffffffff811d82c0-ffffffff811d82df: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ec6f0)
Location: kernel/time/timer.c:1214
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_key_add
```
**Symbols:**

```
ffffffff811ec6f0-ffffffff811ec70f: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81202710)
Location: kernel/time/timer.c:1214
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_key_add
```
**Symbols:**

```
ffffffff81202710-ffffffff8120272f: timer_reduce (STB_GLOBAL)
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
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019f1b8)
Location: kernel/time/timer.c:1113
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffff80001019f1b8-ffff80001019f534: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e9694)
Location: kernel/time/timer.c:1113
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
c03e9694-c03e9a18: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fff40)
Location: kernel/time/timer.c:1113
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
c0000000001fff40-c0000000002003cc: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012d568)
Location: kernel/time/timer.c:1113
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffe00012d568-ffffffe00012d82a: timer_reduce (STB_GLOBAL)
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
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112ea20)
Location: kernel/time/timer.c:1113
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff8112ea20-ffffffff8112ed49: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811217b0)
Location: kernel/time/timer.c:1113
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff811217b0-ffffffff81121ad9: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112c740)
Location: kernel/time/timer.c:1113
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff8112c740-ffffffff8112ca69: timer_reduce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int timer_reduce(struct timer_list *timer, long unsigned int expires);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81138ec0)
Location: kernel/time/timer.c:1113
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
  - kernel/cgroup/cgroup.c:cgroup_file_notify
```
**Symbols:**

```
ffffffff81138ec0-ffffffff811391f4: timer_reduce (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
