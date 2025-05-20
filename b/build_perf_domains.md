# Function: <code>build_perf_domains</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool build_perf_domains(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:333
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff81100ee0-ffffffff81101128: build_perf_domains (STB_LOCAL)
ffffffff81103344-ffffffff8110340f: build_perf_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool build_perf_domains(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:352
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff810ffa30-ffffffff810ffc83: build_perf_domains (STB_LOCAL)
ffffffff81bdcc99-ffffffff81bdcd7e: build_perf_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool build_perf_domains(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:352
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff81101e70-ffffffff811020bf: build_perf_domains (STB_LOCAL)
ffffffff81bcee15-ffffffff81bceef9: build_perf_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool build_perf_domains(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:352
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff8111e7d0-ffffffff8111ea95: build_perf_domains (STB_LOCAL)
ffffffff81ca744c-ffffffff81ca7588: build_perf_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool build_perf_domains(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:372
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff81142e50-ffffffff81143139: build_perf_domains (STB_LOCAL)
ffffffff81e57d58-ffffffff81e57e94: build_perf_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool build_perf_domains(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:372
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff811703a0-ffffffff8117075f: build_perf_domains (STB_LOCAL)
ffffffff82057eb7-ffffffff82057f0a: build_perf_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool build_perf_domains(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:374
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff8117ffb0-ffffffff8118036f: build_perf_domains (STB_LOCAL)
ffffffff820d6631-ffffffff820d6684: build_perf_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool build_perf_domains(const struct cpumask *cpu_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:426
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffff8118eef0-ffffffff8118f183: build_perf_domains (STB_LOCAL)
ffffffff821b1892-ffffffff821b18bb: build_perf_domains.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
