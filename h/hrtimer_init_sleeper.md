# Function: <code>hrtimer_init_sleeper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ee9f0)
Location: kernel/time/hrtimer.c:1474
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_lock_pi
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff810ee9f0-ffffffff810eea07: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8189e2c3)
Location: kernel/time/hrtimer.c:1464
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff810f5ac0-ffffffff810f5ad7: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff818d3163)
Location: kernel/time/hrtimer.c:1464
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid_sleep
```
**Symbols:**

```
ffffffff810fca80-ffffffff810fca97: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8190a2d7)
Location: kernel/time/hrtimer.c:1436
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff810feee0-ffffffff810feef7: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8199460b)
Location: kernel/time/hrtimer.c:1441
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff81109cc0-ffffffff81109cd7: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff819f0e80)
Location: kernel/time/hrtimer.c:1652
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff81115420-ffffffff81115437: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a2c200)
Location: kernel/time/hrtimer.c:1642
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff81120a60-ffffffff81120a77: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a9c3ad)
Location: kernel/time/hrtimer.c:1642
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff8112b220-ffffffff8112b237: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811378f0)
Location: kernel/time/hrtimer.c:1837
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff811378f0-ffffffff8113797f: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81147572)
Location: kernel/time/hrtimer.c:1842
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff81146470-ffffffff811464fe: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142a30)
Location: kernel/time/hrtimer.c:1859
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff81142a30-ffffffff81142aa7: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143a20)
Location: kernel/time/hrtimer.c:1859
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff81143a20-ffffffff81143a97: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81d564a8)
Location: kernel/time/hrtimer.c:2007
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff81167580-ffffffff811675f4: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119beb6)
Location: kernel/time/hrtimer.c:2007
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/futex/core.c:futex_setup_timer
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff8119b110-ffffffff8119b1a7: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811da826)
Location: kernel/time/hrtimer.c:2007
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/futex/core.c:futex_setup_timer
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff811d9960-ffffffff811d99f7: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811eed4b)
Location: kernel/time/hrtimer.c:2010
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/futex/core.c:futex_setup_timer
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff811ee110-ffffffff811ee1a7: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81204ecb)
Location: kernel/time/hrtimer.c:2011
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/futex/core.c:futex_setup_timer
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff812037b0-ffffffff81203847: hrtimer_init_sleeper (STB_GLOBAL)
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
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0f00)
Location: kernel/time/hrtimer.c:1837
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffff8000101a0f00-ffff8000101a0fc8: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03eaa14)
Location: kernel/time/hrtimer.c:1837
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:do_io_getevents
```
**Symbols:**

```
c03eaa14-c03eaaec: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000202250)
Location: kernel/time/hrtimer.c:1837
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
c000000000202250-c000000000202380: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e562)
Location: kernel/time/hrtimer.c:1837
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffe00012e562-ffffffe00012e608: hrtimer_init_sleeper (STB_GLOBAL)
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
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811300a0)
Location: kernel/time/hrtimer.c:1837
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff811300a0-ffffffff8113012f: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122b10)
Location: kernel/time/hrtimer.c:1837
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff81122b10-ffffffff81122b9f: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112ddc0)
Location: kernel/time/hrtimer.c:1837
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff8112ddc0-ffffffff8112de4f: hrtimer_init_sleeper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper *sl, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a710)
Location: kernel/time/hrtimer.c:1837
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff8113a710-ffffffff8113a7b7: hrtimer_init_sleeper (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>clockid_t clock_id</code>
</li>
<li>
<b>Param added. </b>
<code>enum hrtimer_mode mode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
</ul>
</details>
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
