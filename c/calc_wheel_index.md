# Function: <code>calc_wheel_index</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f2640)
Location: kernel/time/timer.c:474
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff810f2640-ffffffff810f276c: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f97c0)
Location: kernel/time/timer.c:474
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff810f97c0-ffffffff810f98ec: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fbce0)
Location: kernel/time/timer.c:477
Inline: False
Direct callers:
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff810fbce0-ffffffff810fbe14: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811065d0)
Location: kernel/time/timer.c:477
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff811065d0-ffffffff81106704: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81111c40)
Location: kernel/time/timer.c:494
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff81111c40-ffffffff81111d57: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111d280)
Location: kernel/time/timer.c:493
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff8111d280-ffffffff8111d397: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81127f00)
Location: kernel/time/timer.c:493
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff81127f00-ffffffff81128017: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81133ea0)
Location: kernel/time/timer.c:497
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff81133ea0-ffffffff81133fb7: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81142d60)
Location: kernel/time/timer.c:497
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff81142d60-ffffffff81142e7f: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk, long unsigned int *bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8113f370)
Location: kernel/time/timer.c:509
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff8113f370-ffffffff8113f4ec: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk, long unsigned int *bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140560)
Location: kernel/time/timer.c:510
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff81140560-ffffffff811406e4: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk, long unsigned int *bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811639f0)
Location: kernel/time/timer.c:510
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811639f0-ffffffff81163b74: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk, long unsigned int *bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81196b00)
Location: kernel/time/timer.c:533
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff81196b00-ffffffff81196c7c: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk, long unsigned int *bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d4c10)
Location: kernel/time/timer.c:533
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811d4c10-ffffffff811d4d8c: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk, long unsigned int *bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811e9000)
Location: kernel/time/timer.c:533
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811e9000-ffffffff811e917c: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk, long unsigned int *bucket_expiry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811fed80)
Location: kernel/time/timer.c:533
Inline: False
Direct callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
```
**Symbols:**

```
ffffffff811fed80-ffffffff811feefc: calc_wheel_index (STB_LOCAL)
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
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019c430)
Location: kernel/time/timer.c:497
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__mod_timer
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffff80001019c430-ffff80001019c57c: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e61e8)
Location: kernel/time/timer.c:497
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
c03e61e8-c03e62e4: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fc0f0)
Location: kernel/time/timer.c:497
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
c0000000001fc0f0-c0000000001fc264: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012afec)
Location: kernel/time/timer.c:497
Inline: False
Direct callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
```
**Symbols:**

```
ffffffe00012afec-ffffffe00012b126: calc_wheel_index (STB_LOCAL)
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
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112c650)
Location: kernel/time/timer.c:497
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff8112c650-ffffffff8112c767: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111eec0)
Location: kernel/time/timer.c:497
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff8111eec0-ffffffff8111efd7: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a370)
Location: kernel/time/timer.c:497
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff8112a370-ffffffff8112a487: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int calc_wheel_index(long unsigned int expires, long unsigned int clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811369c0)
Location: kernel/time/timer.c:497
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:__internal_add_timer
```
**Symbols:**

```
ffffffff811369c0-ffffffff81136ad7: calc_wheel_index (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *bucket_expiry</code>
</li>
</ul>
</details>
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
