# Function: <code>stop_one_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81120340)
Location: kernel/stop_machine.c:121
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:migrate_task_to
```
**Symbols:**

```
ffffffff81120340-ffffffff811203da: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811282a0)
Location: kernel/stop_machine.c:121
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff811282a0-ffffffff8112833a: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81131f30)
Location: kernel/stop_machine.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff81131f30-ffffffff81131fcf: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811334e0)
Location: kernel/stop_machine.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff811334e0-ffffffff81133589: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81140290)
Location: kernel/stop_machine.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff81140290-ffffffff81140339: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114ebc0)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff8114ebc0-ffffffff8114ec5f: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115b8a0)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff8115b8a0-ffffffff8115b93f: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81167e60)
Location: kernel/stop_machine.c:122
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff81167e60-ffffffff81167ef9: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81173d20)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff81173d20-ffffffff81173db9: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81185cd0)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff81185cd0-ffffffff81185d99: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81182e30)
Location: kernel/stop_machine.c:139
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
```
**Symbols:**

```
ffffffff81182e30-ffffffff81182efd: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81183e10)
Location: kernel/stop_machine.c:139
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
```
**Symbols:**

```
ffffffff81183e10-ffffffff81183ef3: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811ac1c0)
Location: kernel/stop_machine.c:139
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
```
**Symbols:**

```
ffffffff811ac1c0-ffffffff811ac2a3: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811ddbe0)
Location: kernel/stop_machine.c:139
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
```
**Symbols:**

```
ffffffff811ddbe0-ffffffff811ddcce: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff812236a0)
Location: kernel/stop_machine.c:139
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
```
**Symbols:**

```
ffffffff812236a0-ffffffff8122378e: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81239d40)
Location: kernel/stop_machine.c:139
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
```
**Symbols:**

```
ffffffff81239d40-ffffffff81239e1c: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81253a10)
Location: kernel/stop_machine.c:139
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
```
**Symbols:**

```
ffffffff81253a10-ffffffff81253aec: stop_one_cpu (STB_GLOBAL)
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e8488)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffff8000101e8488-ffff8000101e8534: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c042857c)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
c042857c-c0428628: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c000000000258dd0)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
c000000000258dd0-c000000000258ea0: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00015d4fe)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffe00015d4fe-ffffffe00015d578: stop_one_cpu (STB_GLOBAL)
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
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116c340)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff8116c340-ffffffff8116c3d9: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115f530)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff8115f530-ffffffff8115f5c9: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116a110)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff8116a110-ffffffff8116a1a9: stop_one_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int stop_one_cpu(unsigned int cpu, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81177860)
Location: kernel/stop_machine.c:123
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff81177860-ffffffff811778f4: stop_one_cpu (STB_GLOBAL)
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
