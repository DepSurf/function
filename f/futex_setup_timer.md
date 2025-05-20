# Function: <code>futex_setup_timer</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811418ca)
Location: kernel/futex.c:484
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (ffffffff8114d945)
Location: kernel/futex.c:489
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (ffffffff8115cf05)
Location: kernel/futex.c:418
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (ffffffff811590ef)
Location: kernel/futex.c:400
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (ffffffff8115b33f)
Location: kernel/futex.c:399
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (ffffffff8117fe61)
Location: kernel/futex.c:457
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct hrtimer_sleeper *futex_setup_timer(ktime_t *time, struct hrtimer_sleeper *timeout, int flags, u64 range_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2520)
Location: kernel/futex/core.c:135
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
```
**Symbols:**

```
ffffffff811b2520-ffffffff811b2588: futex_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hrtimer_sleeper *futex_setup_timer(ktime_t *time, struct hrtimer_sleeper *timeout, int flags, u64 range_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f33b0)
Location: kernel/futex/core.c:135
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
```
**Symbols:**

```
ffffffff811f33b0-ffffffff811f3418: futex_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hrtimer_sleeper *futex_setup_timer(ktime_t *time, struct hrtimer_sleeper *timeout, int flags, u64 range_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81207b30)
Location: kernel/futex/core.c:135
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
```
**Symbols:**

```
ffffffff81207b30-ffffffff81207b98: futex_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hrtimer_sleeper *futex_setup_timer(ktime_t *time, struct hrtimer_sleeper *timeout, int flags, u64 range_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121ed40)
Location: kernel/futex/core.c:136
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:futex2_setup_timeout
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
```
**Symbols:**

```
ffffffff8121ed40-ffffffff8121eda8: futex_setup_timer (STB_GLOBAL)
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
In kernel/futex.c (ffff8000101ba01c)
Location: kernel/futex.c:489
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (c0403c88)
Location: kernel/futex.c:489
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (c000000000221960)
Location: kernel/futex.c:489
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (ffffffe00013fb26)
Location: kernel/futex.c:489
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (ffffffff81145f65)
Location: kernel/futex.c:489
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (ffffffff81139275)
Location: kernel/futex.c:489
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (ffffffff81143e15)
Location: kernel/futex.c:489
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
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
In kernel/futex.c (ffffffff8114fea5)
Location: kernel/futex.c:489
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
