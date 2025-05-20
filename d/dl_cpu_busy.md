# Function: <code>dl_cpu_busy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c9320)
Location: kernel/sched/deadline.c:2649
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810c9320-ffffffff810c93d3: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d0a10)
Location: kernel/sched/deadline.c:2636
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810d0a10-ffffffff810d0ac3: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d8f30)
Location: kernel/sched/deadline.c:2729
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810d8f30-ffffffff810d8fe6: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e2a30)
Location: kernel/sched/deadline.c:2732
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810e2a30-ffffffff810e2ae6: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e9540)
Location: kernel/sched/deadline.c:2723
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810e9540-ffffffff810e95e9: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f5020)
Location: kernel/sched/deadline.c:2770
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810f5020-ffffffff810f50c9: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fe740)
Location: kernel/sched/deadline.c:2770
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810fe740-ffffffff810fe7e6: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fd090)
Location: kernel/sched/deadline.c:2921
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810fd090-ffffffff810fd1de: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ff430)
Location: kernel/sched/deadline.c:2905
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810ff430-ffffffff810ff594: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff8111b430)
Location: kernel/sched/deadline.c:2919
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff8111b430-ffffffff8111b64e: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dl_cpu_busy(int cpu, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8113b0c0)
Location: kernel/sched/deadline.c:3026
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:task_can_attach
```
**Symbols:**

```
ffffffff8113b0c0-ffffffff8113b48a: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dl_cpu_busy(int cpu, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81165a60)
Location: kernel/sched/deadline.c:3024
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:task_can_attach
```
**Symbols:**

```
ffffffff81165a60-ffffffff81165e4b: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff8000101578a0)
Location: kernel/sched/deadline.c:2770
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffff8000101578a0-ffff8000101579dc: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a5614)
Location: kernel/sched/deadline.c:2770
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
c03a5614-c03a570c: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001ac440)
Location: kernel/sched/deadline.c:2770
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
c0000000001ac440-c0000000001ac578: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fe5c2)
Location: kernel/sched/deadline.c:2770
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffe0000fe5c2-ffffffe0000fe68c: dl_cpu_busy (STB_GLOBAL)
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
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ee420)
Location: kernel/sched/deadline.c:2770
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810ee420-ffffffff810ee4c9: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810de4b0)
Location: kernel/sched/deadline.c:2770
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810de4b0-ffffffff810de559: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eb550)
Location: kernel/sched/deadline.c:2770
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810eb550-ffffffff810eb5f9: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool dl_cpu_busy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f6590)
Location: kernel/sched/deadline.c:2770
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810f6590-ffffffff810f665c: dl_cpu_busy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *p</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int cpu</code> ➡️ <code>int cpu</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
