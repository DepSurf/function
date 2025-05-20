# Function: <code>__stop_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81120100)
Location: kernel/stop_machine.c:339
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_cpus
  - kernel/stop_machine.c:try_stop_cpus
```
**Symbols:**

```
ffffffff81120100-ffffffff8112018a: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81128080)
Location: kernel/stop_machine.c:349
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff81128080-ffffffff8112810b: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81131ea0)
Location: kernel/stop_machine.c:364
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff81131ea0-ffffffff81131f2c: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81133450)
Location: kernel/stop_machine.c:364
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff81133450-ffffffff811334dc: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81140200)
Location: kernel/stop_machine.c:364
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff81140200-ffffffff8114028c: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114eb30)
Location: kernel/stop_machine.c:392
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff8114eb30-ffffffff8114ebbc: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115b810)
Location: kernel/stop_machine.c:392
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff8115b810-ffffffff8115b89c: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81167c70)
Location: kernel/stop_machine.c:400
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff81167c70-ffffffff81167cf4: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81173b30)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff81173b30-ffffffff81173bb4: __stop_cpus (STB_LOCAL)
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
In kernel/stop_machine.c (ffffffff811861ac)
Location: kernel/stop_machine.c:405
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
In kernel/stop_machine.c (ffffffff8118333c)
Location: kernel/stop_machine.c:422
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
In kernel/stop_machine.c (ffffffff8118445f)
Location: kernel/stop_machine.c:423
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
In kernel/stop_machine.c (ffffffff811ac78d)
Location: kernel/stop_machine.c:423
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
In kernel/stop_machine.c (ffffffff811dda84)
Location: kernel/stop_machine.c:423
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
In kernel/stop_machine.c (ffffffff81223504)
Location: kernel/stop_machine.c:423
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
In kernel/stop_machine.c (ffffffff81239a54)
Location: kernel/stop_machine.c:423
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
In kernel/stop_machine.c (ffffffff81253724)
Location: kernel/stop_machine.c:423
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
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e83e0)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffff8000101e83e0-ffff8000101e8484: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c04284d8)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
c04284d8-c042857c: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c000000000258ac0)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
c000000000258ac0-c000000000258b80: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00015d48e)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffe00015d48e-ffffffe00015d4fe: __stop_cpus (STB_LOCAL)
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
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116c150)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff8116c150-ffffffff8116c1d4: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115f350)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff8115f350-ffffffff8115f3d4: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81169f20)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff81169f20-ffffffff81169fa4: __stop_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81177680)
Location: kernel/stop_machine.c:404
Inline: False
Direct callers:
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_cpus
```
**Symbols:**

```
ffffffff81177680-ffffffff81177704: __stop_cpus (STB_LOCAL)
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
