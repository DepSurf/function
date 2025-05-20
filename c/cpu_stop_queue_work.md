# Function: <code>cpu_stop_queue_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8111ff00)
Location: kernel/stop_machine.c:84
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/stop_machine.c:stop_one_cpu_nowait
```
**Symbols:**

```
ffffffff8111ff00-ffffffff8111ff7b: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81127e50)
Location: kernel/stop_machine.c:80
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff81127e50-ffffffff81127ed9: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81131ae0)
Location: kernel/stop_machine.c:75
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff81131ae0-ffffffff81131b69: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811330b0)
Location: kernel/stop_machine.c:75
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff811330b0-ffffffff81133136: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8113fe60)
Location: kernel/stop_machine.c:75
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff8113fe60-ffffffff8113fee6: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114e750)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff8114e750-ffffffff8114e829: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115b440)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff8115b440-ffffffff8115b519: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81167ad0)
Location: kernel/stop_machine.c:76
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff81167ad0-ffffffff81167baf: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81173990)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff81173990-ffffffff81173a6f: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81185840)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff81185840-ffffffff8118592a: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81182950)
Location: kernel/stop_machine.c:93
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff81182950-ffffffff81182a3a: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81183aa0)
Location: kernel/stop_machine.c:93
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff81183aa0-ffffffff81183b8a: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:93
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff811abc40-ffffffff811abd56: cpu_stop_queue_work (STB_LOCAL)
ffffffff81cb338d-ffffffff81cb33aa: cpu_stop_queue_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:93
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff811dd660-ffffffff811dd799: cpu_stop_queue_work (STB_LOCAL)
ffffffff81e6422b-ffffffff81e64248: cpu_stop_queue_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:93
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff812230a0-ffffffff812231d9: cpu_stop_queue_work (STB_LOCAL)
ffffffff8205c561-ffffffff8205c57e: cpu_stop_queue_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:93
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff81239770-ffffffff812398a9: cpu_stop_queue_work (STB_LOCAL)
ffffffff820daebe-ffffffff820daedb: cpu_stop_queue_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:93
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff81253440-ffffffff81253579: cpu_stop_queue_work (STB_LOCAL)
ffffffff821b6bbc-ffffffff821b6bd9: cpu_stop_queue_work.cold (STB_LOCAL)
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e81c8)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffff8000101e81c8-ffff8000101e8314: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c042814c)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
c042814c-c0428238: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c000000000258830)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
c000000000258830-c000000000258974: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00015d114)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffe00015d114-ffffffe00015d1e8: cpu_stop_queue_work (STB_LOCAL)
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116bfb0)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff8116bfb0-ffffffff8116c08f: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115f1b0)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff8115f1b0-ffffffff8115f28f: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81169d80)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff81169d80-ffffffff81169e5f: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811774a0)
Location: kernel/stop_machine.c:77
Inline: False
Direct callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_one_cpu_nowait
  - kernel/stop_machine.c:stop_one_cpu
```
**Symbols:**

```
ffffffff811774a0-ffffffff81177596: cpu_stop_queue_work (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
