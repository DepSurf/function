# Function: <code>stop_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81120680)
Location: kernel/stop_machine.c:378
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff81120680-ffffffff811206c8: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811285d0)
Location: kernel/stop_machine.c:389
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff811285d0-ffffffff81128618: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81132280)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine
```
**Symbols:**

```
ffffffff81132280-ffffffff811322c8: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81133840)
Location: kernel/stop_machine.c:404
Inline: False
```
**Symbols:**

```
ffffffff81133840-ffffffff81133888: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811405f0)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff811405f0-ffffffff81140638: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114ef30)
Location: kernel/stop_machine.c:432
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff8114ef30-ffffffff8114ef78: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115bc10)
Location: kernel/stop_machine.c:432
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff8115bc10-ffffffff8115bc58: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811682d0)
Location: kernel/stop_machine.c:440
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffffffff811682d0-ffffffff8116831c: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81174190)
Location: kernel/stop_machine.c:444
Inline: False
```
**Symbols:**

```
ffffffff81174190-ffffffff811741dc: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811861a7)
Location: kernel/stop_machine.c:445
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81183337)
Location: kernel/stop_machine.c:462
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8118445a)
Location: kernel/stop_machine.c:463
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811ac788)
Location: kernel/stop_machine.c:463
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811dda7f)
Location: kernel/stop_machine.c:463
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff812234ff)
Location: kernel/stop_machine.c:463
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81239a4f)
Location: kernel/stop_machine.c:463
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8125371f)
Location: kernel/stop_machine.c:463
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
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
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e89b8)
Location: kernel/stop_machine.c:444
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
**Symbols:**

```
ffff8000101e89b8-ffff8000101e8a24: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c0428a64)
Location: kernel/stop_machine.c:444
Inline: False
```
**Symbols:**

```
c0428a64-c0428ab8: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c000000000259490)
Location: kernel/stop_machine.c:444
Inline: False
```
**Symbols:**

```
c000000000259490-c000000000259510: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00015d992)
Location: kernel/stop_machine.c:444
Inline: False
```
**Symbols:**

```
ffffffe00015d992-ffffffe00015d9f0: stop_cpus (STB_GLOBAL)
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
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116c7b0)
Location: kernel/stop_machine.c:444
Inline: False
```
**Symbols:**

```
ffffffff8116c7b0-ffffffff8116c7fc: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115f970)
Location: kernel/stop_machine.c:444
Inline: False
```
**Symbols:**

```
ffffffff8115f970-ffffffff8115f9bc: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116a580)
Location: kernel/stop_machine.c:444
Inline: False
```
**Symbols:**

```
ffffffff8116a580-ffffffff8116a5cc: stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81177cf0)
Location: kernel/stop_machine.c:444
Inline: False
```
**Symbols:**

```
ffffffff81177cf0-ffffffff81177d3c: stop_cpus (STB_GLOBAL)
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
