# Function: <code>ktime_get_clocktai</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eeb00)
Location: include/linux/timekeeping.h:196
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff810f0ae6)
Location: include/linux/timekeeping.h:196
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff81179801)
Location: include/linux/timekeeping.h:196
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_tai_ns
```
**Symbols:**

```
ffffffff810eeb00-ffffffff810eeb10: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5ae0)
Location: include/linux/timekeeping.h:212
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff810f7b06)
Location: include/linux/timekeeping.h:212
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff8118a0a1)
Location: include/linux/timekeeping.h:212
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_tai_ns
```
**Symbols:**

```
ffffffff810f5ae0-ffffffff810f5af0: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fcaa0)
Location: include/linux/timekeeping.h:212
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811054a6)
Location: include/linux/timekeeping.h:212
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff81199491)
Location: include/linux/timekeeping.h:212
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_tai_ns
```
**Symbols:**

```
ffffffff810fcaa0-ffffffff810fcab0: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fef00)
Location: include/linux/timekeeping.h:201
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811078d6)
Location: include/linux/timekeeping.h:201
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff811a13e1)
Location: include/linux/timekeeping.h:201
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_tai_ns
```
**Symbols:**

```
ffffffff810fef00-ffffffff810fef10: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81109ce0)
Location: include/linux/timekeeping.h:81
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81112a46)
Location: include/linux/timekeeping.h:81
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff811b4f61)
Location: include/linux/timekeeping.h:81
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_tai_ns
```
**Symbols:**

```
ffffffff81109ce0-ffffffff81109cf0: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115800)
Location: include/linux/timekeeping.h:91
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8111e4a5)
Location: include/linux/timekeeping.h:91
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff811d3dc0)
Location: include/linux/timekeeping.h:91
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_tai_ns
```
**Symbols:**

```
ffffffff81115800-ffffffff81115810: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120ed0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81129cf5)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff811e42c0)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_tai_ns
```
**Symbols:**

```
ffffffff81120ed0-ffffffff81120ee0: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b650)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81134775)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff811fb5b0)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff8112b650-ffffffff8112b660: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811377d0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81140785)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff81208960)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff811377d0-ffffffff811377e0: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146200)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8114f685)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
```
```
In kernel/events/core.c (ffffffff812313e0)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff81146200-ffffffff81146210: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142720)
Location: include/linux/timekeeping.h:105
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8114b905)
Location: include/linux/timekeeping.h:105
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
```
```
In kernel/events/core.c (ffffffff8123b050)
Location: include/linux/timekeeping.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff81142720-ffffffff81142730: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811438f0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8114cdb5)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
```
```
In kernel/events/core.c (ffffffff8123f810)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff811438f0-ffffffff81143900: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81166ce0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81170df5)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
```
```
In kernel/events/core.c (ffffffff8127a030)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff81166ce0-ffffffff81166cf0: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119a490)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811a5485)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
```
```
In kernel/events/core.c (ffffffff812cd510)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff8119a490-ffffffff8119a4a6: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d8bd0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811e4e55)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
```
```
In kernel/events/core.c (ffffffff81335420)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff811d8bd0-ffffffff811d8be6: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ed000)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811f94b5)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
```
```
In kernel/events/core.c (ffffffff81366170)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff811ed000-ffffffff811ed016: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81203230)
Location: include/linux/timekeeping.h:107
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8120f6a5)
Location: include/linux/timekeeping.h:107
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
```
```
In kernel/events/core.c (ffffffff8138f290)
Location: include/linux/timekeeping.h:107
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff81203230-ffffffff81203246: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0ae0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffff8000101aab40)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffff800010291d50)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffff8000101a0ae0-ffff8000101a0af8: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea8d0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (c03f6194)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (c04c2f24)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
c03ea8d0-c03ea8e8: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201ef0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (c00000000020e770)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (c000000000340394)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
c000000000201ef0-c000000000201f20: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e408)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffe000135e94)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffe0001c460e)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffe00012e408-ffffffe00012e422: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112ff80)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81138f35)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff81200f80)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff8112ff80-ffffffff8112ff90: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811229f0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8112b985)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff811f3cd0)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff811229f0-ffffffff81122a00: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112dca0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81136c55)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff811fed50)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff8112dca0-ffffffff8112dcb0: ktime_get_clocktai (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_clocktai();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a5f0)
Location: include/linux/timekeeping.h:106
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811436e5)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_tai
```
```
In kernel/events/core.c (ffffffff8120dde0)
Location: include/linux/timekeeping.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_clocktai_ns
```
**Symbols:**

```
ffffffff8113a5f0-ffffffff8113a600: ktime_get_clocktai (STB_LOCAL)
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
