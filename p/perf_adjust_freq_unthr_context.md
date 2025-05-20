# Function: <code>perf_adjust_freq_unthr_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117f701)
Location: kernel/events/core.c:2993
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119152f)
Location: kernel/events/core.c:3229
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
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
In kernel/events/core.c (ffffffff811a0cdf)
Location: kernel/events/core.c:3300
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
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
In kernel/events/core.c (ffffffff811a869e)
Location: kernel/events/core.c:3387
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
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
In kernel/events/core.c (ffffffff811bbe0f)
Location: kernel/events/core.c:3290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dbfa5)
Location: kernel/events/core.c:3597
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ec36c)
Location: kernel/events/core.c:3592
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81203d78)
Location: kernel/events/core.c:3619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210968)
Location: kernel/events/core.c:3704
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_adjust_freq_unthr_context(struct perf_event_context *ctx, int needs_unthr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812381d0)
Location: kernel/events/core.c:3921
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff812381d0-ffffffff81238496: perf_adjust_freq_unthr_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_adjust_freq_unthr_context(struct perf_event_context *ctx, int needs_unthr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242240)
Location: kernel/events/core.c:3998
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff81242240-ffffffff81242506: perf_adjust_freq_unthr_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_adjust_freq_unthr_context(struct perf_event_context *ctx, int needs_unthr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81247210)
Location: kernel/events/core.c:4027
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff81247210-ffffffff812474d6: perf_adjust_freq_unthr_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_adjust_freq_unthr_context(struct perf_event_context *ctx, int needs_unthr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81281570)
Location: kernel/events/core.c:4123
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff81281570-ffffffff81281836: perf_adjust_freq_unthr_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_adjust_freq_unthr_context(struct perf_event_context *ctx, int needs_unthr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d58a0)
Location: kernel/events/core.c:4022
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff812d58a0-ffffffff812d5b85: perf_adjust_freq_unthr_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_adjust_freq_unthr_context(struct perf_event_context *ctx, bool unthrottle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133c850)
Location: kernel/events/core.c:4105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff8133c850-ffffffff8133ca54: perf_adjust_freq_unthr_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_adjust_freq_unthr_context(struct perf_event_context *ctx, bool unthrottle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136d9d0)
Location: kernel/events/core.c:4105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff8136d9d0-ffffffff8136dbd4: perf_adjust_freq_unthr_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_adjust_freq_unthr_context(struct perf_event_context *ctx, bool unthrottle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81396aa0)
Location: kernel/events/core.c:4137
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff81396aa0-ffffffff81396ca4: perf_adjust_freq_unthr_context (STB_LOCAL)
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
In kernel/events/core.c (ffff80001029ae60)
Location: kernel/events/core.c:3704
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04ca2f8)
Location: kernel/events/core.c:3704
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
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
In kernel/events/core.c (c00000000034ab00)
Location: kernel/events/core.c:3704
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
In kernel/events/core.c (ffffffe0001cd550)
Location: kernel/events/core.c:3704
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208fb8)
Location: kernel/events/core.c:3704
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fbd58)
Location: kernel/events/core.c:3704
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81206d58)
Location: kernel/events/core.c:3704
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81215ad8)
Location: kernel/events/core.c:3704
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_task_tick
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool unthrottle</code>
</li>
<li>
<b>Param removed. </b>
<code>int needs_unthr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
