# Function: <code>stop_two_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811203e0)
Location: kernel/stop_machine.c:255
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff811203e0-ffffffff81120639: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81128340)
Location: kernel/stop_machine.c:263
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81128340-ffffffff81128585: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81131fd0)
Location: kernel/stop_machine.c:279
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81131fd0-ffffffff81132231: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81133590)
Location: kernel/stop_machine.c:279
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81133590-ffffffff811337f1: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81140340)
Location: kernel/stop_machine.c:279
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81140340-ffffffff811405a1: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114ec60)
Location: kernel/stop_machine.c:307
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff8114ec60-ffffffff8114eee2: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115b940)
Location: kernel/stop_machine.c:307
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff8115b940-ffffffff8115bbc2: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81168020)
Location: kernel/stop_machine.c:315
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81168020-ffffffff81168282: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81173ee0)
Location: kernel/stop_machine.c:317
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81173ee0-ffffffff81174142: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81185ec0)
Location: kernel/stop_machine.c:318
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81185ec0-ffffffff8118603d: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81183020)
Location: kernel/stop_machine.c:334
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81183020-ffffffff811831c7: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81184030)
Location: kernel/stop_machine.c:334
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81184030-ffffffff811842e5: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811ac3e0)
Location: kernel/stop_machine.c:334
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff811ac3e0-ffffffff811ac5c3: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811dde00)
Location: kernel/stop_machine.c:334
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff811dde00-ffffffff811de080: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff812238f0)
Location: kernel/stop_machine.c:334
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff812238f0-ffffffff81223b70: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81239f80)
Location: kernel/stop_machine.c:334
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81239f80-ffffffff8123a1c4: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81253c50)
Location: kernel/stop_machine.c:334
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81253c50-ffffffff81253e94: stop_two_cpus (STB_GLOBAL)
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
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e86d0)
Location: kernel/stop_machine.c:317
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffff8000101e86d0-ffff8000101e8964: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c04287b8)
Location: kernel/stop_machine.c:317
Inline: False
```
**Symbols:**

```
c04287b8-c0428a2c: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c0000000002590e0)
Location: kernel/stop_machine.c:317
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
c0000000002590e0-c000000000259450: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00015d6e8)
Location: kernel/stop_machine.c:317
Inline: False
```
**Symbols:**

```
ffffffe00015d6e8-ffffffe00015d940: stop_two_cpus (STB_GLOBAL)
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
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116c500)
Location: kernel/stop_machine.c:317
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff8116c500-ffffffff8116c762: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115f6d0)
Location: kernel/stop_machine.c:317
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff8115f6d0-ffffffff8115f929: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116a2d0)
Location: kernel/stop_machine.c:317
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff8116a2d0-ffffffff8116a532: stop_two_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int stop_two_cpus(unsigned int cpu1, unsigned int cpu2, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81177a20)
Location: kernel/stop_machine.c:317
Inline: False
Direct callers:
  - kernel/sched/core.c:migrate_swap
```
**Symbols:**

```
ffffffff81177a20-ffffffff81177ca8: stop_two_cpus (STB_GLOBAL)
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
