# Function: <code>nr_iowait_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad060)
Location: kernel/sched/core.c:2765
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:update_ts_time_stats
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
```
**Symbols:**

```
ffffffff810ad060-ffffffff810ad084: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afad0)
Location: kernel/sched/core.c:2948
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
**Symbols:**

```
ffffffff810afad0-ffffffff810afaf4: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5c10)
Location: kernel/sched/core.c:2962
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
**Symbols:**

```
ffffffff810b5c10-ffffffff810b5c34: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b1ea0)
Location: kernel/sched/core.c:2870
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
**Symbols:**

```
ffffffff810b1ea0-ffffffff810b1ec4: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9250)
Location: kernel/sched/core.c:2899
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
**Symbols:**

```
ffffffff810b9250-ffffffff810b9274: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c0d40)
Location: kernel/sched/core.c:2952
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
**Symbols:**

```
ffffffff810c0d40-ffffffff810c0d64: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ca09e)
Location: kernel/sched/core.c:2903
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810ca050-ffffffff810ca074: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1d3f)
Location: kernel/sched/core.c:3313
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810d1cf0-ffffffff810d1d14: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbd1f)
Location: kernel/sched/core.c:3444
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810dbcd0-ffffffff810dbcf4: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e4c2f)
Location: kernel/sched/core.c:3605
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810e4be0-ffffffff810e4c04: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e271f)
Location: kernel/sched/core.c:4381
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810e26d0-ffffffff810e26f4: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e44f8)
Location: kernel/sched/core.c:4400
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810e44a0-ffffffff810e44c4: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fb26b)
Location: kernel/sched/core.c:5012
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810fb1f0-ffffffff810fb233: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8111773b)
Location: kernel/sched/core.c:5215
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff811176c0-ffffffff8111770b: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113ecd8)
Location: kernel/sched/core.c:5355
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff8113ec50-ffffffff8113ec9b: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114b538)
Location: kernel/sched/core.c:5445
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:tick_nohz_stop_idle
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff8114b4b0-ffffffff8114b4fb: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81157168)
Location: kernel/sched/core.c:5464
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:tick_nohz_stop_idle
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff811570e0-ffffffff8115712b: nr_iowait_cpu (STB_GLOBAL)
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
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013bc50)
Location: kernel/sched/core.c:3444
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffff80001013bba8-ffff80001013bbec: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038b420)
Location: kernel/sched/core.c:3444
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
c038b394-c038b3c8: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000189b0c)
Location: kernel/sched/core.c:3444
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
c000000000189a50-c000000000189a88: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000eb0d4)
Location: kernel/sched/core.c:3444
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
```
**Symbols:**

```
ffffffe0000eb074-ffffffe0000eb0b6: nr_iowait_cpu (STB_GLOBAL)
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
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d618f)
Location: kernel/sched/core.c:3444
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810d6140-ffffffff810d6164: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c481f)
Location: kernel/sched/core.c:3444
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810c47d0-ffffffff810c47f4: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2fbf)
Location: kernel/sched/core.c:3444
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810d2f70-ffffffff810d2f94: nr_iowait_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_iowait_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddaaf)
Location: kernel/sched/core.c:3444
Inline: True
Inline callers:
  - kernel/sched/core.c:nr_iowait
Direct callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:update_ts_time_stats
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810dda60-ffffffff810dda84: nr_iowait_cpu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
