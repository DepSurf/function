# Function: <code>irq_work_queue_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81170d30)
Location: kernel/irq_work.c:66
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_irq_work_func
```
**Symbols:**

```
ffffffff81170d30-ffffffff81170e50: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8117e430)
Location: kernel/irq_work.c:66
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_irq_work_func
```
**Symbols:**

```
ffffffff8117e430-ffffffff8117e537: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8118a040)
Location: kernel/irq_work.c:66
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_irq_work_func
```
**Symbols:**

```
ffffffff8118a040-ffffffff8118a147: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8118cba0)
Location: kernel/irq_work.c:66
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_irq_work_func
```
**Symbols:**

```
ffffffff8118cba0-ffffffff8118cc52: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8119a7c0)
Location: kernel/irq_work.c:65
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff8119a7c0-ffffffff8119a87a: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811b0200)
Location: kernel/irq_work.c:65
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff811b0200-ffffffff811b02bb: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811be810)
Location: kernel/irq_work.c:65
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff811be810-ffffffff811be8dd: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811ce3c0)
Location: kernel/irq_work.c:96
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811ce3c0-ffffffff811ce485: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811da9e0)
Location: kernel/irq_work.c:96
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811da9e0-ffffffff811daaa5: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f7420)
Location: kernel/irq_work.c:88
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:tell_cpu_to_push
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811f7420-ffffffff811f7487: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f5f90)
Location: kernel/irq_work.c:88
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:tell_cpu_to_push
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811f5f90-ffffffff811f5ff7: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f6e80)
Location: kernel/irq_work.c:88
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811f6e80-ffffffff811f6ee7: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81228450)
Location: kernel/irq_work.c:88
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff81228450-ffffffff812284b7: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812694a0)
Location: kernel/irq_work.c:127
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff812694a0-ffffffff81269529: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812be320)
Location: kernel/irq_work.c:127
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_irq
  - kernel/events/core.c:perf_pending_irq
```
**Symbols:**

```
ffffffff812be320-ffffffff812be3a8: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812e4f60)
Location: kernel/irq_work.c:137
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_irq
  - kernel/events/core.c:perf_pending_irq
```
**Symbols:**

```
ffffffff812e4f60-ffffffff812e4fe8: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81303010)
Location: kernel/irq_work.c:137
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_irq
  - kernel/events/core.c:perf_pending_irq
```
**Symbols:**

```
ffffffff81303010-ffffffff81303098: irq_work_queue_on (STB_GLOBAL)
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
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffff80001025b1c8)
Location: kernel/irq_work.c:96
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffff80001025b1c8-ffff80001025b2a0: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c048e2dc)
Location: kernel/irq_work.c:96
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
c048e2dc-c048e404: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c0000000002fee60)
Location: kernel/irq_work.c:96
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
c0000000002fee60-c0000000002fef78: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffe00019a21a)
Location: kernel/irq_work.c:96
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffe00019a21a-ffffffe00019a306: irq_work_queue_on (STB_GLOBAL)
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
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811d3000)
Location: kernel/irq_work.c:96
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811d3000-ffffffff811d30c5: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811c5dc0)
Location: kernel/irq_work.c:96
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811c5dc0-ffffffff811c5e85: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811d0dd0)
Location: kernel/irq_work.c:96
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811d0dd0-ffffffff811d0e95: irq_work_queue_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool irq_work_queue_on(struct irq_work *work, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811df0b0)
Location: kernel/irq_work.c:96
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/rcu/tree.c:__rcu_read_unlock
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811df0b0-ffffffff811df18f: irq_work_queue_on (STB_GLOBAL)
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
