# Function: <code>raise_softirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81085d50)
Location: kernel/softirq.c:418
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81085d50-ffffffff81085e07: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81088b90)
Location: kernel/softirq.c:418
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/rcu/tree.c:invoke_rcu_core
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff81088b90-ffffffff81088c3d: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108dae0)
Location: kernel/softirq.c:432
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/rcu/tree.c:invoke_rcu_core
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff8108dae0-ffffffff8108db8e: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108ab10)
Location: kernel/softirq.c:432
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/rcu/tree.c:invoke_rcu_core
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff8108ab10-ffffffff8108abbe: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810917e0)
Location: kernel/softirq.c:432
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810917e0-ffffffff81091894: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810952c0)
Location: kernel/softirq.c:439
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810952c0-ffffffff81095375: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109d640)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff8109d640-ffffffff8109d6f5: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a1c00)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810a1c00-ffffffff810a1cb5: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a81c0)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810a81c0-ffffffff810a8275: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810afab0)
Location: kernel/softirq.c:467
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810afab0-ffffffff810afb62: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ab230)
Location: kernel/softirq.c:470
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810ab230-ffffffff810ab2cf: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ac420)
Location: kernel/softirq.c:687
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810ac420-ffffffff810ac4c6: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810bdbd0)
Location: kernel/softirq.c:686
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810bdbd0-ffffffff810bdc2d: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d4c10)
Location: kernel/softirq.c:700
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:update_process_times
  - block/blk-mq.c:blk_mq_complete_request_remote
```
**Symbols:**

```
ffffffff810d4c10-ffffffff810d4c69: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f3bf0)
Location: kernel/softirq.c:700
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:update_process_times
  - block/blk-mq.c:blk_mq_complete_request_remote
```
**Symbols:**

```
ffffffff810f3bf0-ffffffff810f3c58: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81100020)
Location: kernel/softirq.c:682
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:update_process_times
  - block/blk-mq.c:blk_mq_complete_request_remote
```
**Symbols:**

```
ffffffff81100020-ffffffff81100088: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81109740)
Location: kernel/softirq.c:682
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:update_process_times
  - block/blk-mq.c:blk_mq_complete_request_remote
```
**Symbols:**

```
ffffffff81109740-ffffffff811097a8: raise_softirq (STB_GLOBAL)
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
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000100ff518)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffff8000100ff518-ffff8000100ff590: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c035c17c)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
c035c17c-c035c1d4: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c0000000001468b0)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
c0000000001468b0-c000000000146934: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe0000c7362)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffe0000c7362-ffffffe0000c73c6: raise_softirq (STB_GLOBAL)
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
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a1ae0)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810a1ae0-ffffffff810a1b95: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810904e0)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810904e0-ffffffff8109057e: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a1a90)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810a1a90-ffffffff810a1b45: raise_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void raise_softirq(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a9a90)
Location: kernel/softirq.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/time/timer.c:run_local_timers
```
**Symbols:**

```
ffffffff810a9a90-ffffffff810a9b5e: raise_softirq (STB_GLOBAL)
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
