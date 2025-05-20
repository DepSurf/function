# Function: <code>sched_numa_find_closest</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f8a30)
Location: kernel/sched/topology.c:1736
Inline: False
```
**Symbols:**

```
ffffffff810f8a30-ffffffff810f8ab6: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811028e0)
Location: kernel/sched/topology.c:1721
Inline: False
```
**Symbols:**

```
ffffffff811028e0-ffffffff81102966: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101500)
Location: kernel/sched/topology.c:1780
Inline: False
```
**Symbols:**

```
ffffffff81101500-ffffffff81101586: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81103890)
Location: kernel/sched/topology.c:1808
Inline: False
```
**Symbols:**

```
ffffffff81103890-ffffffff8110391c: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81120880)
Location: kernel/sched/topology.c:2002
Inline: False
```
**Symbols:**

```
ffffffff81120880-ffffffff8112093a: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114ab70)
Location: kernel/sched/topology.c:2046
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:housekeeping_any_cpu
```
**Symbols:**

```
ffffffff8114ab70-ffffffff8114ac46: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81179510)
Location: kernel/sched/topology.c:2046
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:housekeeping_any_cpu
```
**Symbols:**

```
ffffffff81179510-ffffffff811795e6: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a100)
Location: kernel/sched/topology.c:2053
Inline: False
```
**Symbols:**

```
ffffffff8118a100-ffffffff8118a1d4: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81198a00)
Location: kernel/sched/topology.c:2079
Inline: False
```
**Symbols:**

```
ffffffff81198a00-ffffffff81198ad4: sched_numa_find_closest (STB_GLOBAL)
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
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015d0a8)
Location: kernel/sched/topology.c:1736
Inline: False
```
**Symbols:**

```
ffff80001015d0a8-ffff80001015d17c: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (0)
Location: kernel/sched/sched.h:1280
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b1b80)
Location: kernel/sched/topology.c:1736
Inline: False
```
**Symbols:**

```
c0000000001b1b80-c0000000001b1cac: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (0)
Location: kernel/sched/sched.h:1280
Inline: True
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
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f1e30)
Location: kernel/sched/topology.c:1736
Inline: False
```
**Symbols:**

```
ffffffff810f1e30-ffffffff810f1eb6: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e1ea0)
Location: kernel/sched/topology.c:1736
Inline: False
```
**Symbols:**

```
ffffffff810e1ea0-ffffffff810e1f26: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810eef60)
Location: kernel/sched/topology.c:1736
Inline: False
```
**Symbols:**

```
ffffffff810eef60-ffffffff810eefe6: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sched_numa_find_closest(const struct cpumask *cpus, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f9fa0)
Location: kernel/sched/topology.c:1736
Inline: False
```
**Symbols:**

```
ffffffff810f9fa0-ffffffff810fa026: sched_numa_find_closest (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
