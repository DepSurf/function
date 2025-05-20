# Function: <code>get_state_synchronize_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff810e62a0-ffffffff810e62b5: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:3328
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff810ec8a0-ffffffff810ec8b5: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:3326
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff810f3820-ffffffff810f3835: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2490)
Location: kernel/rcu/tree.c:3346
Inline: True
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff810f2490-ffffffff810f24a5: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc210)
Location: kernel/rcu/tree.c:3329
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff810fc210-ffffffff810fc228: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81104820)
Location: kernel/rcu/tree.c:3135
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81104820-ffffffff81104838: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110200)
Location: kernel/rcu/tree.c:2980
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81110200-ffffffff81110226: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811199c0)
Location: kernel/rcu/tree.c:2689
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff811199c0-ffffffff811199e6: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81125d50)
Location: kernel/rcu/tree.c:2749
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81125d50-ffffffff81125d76: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133640)
Location: kernel/rcu/tree.c:3444
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81133640-ffffffff81133666: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112ece0)
Location: kernel/rcu/tree.c:3754
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff8112ece0-ffffffff8112ed06: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811319f5)
Location: kernel/rcu/tree.c:3799
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff8112f310-ffffffff8112f336: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81153a15)
Location: kernel/rcu/tree.c:3760
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff811508c0-ffffffff811508e6: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81179325)
Location: kernel/rcu/tree.c:3856
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/events/core.c:ring_buffer_attach
  - net/sched/sch_generic.c:mini_qdisc_pair_init
```
**Symbols:**

```
ffffffff81177fb0-ffffffff81177fda: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b03f5)
Location: kernel/rcu/tree.c:3593
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/events/core.c:ring_buffer_attach
  - net/sched/sch_generic.c:mini_qdisc_pair_init
```
**Symbols:**

```
ffffffff811af710-ffffffff811af73a: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c23c5)
Location: kernel/rcu/tree.c:3585
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/events/core.c:ring_buffer_attach
  - net/sched/sch_generic.c:mini_qdisc_pair_init
```
**Symbols:**

```
ffffffff811c1780-ffffffff811c17aa: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d2935)
Location: kernel/rcu/tree.c:3657
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/events/core.c:ring_buffer_attach
  - net/sched/sch_generic.c:mini_qdisc_pair_init
```
**Symbols:**

```
ffffffff811d1c80-ffffffff811d1caa: get_state_synchronize_rcu (STB_GLOBAL)
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
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018bd00)
Location: kernel/rcu/tree.c:2749
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffff80001018bd00-ffff80001018bd34: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03d9ec4)
Location: kernel/rcu/tree.c:2749
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
c03d9ec4-c03d9ef8: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e6530)
Location: kernel/rcu/tree.c:2749
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
c0000000001e6530-c0000000001e6560: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000120490)
Location: kernel/rcu/tree.c:2749
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffe000120490-ffffffe0001204be: get_state_synchronize_rcu (STB_GLOBAL)
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
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e330)
Location: kernel/rcu/tree.c:2749
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff8111e330-ffffffff8111e356: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8110f390)
Location: kernel/rcu/tree.c:2749
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff8110f390-ffffffff8110f3b6: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111c220)
Location: kernel/rcu/tree.c:2749
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff8111c220-ffffffff8111c246: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127930)
Location: kernel/rcu/tree.c:2749
Inline: False
Direct callers:
  - kernel/events/core.c:ring_buffer_attach
```
**Symbols:**

```
ffffffff81127930-ffffffff81127956: get_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
