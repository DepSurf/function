# Function: <code>hrtimer_sleeper_start_expires</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81ad3c63)
Location: kernel/time/hrtimer.c:1782
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
**Symbols:**

```
ffffffff81138190-ffffffff811381ad: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81bcbc6f)
Location: kernel/time/hrtimer.c:1787
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
**Symbols:**

```
ffffffff81146da0-ffffffff81146dbd: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c44a8f)
Location: kernel/time/hrtimer.c:1804
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff81142eb0-ffffffff81142ecd: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c37cfc)
Location: kernel/time/hrtimer.c:1804
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff811443e0-ffffffff811443fd: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81d565bc)
Location: kernel/time/hrtimer.c:1952
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff81167c90-ffffffff81167cad: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81f28428)
Location: kernel/time/hrtimer.c:1952
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff8119b640-ffffffff8119b669: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff820d4078)
Location: kernel/time/hrtimer.c:1952
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff811d9ed0-ffffffff811d9ef9: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff821582d2)
Location: kernel/time/hrtimer.c:1955
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff811ee030-ffffffff811ee059: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8223b142)
Location: kernel/time/hrtimer.c:1956
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
  - fs/aio.c:read_events
```
**Symbols:**

```
ffffffff81204390-ffffffff812043b9: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff800010da6808)
Location: kernel/time/hrtimer.c:1782
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
**Symbols:**

```
ffff8000101a1a68-ffff8000101a1aa4: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c0e9e618)
Location: kernel/time/hrtimer.c:1782
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
**Symbols:**

```
c03eb704-c03eb74c: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000ee9054)
Location: kernel/time/hrtimer.c:1782
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
**Symbols:**

```
c000000000203010-c000000000203034: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe0008c8ba8)
Location: kernel/time/hrtimer.c:1782
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
**Symbols:**

```
ffffffe00012ef40-ffffffe00012ef78: hrtimer_sleeper_start_expires (STB_GLOBAL)
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
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a72ad3)
Location: kernel/time/hrtimer.c:1782
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
**Symbols:**

```
ffffffff81130940-ffffffff8113095d: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a2eea3)
Location: kernel/time/hrtimer.c:1782
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
**Symbols:**

```
ffffffff811233b0-ffffffff811233cd: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81adeee3)
Location: kernel/time/hrtimer.c:1782
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
**Symbols:**

```
ffffffff8112e660-ffffffff8112e67d: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper *sl, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81aeb373)
Location: kernel/time/hrtimer.c:1782
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
**Symbols:**

```
ffffffff8113b060-ffffffff8113b07d: hrtimer_sleeper_start_expires (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
