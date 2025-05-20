# Function: <code>try_stop_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811207e0)
Location: kernel/stop_machine.c:407
Inline: False
```
**Symbols:**

```
ffffffff811207e0-ffffffff81120833: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81128730)
Location: kernel/stop_machine.c:418
Inline: False
```
**Symbols:**

```
ffffffff81128730-ffffffff81128785: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811323e0)
Location: kernel/stop_machine.c:433
Inline: False
```
**Symbols:**

```
ffffffff811323e0-ffffffff81132435: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81133890)
Location: kernel/stop_machine.c:433
Inline: False
```
**Symbols:**

```
ffffffff81133890-ffffffff811338e3: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81140640)
Location: kernel/stop_machine.c:433
Inline: False
```
**Symbols:**

```
ffffffff81140640-ffffffff81140693: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114ef80)
Location: kernel/stop_machine.c:461
Inline: False
```
**Symbols:**

```
ffffffff8114ef80-ffffffff8114efd3: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115bc60)
Location: kernel/stop_machine.c:461
Inline: False
```
**Symbols:**

```
ffffffff8115bc60-ffffffff8115bcb3: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81168320)
Location: kernel/stop_machine.c:469
Inline: False
```
**Symbols:**

```
ffffffff81168320-ffffffff81168378: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811741e0)
Location: kernel/stop_machine.c:473
Inline: False
```
**Symbols:**

```
ffffffff811741e0-ffffffff81174238: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e8a28)
Location: kernel/stop_machine.c:473
Inline: False
```
**Symbols:**

```
ffff8000101e8a28-ffff8000101e8aa0: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c0428ab8)
Location: kernel/stop_machine.c:473
Inline: False
```
**Symbols:**

```
c0428ab8-c0428b18: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c000000000259510)
Location: kernel/stop_machine.c:473
Inline: False
```
**Symbols:**

```
c000000000259510-c0000000002595b8: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffe00015d9f0)
Location: kernel/stop_machine.c:473
Inline: False
```
**Symbols:**

```
ffffffe00015d9f0-ffffffe00015da54: try_stop_cpus (STB_GLOBAL)
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
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116c800)
Location: kernel/stop_machine.c:473
Inline: False
```
**Symbols:**

```
ffffffff8116c800-ffffffff8116c858: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115f9c0)
Location: kernel/stop_machine.c:473
Inline: False
```
**Symbols:**

```
ffffffff8115f9c0-ffffffff8115fa18: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116a5d0)
Location: kernel/stop_machine.c:473
Inline: False
```
**Symbols:**

```
ffffffff8116a5d0-ffffffff8116a628: try_stop_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int try_stop_cpus(const struct cpumask *cpumask, cpu_stop_fn_t fn, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81177d40)
Location: kernel/stop_machine.c:473
Inline: False
```
**Symbols:**

```
ffffffff81177d40-ffffffff81177d98: try_stop_cpus (STB_GLOBAL)
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
