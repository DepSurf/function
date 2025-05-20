# Function: <code>__hrtimer_get_next_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ee980)
Location: kernel/time/hrtimer.c:469
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_interrupt
```
**Symbols:**

```
ffffffff810ee980-ffffffff810ee9e5: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5a50)
Location: kernel/time/hrtimer.c:465
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff810f5a50-ffffffff810f5ab5: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fdaa3)
Location: kernel/time/hrtimer.c:465
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ffd20)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110ab10)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811155c0)
Location: kernel/time/hrtimer.c:556
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffffffff811155c0-ffffffff81115632: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120c00)
Location: kernel/time/hrtimer.c:547
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffffffff81120c00-ffffffff81120c72: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b410)
Location: kernel/time/hrtimer.c:546
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffffffff8112b410-ffffffff8112b48d: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811374f0)
Location: kernel/time/hrtimer.c:567
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffffffff811374f0-ffffffff8113756d: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81147bef)
Location: kernel/time/hrtimer.c:567
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
```
**Symbols:**

```
ffffffff81146180-ffffffff811461fb: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81144072)
Location: kernel/time/hrtimer.c:569
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_get_next_event
```
**Symbols:**

```
ffffffff811426a0-ffffffff8114271b: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81145202)
Location: kernel/time/hrtimer.c:569
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_get_next_event
```
**Symbols:**

```
ffffffff81143870-ffffffff811438eb: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81168a5b)
Location: kernel/time/hrtimer.c:569
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_get_next_event
```
**Symbols:**

```
ffffffff81167040-ffffffff811670bb: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119c5bd)
Location: kernel/time/hrtimer.c:569
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_get_next_event
```
**Symbols:**

```
ffffffff8119a8c0-ffffffff8119a953: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811daf8d)
Location: kernel/time/hrtimer.c:569
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_get_next_event
```
**Symbols:**

```
ffffffff811d9080-ffffffff811d9113: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ef4bd)
Location: kernel/time/hrtimer.c:571
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_get_next_event
```
**Symbols:**

```
ffffffff811ed4e0-ffffffff811ed573: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81205643)
Location: kernel/time/hrtimer.c:571
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_update_next_event
  - kernel/time/hrtimer.c:hrtimer_update_next_event
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_get_next_event
```
**Symbols:**

```
ffffffff81203660-ffffffff812036f3: __hrtimer_get_next_event (STB_LOCAL)
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0908)
Location: kernel/time/hrtimer.c:567
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffff8000101a0908-ffff8000101a09a8: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea68c)
Location: kernel/time/hrtimer.c:567
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
c03ea68c-c03ea75c: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201aa0)
Location: kernel/time/hrtimer.c:567
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
c000000000201aa0-c000000000201b68: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e1ac)
Location: kernel/time/hrtimer.c:567
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffffffe00012e1ac-ffffffe00012e230: __hrtimer_get_next_event (STB_LOCAL)
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112fca0)
Location: kernel/time/hrtimer.c:567
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffffffff8112fca0-ffffffff8112fd1d: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122710)
Location: kernel/time/hrtimer.c:567
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffffffff81122710-ffffffff8112278d: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112d9c0)
Location: kernel/time/hrtimer.c:567
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffffffff8112d9c0-ffffffff8112da3d: __hrtimer_get_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base *cpu_base, unsigned int active_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a2f0)
Location: kernel/time/hrtimer.c:567
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_update_softirq_timer
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
  - kernel/time/hrtimer.c:hrtimer_force_reprogram
```
**Symbols:**

```
ffffffff8113a2f0-ffffffff8113a36d: __hrtimer_get_next_event (STB_LOCAL)
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
