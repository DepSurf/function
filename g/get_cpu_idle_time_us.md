# Function: <code>get_cpu_idle_time_us</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff810fe1c0)
Location: kernel/time/tick-sched.c:490
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
**Symbols:**

```
ffffffff810fe1c0-ffffffff810fe285: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81105550)
Location: kernel/time/tick-sched.c:582
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81105550-ffffffff81105615: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110cc90)
Location: kernel/time/tick-sched.c:580
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff8110cc90-ffffffff8110cd55: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110eb70)
Location: kernel/time/tick-sched.c:590
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff8110eb70-ffffffff8110ec35: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81119dc0)
Location: kernel/time/tick-sched.c:566
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81119dc0-ffffffff81119e84: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81126970)
Location: kernel/time/tick-sched.c:556
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81126970-ffffffff81126a2a: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81132050)
Location: kernel/time/tick-sched.c:553
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81132050-ffffffff8113210a: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113ce90)
Location: kernel/time/tick-sched.c:562
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff8113ce90-ffffffff8113cf45: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81148740)
Location: kernel/time/tick-sched.c:566
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81148740-ffffffff811487f5: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81158ed0)
Location: kernel/time/tick-sched.c:591
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81158ed0-ffffffff81158fd3: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81154eb0)
Location: kernel/time/tick-sched.c:639
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81154eb0-ffffffff81154fb3: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81155f90)
Location: kernel/time/tick-sched.c:640
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81155f90-ffffffff81156093: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8117ac30)
Location: kernel/time/tick-sched.c:675
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff8117ac30-ffffffff8117ad49: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811b03b0)
Location: kernel/time/tick-sched.c:691
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff811b03b0-ffffffff811b04d3: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f0e90)
Location: kernel/time/tick-sched.c:691
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff811f0e90-ffffffff811f0fb3: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81205030)
Location: kernel/time/tick-sched.c:739
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81205030-ffffffff812050bd: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8121b700)
Location: kernel/time/tick-sched.c:740
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff8121b700-ffffffff8121b78d: get_cpu_idle_time_us (STB_GLOBAL)
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
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffff8000101b4930)
Location: kernel/time/tick-sched.c:566
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffff8000101b4930-ffff8000101b4a08: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c03fef18)
Location: kernel/time/tick-sched.c:566
Inline: False
Direct callers:
  - fs/proc/stat.c:get_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
c03fef18-c03ff070: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c000000000219c60)
Location: kernel/time/tick-sched.c:566
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
c000000000219c60-c000000000219dc0: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffe00013acae)
Location: kernel/time/tick-sched.c:566
Inline: False
```
**Symbols:**

```
ffffffe00013acae-ffffffe00013ad50: get_cpu_idle_time_us (STB_GLOBAL)
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
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81140d60)
Location: kernel/time/tick-sched.c:566
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81140d60-ffffffff81140e15: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81133b00)
Location: kernel/time/tick-sched.c:566
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff81133b00-ffffffff81133bb5: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113ec10)
Location: kernel/time/tick-sched.c:566
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff8113ec10-ffffffff8113ecc5: get_cpu_idle_time_us (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 get_cpu_idle_time_us(int cpu, u64 *last_update_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8114b780)
Location: kernel/time/tick-sched.c:566
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
**Symbols:**

```
ffffffff8114b780-ffffffff8114b835: get_cpu_idle_time_us (STB_GLOBAL)
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
