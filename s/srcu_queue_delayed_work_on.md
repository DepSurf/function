# Function: <code>srcu_queue_delayed_work_on</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool srcu_queue_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f0b80)
Location: kernel/rcu/srcutree.c:446
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff810f0b80-ffffffff810f0bae: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool srcu_queue_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fa850)
Location: kernel/rcu/srcutree.c:447
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff810fa850-ffffffff810fa87e: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool srcu_queue_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81102dd0)
Location: kernel/rcu/srcutree.c:478
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81102dd0-ffffffff81102dfe: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool srcu_queue_delayed_work_on(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e7c0)
Location: kernel/rcu/srcutree.c:486
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8110e7c0-ffffffff8110e7ee: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void srcu_queue_delayed_work_on(struct srcu_data *sdp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81117e80)
Location: kernel/rcu/srcutree.c:465
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81117e80-ffffffff81117ec1: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void srcu_queue_delayed_work_on(struct srcu_data *sdp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81124240)
Location: kernel/rcu/srcutree.c:465
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81124240-ffffffff81124281: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811331b4)
Location: kernel/rcu/srcutree.c:478
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e994)
Location: kernel/rcu/srcutree.c:467
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112ec25)
Location: kernel/rcu/srcutree.c:470
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81150113)
Location: kernel/rcu/srcutree.c:462
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811775b7)
Location: kernel/rcu/srcutree.c:693
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811aebe7)
Location: kernel/rcu/srcutree.c:756
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c0be9)
Location: kernel/rcu/srcutree.c:804
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d10dc)
Location: kernel/rcu/srcutree.c:795
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
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
void srcu_queue_delayed_work_on(struct srcu_data *sdp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff8000101897d8)
Location: kernel/rcu/srcutree.c:465
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffff8000101897d8-ffff800010189838: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void srcu_queue_delayed_work_on(struct srcu_data *sdp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d8198)
Location: kernel/rcu/srcutree.c:465
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
c03d8198-c03d81ec: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void srcu_queue_delayed_work_on(struct srcu_data *sdp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e3ed0)
Location: kernel/rcu/srcutree.c:465
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
c0000000001e3ed0-c0000000001e3f5c: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void srcu_queue_delayed_work_on(struct srcu_data *sdp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011eb06)
Location: kernel/rcu/srcutree.c:465
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffe00011eb06-ffffffe00011eb6a: srcu_queue_delayed_work_on (STB_LOCAL)
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
void srcu_queue_delayed_work_on(struct srcu_data *sdp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111c820)
Location: kernel/rcu/srcutree.c:465
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8111c820-ffffffff8111c861: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void srcu_queue_delayed_work_on(struct srcu_data *sdp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110d8e0)
Location: kernel/rcu/srcutree.c:465
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8110d8e0-ffffffff8110d921: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void srcu_queue_delayed_work_on(struct srcu_data *sdp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111a710)
Location: kernel/rcu/srcutree.c:465
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8111a710-ffffffff8111a751: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void srcu_queue_delayed_work_on(struct srcu_data *sdp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81125ea0)
Location: kernel/rcu/srcutree.c:465
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81125ea0-ffffffff81125ee1: srcu_queue_delayed_work_on (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_data *sdp</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>struct workqueue_struct *wq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct delayed_work *dwork</code>
</li>
<li>
<b>Param reordered. </b>
<code>cpu, wq, dwork, delay</code> ➡️ <code>sdp, delay</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
