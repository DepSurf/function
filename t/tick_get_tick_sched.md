# Function: <code>tick_get_tick_sched</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff810fea40)
Location: kernel/time/tick-sched.c:44
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff810fea40-ffffffff810fea5d: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81105de0)
Location: kernel/time/tick-sched.c:38
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81105de0-ffffffff81105dfd: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110d520)
Location: kernel/time/tick-sched.c:38
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8110d520-ffffffff8110d53d: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110f3e0)
Location: kernel/time/tick-sched.c:42
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8110f3e0-ffffffff8110f3fd: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8111a785)
Location: kernel/time/tick-sched.c:43
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8111a6a0-ffffffff8111a6bd: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81127585)
Location: kernel/time/tick-sched.c:43
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff811270d0-ffffffff811270ed: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81132c75)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff811327c0-ffffffff811327dd: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113d815)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8113d330-ffffffff8113d34d: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811493b5)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81148ed0-ffffffff81148eed: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811592f5)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81158fe0-ffffffff81158ffd: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811552d5)
Location: kernel/time/tick-sched.c:41
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81154fc0-ffffffff81154fdd: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81156645)
Location: kernel/time/tick-sched.c:41
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81156330-ffffffff8115634d: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8117b345)
Location: kernel/time/tick-sched.c:41
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8117afe0-ffffffff8117b028: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811b09a5)
Location: kernel/time/tick-sched.c:41
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff811b0610-ffffffff811b0660: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f1545)
Location: kernel/time/tick-sched.c:41
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff811f1110-ffffffff811f1160: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81205d45)
Location: kernel/time/tick-sched.c:41
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81205900-ffffffff81205950: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8121cf55)
Location: kernel/time/tick-sched.c:41
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8121c4c0-ffffffff8121c510: tick_get_tick_sched (STB_GLOBAL)
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
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffff8000101b5900)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffff8000101b5348-ffff8000101b5384: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c03ff870)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
c03ff1c8-c03ff1f8: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c00000000021b160)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
c00000000021aa20-c00000000021aa50: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffe00013baec)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffe00013b580-ffffffe00013b5b8: tick_get_tick_sched (STB_GLOBAL)
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
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811419d5)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff811414f0-ffffffff8114150d: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81134d45)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff811346a0-ffffffff811346bd: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113f885)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8113f3a0-ffffffff8113f3bd: tick_get_tick_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct tick_sched *tick_get_tick_sched(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8114c3b5)
Location: kernel/time/tick-sched.c:40
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu
Direct callers:
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8114beb0-ffffffff8114becd: tick_get_tick_sched (STB_GLOBAL)
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
