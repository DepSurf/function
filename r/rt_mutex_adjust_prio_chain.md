# Function: <code>rt_mutex_adjust_prio_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810caf60)
Location: kernel/locking/rtmutex.c:424
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
```
**Symbols:**

```
ffffffff810caf60-ffffffff810cb390: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cfa50)
Location: kernel/locking/rtmutex.c:426
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810cfa50-ffffffff810cfe19: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d6430)
Location: kernel/locking/rtmutex.c:490
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810d6430-ffffffff810d680c: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5400)
Location: kernel/locking/rtmutex.c:460
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810d5400-ffffffff810d586f: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810dd2e0)
Location: kernel/locking/rtmutex.c:448
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810dd2e0-ffffffff810dd7c5: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex.c:448
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810e59a0-ffffffff810e5e34: rt_mutex_adjust_prio_chain (STB_LOCAL)
ffffffff810e6521-ffffffff810e6549: rt_mutex_adjust_prio_chain.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex.c:448
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810f0f20-ffffffff810f13bd: rt_mutex_adjust_prio_chain (STB_LOCAL)
ffffffff810f1aa1-ffffffff810f1ac9: rt_mutex_adjust_prio_chain.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex.c:449
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810f96c0-ffffffff810f9bff: rt_mutex_adjust_prio_chain (STB_LOCAL)
ffffffff810fa3b6-ffffffff810fa3de: rt_mutex_adjust_prio_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex.c:449
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff811054b0-ffffffff811059ef: rt_mutex_adjust_prio_chain (STB_LOCAL)
ffffffff81106193-ffffffff811061bb: rt_mutex_adjust_prio_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex.c:447
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff81110260-ffffffff811108c6: rt_mutex_adjust_prio_chain (STB_LOCAL)
ffffffff8111113b-ffffffff81111163: rt_mutex_adjust_prio_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex.c:447
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff8110d410-ffffffff8110da76: rt_mutex_adjust_prio_chain (STB_LOCAL)
ffffffff81bde8c1-ffffffff81bde8e9: rt_mutex_adjust_prio_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c36200)
Location: kernel/locking/rtmutex.c:424
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff81c36200-ffffffff81c36a45: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex_base *orig_lock, struct rt_mutex_base *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d54ae0)
Location: kernel/locking/rtmutex.c:567
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
```
**Symbols:**

```
ffffffff81d54ae0-ffffffff81d55359: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex_base *orig_lock, struct rt_mutex_base *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f26690)
Location: kernel/locking/rtmutex.c:576
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
```
**Symbols:**

```
ffffffff81f26690-ffffffff81f26fbc: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex_base *orig_lock, struct rt_mutex_base *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d2140)
Location: kernel/locking/rtmutex.c:613
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
```
**Symbols:**

```
ffffffff820d2140-ffffffff820d2a62: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex_base *orig_lock, struct rt_mutex_base *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82156500)
Location: kernel/locking/rtmutex.c:655
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
```
**Symbols:**

```
ffffffff82156500-ffffffff82156ddc: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex_base *orig_lock, struct rt_mutex_base *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82239340)
Location: kernel/locking/rtmutex.c:674
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
```
**Symbols:**

```
ffffffff82239340-ffffffff82239c1c: rt_mutex_adjust_prio_chain (STB_LOCAL)
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
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016b1d8)
Location: kernel/locking/rtmutex.c:449
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffff80001016b1d8-ffff80001016b9c0: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b6dbc)
Location: kernel/locking/rtmutex.c:449
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
c03b6dbc-c03b7474: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c2b40)
Location: kernel/locking/rtmutex.c:449
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
c0000000001c2b40-c0000000001c3458: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010b76e)
Location: kernel/locking/rtmutex.c:449
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffe00010b76e-ffffffe00010bdbc: rt_mutex_adjust_prio_chain (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex.c:449
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810fe7c0-ffffffff810fecff: rt_mutex_adjust_prio_chain (STB_LOCAL)
ffffffff810ff4a3-ffffffff810ff4cb: rt_mutex_adjust_prio_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex.c:449
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810ee9c0-ffffffff810eeee1: rt_mutex_adjust_prio_chain (STB_LOCAL)
ffffffff810ef68d-ffffffff810ef6b5: rt_mutex_adjust_prio_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex.c:449
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810fb980-ffffffff810fbebf: rt_mutex_adjust_prio_chain (STB_LOCAL)
ffffffff810fc663-ffffffff810fc68b: rt_mutex_adjust_prio_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct *task, enum rtmutex_chainwalk chwalk, struct rt_mutex *orig_lock, struct rt_mutex *next_lock, struct rt_mutex_waiter *orig_waiter, struct task_struct *top_task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (0)
Location: kernel/locking/rtmutex.c:449
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff81106b40-ffffffff811070dd: rt_mutex_adjust_prio_chain (STB_LOCAL)
ffffffff8110788a-ffffffff811078b2: rt_mutex_adjust_prio_chain.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt_mutex *orig_lock</code> ➡️ <code>struct rt_mutex_base *orig_lock</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt_mutex *next_lock</code> ➡️ <code>struct rt_mutex_base *next_lock</code>
</li>
</ul>
</details>
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
