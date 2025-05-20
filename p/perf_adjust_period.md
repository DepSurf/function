# Function: <code>perf_adjust_period</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81179d70)
Location: kernel/events/core.c:2959
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff81179d70-ffffffff81179f1b: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118a560)
Location: kernel/events/core.c:3195
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff8118a560-ffffffff8118a705: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81199950)
Location: kernel/events/core.c:3266
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff81199950-ffffffff81199af5: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1800)
Location: kernel/events/core.c:3353
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff811a1800-ffffffff811a19b2: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b5410)
Location: kernel/events/core.c:3256
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff811b5410-ffffffff811b55ce: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d42e0)
Location: kernel/events/core.c:3563
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff811d42e0-ffffffff811d44a6: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e4980)
Location: kernel/events/core.c:3558
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff811e4980-ffffffff811e4b46: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fbc90)
Location: kernel/events/core.c:3585
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff811fbc90-ffffffff811fbe78: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208d60)
Location: kernel/events/core.c:3670
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff81208d60-ffffffff81208f48: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81231ba0)
Location: kernel/events/core.c:3887
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_adjust_freq_unthr_context
```
**Symbols:**

```
ffffffff81231ba0-ffffffff81231c61: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123b810)
Location: kernel/events/core.c:3964
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_adjust_freq_unthr_context
```
**Symbols:**

```
ffffffff8123b810-ffffffff8123b8d1: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123fed0)
Location: kernel/events/core.c:3993
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_adjust_freq_unthr_context
```
**Symbols:**

```
ffffffff8123fed0-ffffffff812400a7: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127a770)
Location: kernel/events/core.c:4089
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_adjust_freq_unthr_context
```
**Symbols:**

```
ffffffff8127a770-ffffffff8127a947: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812ce2e0)
Location: kernel/events/core.c:3988
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_adjust_freq_unthr_context
```
**Symbols:**

```
ffffffff812ce2e0-ffffffff812ce4f5: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81335ca0)
Location: kernel/events/core.c:4070
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_adjust_freq_unthr_context
```
**Symbols:**

```
ffffffff81335ca0-ffffffff81335eb5: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813669f0)
Location: kernel/events/core.c:4070
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_account_interrupt
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_adjust_freq_unthr_context
```
**Symbols:**

```
ffffffff813669f0-ffffffff81366c08: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138f950)
Location: kernel/events/core.c:4102
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_adjust_freq_unthr_context
```
**Symbols:**

```
ffffffff8138f950-ffffffff8138fb65: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010296a4c)
Location: kernel/events/core.c:3670
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c1a44)
Location: kernel/events/core.c:3670
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
c04c1a44-c04c1dbc: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034ad50)
Location: kernel/events/core.c:3670
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c531a)
Location: kernel/events/core.c:3670
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201380)
Location: kernel/events/core.c:3670
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff81201380-ffffffff81201568: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f40d0)
Location: kernel/events/core.c:3670
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff811f40d0-ffffffff811f42b8: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff150)
Location: kernel/events/core.c:3670
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff811ff150-ffffffff811ff338: perf_adjust_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void perf_adjust_period(struct perf_event *event, u64 nsec, u64 count, bool disable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120e1e0)
Location: kernel/events/core.c:3670
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff8120e1e0-ffffffff8120e3c8: perf_adjust_period (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
