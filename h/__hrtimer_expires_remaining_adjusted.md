# Function: <code>__hrtimer_expires_remaining_adjusted</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f0c0a)
Location: include/linux/hrtimer.h:327
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_get
```
```
In fs/timerfd.c (ffffffff81257fa2)
Location: include/linux/hrtimer.h:327
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f7c2a)
Location: include/linux/hrtimer.h:327
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_get
```
```
In fs/timerfd.c (ffffffff812808a2)
Location: include/linux/hrtimer.h:327
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811055ca)
Location: include/linux/hrtimer.h:327
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_get
```
```
In fs/timerfd.c (ffffffff81294412)
Location: include/linux/hrtimer.h:327
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81107405)
Location: include/linux/hrtimer.h:311
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff812a16f2)
Location: include/linux/hrtimer.h:311
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81112535)
Location: include/linux/hrtimer.h:311
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff812c4a18)
Location: include/linux/hrtimer.h:311
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111df35)
Location: include/linux/hrtimer.h:331
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff812ed8a8)
Location: include/linux/hrtimer.h:331
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811296d5)
Location: include/linux/hrtimer.h:328
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff81302238)
Location: include/linux/hrtimer.h:328
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81134155)
Location: include/linux/hrtimer.h:314
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff813237a9)
Location: include/linux/hrtimer.h:314
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811400f5)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff81336509)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114f565)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff8137083f)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114b7e5)
Location: include/linux/hrtimer.h:334
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff8137e5ba)
Location: include/linux/hrtimer.h:334
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114cc95)
Location: include/linux/hrtimer.h:334
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff8138523a)
Location: include/linux/hrtimer.h:334
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81170b25)
Location: include/linux/hrtimer.h:330
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff813d24ba)
Location: include/linux/hrtimer.h:330
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a5135)
Location: include/linux/hrtimer.h:330
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff8145c05e)
Location: include/linux/hrtimer.h:330
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e4a65)
Location: include/linux/hrtimer.h:330
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff814eb72e)
Location: include/linux/hrtimer.h:330
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f90c5)
Location: include/linux/hrtimer.h:330
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff815224d1)
Location: include/linux/hrtimer.h:330
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120f2b5)
Location: include/linux/hrtimer.h:292
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff81556af1)
Location: include/linux/hrtimer.h:292
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101aa574)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffff8000103f4244)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f5824)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (c05c925c)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c00000000020dc48)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (c0000000004fc18c)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe0001358ae)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffe0002a560e)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811388a5)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff8132eae9)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112b2f5)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff8131f729)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811365c5)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff8132c5b9)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81142f85)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_remaining
```
```
In fs/timerfd.c (ffffffff8133ef39)
Location: include/linux/hrtimer.h:333
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_get_remaining
```
</details>
</li>
</ul>

## Differences
