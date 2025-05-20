# Function: <code>queue_stop_cpus_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81120060)
Location: kernel/stop_machine.c:316
Inline: False
Direct callers:
  - kernel/stop_machine.c:__stop_cpus
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
```
**Symbols:**

```
ffffffff81120060-ffffffff811200fa: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81127fd0)
Location: kernel/stop_machine.c:322
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff81127fd0-ffffffff8112807c: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81131c60)
Location: kernel/stop_machine.c:335
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff81131c60-ffffffff81131d04: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81133230)
Location: kernel/stop_machine.c:335
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff81133230-ffffffff811332d3: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8113fef0)
Location: kernel/stop_machine.c:335
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff8113fef0-ffffffff8113ff83: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114e830)
Location: kernel/stop_machine.c:363
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff8114e830-ffffffff8114e8c3: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115b520)
Location: kernel/stop_machine.c:363
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff8115b520-ffffffff8115b5ae: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81167bd0)
Location: kernel/stop_machine.c:371
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff81167bd0-ffffffff81167c6c: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81173a90)
Location: kernel/stop_machine.c:373
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff81173a90-ffffffff81173b2c: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (ffffffff811859b0)
Location: kernel/stop_machine.c:374
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff811859b0-ffffffff81185a48: queue_stop_cpus_work.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (ffffffff81182ac0)
Location: kernel/stop_machine.c:391
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff81182ac0-ffffffff81182b58: queue_stop_cpus_work.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (ffffffff81183c10)
Location: kernel/stop_machine.c:391
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff81183c10-ffffffff81183cb0: queue_stop_cpus_work.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (ffffffff811abd60)
Location: kernel/stop_machine.c:391
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff811abd60-ffffffff811abe22: queue_stop_cpus_work.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (ffffffff811dd7a0)
Location: kernel/stop_machine.c:391
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff811dd7a0-ffffffff811dd880: queue_stop_cpus_work.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (ffffffff812231f0)
Location: kernel/stop_machine.c:391
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff812231f0-ffffffff812232df: queue_stop_cpus_work.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (ffffffff812398c0)
Location: kernel/stop_machine.c:391
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff812398c0-ffffffff812399af: queue_stop_cpus_work.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (ffffffff81253590)
Location: kernel/stop_machine.c:391
Inline: True
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff81253590-ffffffff8125367f: queue_stop_cpus_work.constprop.0 (STB_LOCAL)
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
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e8318)
Location: kernel/stop_machine.c:373
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffff8000101e8318-ffff8000101e83e0: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c0428238)
Location: kernel/stop_machine.c:373
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
c0428238-c0428308: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c000000000258980)
Location: kernel/stop_machine.c:373
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
c000000000258980-c000000000258ab4: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00015d1e8)
Location: kernel/stop_machine.c:373
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffe00015d1e8-ffffffe00015d29e: queue_stop_cpus_work (STB_LOCAL)
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
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116c0b0)
Location: kernel/stop_machine.c:373
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff8116c0b0-ffffffff8116c14c: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115f2b0)
Location: kernel/stop_machine.c:373
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff8115f2b0-ffffffff8115f34c: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81169e80)
Location: kernel/stop_machine.c:373
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff81169e80-ffffffff81169f1c: queue_stop_cpus_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool queue_stop_cpus_work(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg, struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811775c0)
Location: kernel/stop_machine.c:373
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
**Symbols:**

```
ffffffff811775c0-ffffffff81177673: queue_stop_cpus_work (STB_LOCAL)
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
