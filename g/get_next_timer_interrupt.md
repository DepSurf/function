# Function: <code>get_next_timer_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ee660)
Location: kernel/time/timer.c:1380
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810ee660-ffffffff810ee892: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f5660)
Location: kernel/time/timer.c:1494
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810f5660-ffffffff810f5786: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fc6d0)
Location: kernel/time/timer.c:1504
Inline: False
```
**Symbols:**

```
ffffffff810fc6d0-ffffffff810fc7e6: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810feb20)
Location: kernel/time/timer.c:1476
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810feb20-ffffffff810fec3e: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81109810)
Location: kernel/time/timer.c:1511
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff81109810-ffffffff8110992e: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81114e30)
Location: kernel/time/timer.c:1519
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81114e30-ffffffff81114f4d: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120470)
Location: kernel/time/timer.c:1518
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81120470-ffffffff8112058d: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112ad60)
Location: kernel/time/timer.c:1522
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff8112ad60-ffffffff8112ae7a: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81136d00)
Location: kernel/time/timer.c:1607
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81136d00-ffffffff81136e1a: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81145970)
Location: kernel/time/timer.c:1619
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81145970-ffffffff81145a8a: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141f50)
Location: kernel/time/timer.c:1631
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81141f50-ffffffff81142081: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81143150)
Location: kernel/time/timer.c:1650
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81143150-ffffffff8114327a: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1636
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81cb08ea-ffffffff81cb091c: get_next_timer_interrupt.cold (STB_LOCAL)
ffffffff811666a0-ffffffff811667f5: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1689
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81e61e75-ffffffff81e61ea7: get_next_timer_interrupt.cold (STB_LOCAL)
ffffffff81199d90-ffffffff81199ee8: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1921
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff8205ad46-ffffffff8205ad78: get_next_timer_interrupt.cold (STB_LOCAL)
ffffffff811d8460-ffffffff811d85b8: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1921
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff820d95f5-ffffffff820d9627: get_next_timer_interrupt.cold (STB_LOCAL)
ffffffff811ec890-ffffffff811ec9e8: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer.c (0)
Location: kernel/time/timer.c:1922
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff821b4e96-ffffffff821b4f0e: get_next_timer_interrupt.cold (STB_LOCAL)
ffffffff812028b0-ffffffff81202ad8: get_next_timer_interrupt (STB_GLOBAL)
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
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019fec0)
Location: kernel/time/timer.c:1607
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffff80001019fec0-ffff8000101a0074: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e9ad4)
Location: kernel/time/timer.c:1607
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
c03e9ad4-c03e9d18: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c000000000200d80)
Location: kernel/time/timer.c:1607
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
c000000000200d80-c000000000200fd0: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012dc02)
Location: kernel/time/timer.c:1607
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffe00012dc02-ffffffe00012dd60: get_next_timer_interrupt (STB_GLOBAL)
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
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112f4b0)
Location: kernel/time/timer.c:1607
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff8112f4b0-ffffffff8112f5ca: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81121f30)
Location: kernel/time/timer.c:1607
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81121f30-ffffffff8112204a: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d1d0)
Location: kernel/time/timer.c:1607
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff8112d1d0-ffffffff8112d2ea: get_next_timer_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 get_next_timer_interrupt(long unsigned int basej, u64 basem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81139ae0)
Location: kernel/time/timer.c:1607
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81139ae0-ffffffff81139bf8: get_next_timer_interrupt (STB_GLOBAL)
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
