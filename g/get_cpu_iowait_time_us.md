# Function: <code>get_cpu_iowait_time_us</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff810fe290)
Location: kernel/time/tick-sched.c:531
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff810fe290-ffffffff810fe355: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81105620)
Location: kernel/time/tick-sched.c:623
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/intel_pstate.c:get_target_pstate_use_cpu_load
```
**Symbols:**

```
ffffffff81105620-ffffffff811056e5: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110cd60)
Location: kernel/time/tick-sched.c:621
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff8110cd60-ffffffff8110ce25: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110ec40)
Location: kernel/time/tick-sched.c:631
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff8110ec40-ffffffff8110ed05: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81119e90)
Location: kernel/time/tick-sched.c:607
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff81119e90-ffffffff81119f54: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81126a30)
Location: kernel/time/tick-sched.c:597
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff81126a30-ffffffff81126aea: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81132110)
Location: kernel/time/tick-sched.c:594
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff81132110-ffffffff811321ca: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113cf50)
Location: kernel/time/tick-sched.c:603
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff8113cf50-ffffffff8113d005: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81148800)
Location: kernel/time/tick-sched.c:607
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff81148800-ffffffff811488b5: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81158dc0)
Location: kernel/time/tick-sched.c:632
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff81158dc0-ffffffff81158ec3: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81154da0)
Location: kernel/time/tick-sched.c:680
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff81154da0-ffffffff81154ea3: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81155e80)
Location: kernel/time/tick-sched.c:681
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff81155e80-ffffffff81155f83: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8117ab10)
Location: kernel/time/tick-sched.c:716
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff8117ab10-ffffffff8117ac29: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811b04e0)
Location: kernel/time/tick-sched.c:732
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff811b04e0-ffffffff811b0603: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f0fd0)
Location: kernel/time/tick-sched.c:732
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff811f0fd0-ffffffff811f10f3: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff812050d0)
Location: kernel/time/tick-sched.c:765
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff812050d0-ffffffff8120515d: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8121b7a0)
Location: kernel/time/tick-sched.c:766
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff8121b7a0-ffffffff8121b82d: get_cpu_iowait_time_us (STB_GLOBAL)
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
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffff8000101b4a08)
Location: kernel/time/tick-sched.c:607
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffff8000101b4a08-ffff8000101b4ae0: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c03ff070)
Location: kernel/time/tick-sched.c:607
Inline: False
Direct callers:
  - fs/proc/stat.c:get_iowait_time
```
**Symbols:**

```
c03ff070-c03ff1c8: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c000000000219dc0)
Location: kernel/time/tick-sched.c:607
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
c000000000219dc0-c000000000219f20: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffe00013ad50)
Location: kernel/time/tick-sched.c:607
Inline: False
```
**Symbols:**

```
ffffffe00013ad50-ffffffe00013adf2: get_cpu_iowait_time_us (STB_GLOBAL)
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
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81140e20)
Location: kernel/time/tick-sched.c:607
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff81140e20-ffffffff81140ed5: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81133bc0)
Location: kernel/time/tick-sched.c:607
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff81133bc0-ffffffff81133c75: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113ecd0)
Location: kernel/time/tick-sched.c:607
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff8113ecd0-ffffffff8113ed85: get_cpu_iowait_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 get_cpu_iowait_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8114b840)
Location: kernel/time/tick-sched.c:607
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff8114b840-ffffffff8114b8f5: get_cpu_iowait_time_us (STB_GLOBAL)
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
