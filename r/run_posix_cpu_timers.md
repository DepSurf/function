# Function: <code>run_posix_cpu_timers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void run_posix_cpu_timers(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f3860)
Location: kernel/time/posix-cpu-timers.c:1185
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810f3860-ffffffff810f4032: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void run_posix_cpu_timers(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810fa9a0)
Location: kernel/time/posix-cpu-timers.c:1156
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff810fa9a0-ffffffff810fb1bb: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void run_posix_cpu_timers(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81108320)
Location: kernel/time/posix-cpu-timers.c:1152
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81108320-ffffffff81108b3b: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void run_posix_cpu_timers(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8110a500)
Location: kernel/time/posix-cpu-timers.c:1123
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8110a500-ffffffff8110ad1b: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void run_posix_cpu_timers(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811156c0)
Location: kernel/time/posix-cpu-timers.c:1122
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff811156c0-ffffffff81115ec5: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void run_posix_cpu_timers(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:1138
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff811228a5-ffffffff81122925: run_posix_cpu_timers.cold.20 (STB_LOCAL)
ffffffff81121e50-ffffffff811226ec: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void run_posix_cpu_timers(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:1136
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8112df85-ffffffff8112e005: run_posix_cpu_timers.cold.20 (STB_LOCAL)
ffffffff8112d570-ffffffff8112ddc6: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void run_posix_cpu_timers(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:1135
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81138997-ffffffff81138a17: run_posix_cpu_timers.cold (STB_LOCAL)
ffffffff81137f80-ffffffff811387e7: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811440b0)
Location: kernel/time/posix-cpu-timers.c:1113
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff811440b0-ffffffff8114454c: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81153cb0)
Location: kernel/time/posix-cpu-timers.c:1088
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81153cb0-ffffffff81153ea7: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81150120)
Location: kernel/time/posix-cpu-timers.c:1296
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81150120-ffffffff8115020b: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81151550)
Location: kernel/time/posix-cpu-timers.c:1296
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81151550-ffffffff8115163b: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81175950)
Location: kernel/time/posix-cpu-timers.c:1369
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81175950-ffffffff81175a3b: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811aa8f0)
Location: kernel/time/posix-cpu-timers.c:1376
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff811aa8f0-ffffffff811aaa03: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811ea9e0)
Location: kernel/time/posix-cpu-timers.c:1376
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff811ea9e0-ffffffff811eaaf3: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811ff130)
Location: kernel/time/posix-cpu-timers.c:1434
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff811ff130-ffffffff811ff243: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff812154b0)
Location: kernel/time/posix-cpu-timers.c:1434
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff812154b0-ffffffff8121560e: run_posix_cpu_timers (STB_GLOBAL)
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
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ae648)
Location: kernel/time/posix-cpu-timers.c:1113
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffff8000101ae648-ffff8000101aea8c: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f9660)
Location: kernel/time/posix-cpu-timers.c:1113
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
c03f9660-c03f9b9c: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000212bd0)
Location: kernel/time/posix-cpu-timers.c:1113
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
c000000000212bd0-c00000000021308c: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe00013811e)
Location: kernel/time/posix-cpu-timers.c:1113
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffe00013811e-ffffffe00013847a: run_posix_cpu_timers (STB_GLOBAL)
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
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113c860)
Location: kernel/time/posix-cpu-timers.c:1113
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8113c860-ffffffff8113ccfc: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112f300)
Location: kernel/time/posix-cpu-timers.c:1113
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8112f300-ffffffff8112f815: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113a580)
Location: kernel/time/posix-cpu-timers.c:1113
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8113a580-ffffffff8113aa1c: run_posix_cpu_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void run_posix_cpu_timers();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81147040)
Location: kernel/time/posix-cpu-timers.c:1113
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81147040-ffffffff811474da: run_posix_cpu_timers (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
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
