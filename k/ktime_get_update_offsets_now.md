# Function: <code>ktime_get_update_offsets_now</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f6a50)
Location: kernel/time/timekeeping.c:2212
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_queues
```
**Symbols:**

```
ffffffff810f6a50-ffffffff810f6b4c: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fdbb0)
Location: kernel/time/timekeeping.c:2218
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff810fdbb0-ffffffff810fdcb0: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811009a0)
Location: kernel/time/timekeeping.c:2230
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff811009a0-ffffffff81100aa0: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81102ae0)
Location: kernel/time/timekeeping.c:2219
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81102ae0-ffffffff81102bdf: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110da80)
Location: kernel/time/timekeeping.c:2248
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8110da80-ffffffff8110db82: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81119470)
Location: kernel/time/timekeeping.c:2189
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81119470-ffffffff81119577: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81124960)
Location: kernel/time/timekeeping.c:2203
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81124960-ffffffff81124a67: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f2a0)
Location: kernel/time/timekeeping.c:2213
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8112f2a0-ffffffff8112f3a1: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113b260)
Location: kernel/time/timekeeping.c:2213
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8113b260-ffffffff8113b361: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8114a2b0)
Location: kernel/time/timekeeping.c:2212
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8114a2b0-ffffffff8114a3b3: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81146800)
Location: kernel/time/timekeeping.c:2275
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81146800-ffffffff81146903: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81147970)
Location: kernel/time/timekeeping.c:2286
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81147970-ffffffff81147a73: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2287
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81cb1373-ffffffff81cb1397: ktime_get_update_offsets_now.cold (STB_LOCAL)
ffffffff8116b490-ffffffff8116b59c: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2308
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81e62912-ffffffff81e62936: ktime_get_update_offsets_now.cold (STB_LOCAL)
ffffffff8119f3a0-ffffffff8119f4b1: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2308
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8205b74e-ffffffff8205b772: ktime_get_update_offsets_now.cold (STB_LOCAL)
ffffffff811de090-ffffffff811de1a1: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2308
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff820da008-ffffffff820da02c: ktime_get_update_offsets_now.cold (STB_LOCAL)
ffffffff811f2560-ffffffff811f2671: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2308
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff821b5907-ffffffff821b592b: ktime_get_update_offsets_now.cold (STB_LOCAL)
ffffffff812086a0-ffffffff812087b1: ktime_get_update_offsets_now (STB_GLOBAL)
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
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a5480)
Location: kernel/time/timekeeping.c:2213
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffff8000101a5480-ffff8000101a5580: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03f0424)
Location: kernel/time/timekeeping.c:2213
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
c03f0424-c03f05b4: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000207260)
Location: kernel/time/timekeeping.c:2213
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
c000000000207260-c0000000002073a4: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe0001318e8)
Location: kernel/time/timekeeping.c:2213
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffe0001318e8-ffffffe0001319ca: ktime_get_update_offsets_now (STB_GLOBAL)
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
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81133a10)
Location: kernel/time/timekeeping.c:2213
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81133a10-ffffffff81133b11: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81126470)
Location: kernel/time/timekeeping.c:2213
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81126470-ffffffff81126571: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131730)
Location: kernel/time/timekeeping.c:2213
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81131730-ffffffff81131831: ktime_get_update_offsets_now (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ktime_t ktime_get_update_offsets_now(unsigned int *cwsseq, ktime_t *offs_real, ktime_t *offs_boot, ktime_t *offs_tai);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113e150)
Location: kernel/time/timekeeping.c:2213
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8113e150-ffffffff8113e251: ktime_get_update_offsets_now (STB_GLOBAL)
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
