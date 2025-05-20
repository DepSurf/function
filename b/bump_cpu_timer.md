# Function: <code>bump_cpu_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bump_cpu_timer(struct k_itimer *timer, long long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f2230)
Location: kernel/time/posix-cpu-timers.c:82
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff810f2230-ffffffff810f229d: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bump_cpu_timer(struct k_itimer *timer, long long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f9300)
Location: kernel/time/posix-cpu-timers.c:82
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff810f9300-ffffffff810f936a: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bump_cpu_timer(struct k_itimer *timer, long long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81106c90)
Location: kernel/time/posix-cpu-timers.c:81
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81106c90-ffffffff81106cfa: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81109130)
Location: kernel/time/posix-cpu-timers.c:63
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81109130-ffffffff811091a3: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81114300)
Location: kernel/time/posix-cpu-timers.c:64
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81114300-ffffffff81114373: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81120ab0)
Location: kernel/time/posix-cpu-timers.c:65
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81120ab0-ffffffff81120b25: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112c1d0)
Location: kernel/time/posix-cpu-timers.c:65
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff8112c1d0-ffffffff8112c245: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81136bb0)
Location: kernel/time/posix-cpu-timers.c:65
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81136bb0-ffffffff81136c25: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81142c60)
Location: kernel/time/posix-cpu-timers.c:125
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81142c60-ffffffff81142ce5: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81152520)
Location: kernel/time/posix-cpu-timers.c:115
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81152520-ffffffff811525a2: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114e7a0)
Location: kernel/time/posix-cpu-timers.c:115
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff8114e7a0-ffffffff8114e822: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114fc40)
Location: kernel/time/posix-cpu-timers.c:115
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff8114fc40-ffffffff8114fcc2: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:115
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81173f10-ffffffff81173fb2: bump_cpu_timer (STB_LOCAL)
ffffffff81cb1c45-ffffffff81cb1c6e: bump_cpu_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:122
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff811a8be0-ffffffff811a8c91: bump_cpu_timer (STB_LOCAL)
ffffffff81e631f1-ffffffff81e6321a: bump_cpu_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:122
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff811e8a10-ffffffff811e8ac1: bump_cpu_timer (STB_LOCAL)
ffffffff8205bb75-ffffffff8205bb9e: bump_cpu_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:122
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff811fd020-ffffffff811fd0d1: bump_cpu_timer (STB_LOCAL)
ffffffff820da377-ffffffff820da3a0: bump_cpu_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:122
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81213210-ffffffff812132c1: bump_cpu_timer (STB_LOCAL)
ffffffff821b5c76-ffffffff821b5c9f: bump_cpu_timer.cold (STB_LOCAL)
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
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101acf48)
Location: kernel/time/posix-cpu-timers.c:125
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffff8000101acf48-ffff8000101ad000: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f7c88)
Location: kernel/time/posix-cpu-timers.c:125
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
c03f7c88-c03f7e1c: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000210ca0)
Location: kernel/time/posix-cpu-timers.c:125
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
c000000000210ca0-c000000000210d48: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe000136e44)
Location: kernel/time/posix-cpu-timers.c:125
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffe000136e44-ffffffe000136ec2: bump_cpu_timer (STB_LOCAL)
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
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113b410)
Location: kernel/time/posix-cpu-timers.c:125
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff8113b410-ffffffff8113b495: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112de50)
Location: kernel/time/posix-cpu-timers.c:125
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff8112de50-ffffffff8112ded5: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81139130)
Location: kernel/time/posix-cpu-timers.c:125
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81139130-ffffffff811391b5: bump_cpu_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bump_cpu_timer(struct k_itimer *timer, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81145bd0)
Location: kernel/time/posix-cpu-timers.c:125
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
**Symbols:**

```
ffffffff81145bd0-ffffffff81145c55: bump_cpu_timer (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long long unsigned int now</code> ➡️ <code>u64 now</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
