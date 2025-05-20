# Function: <code>alloc_sched_domains</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afc70)
Location: kernel/sched/core.c:7057
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810afc70-ffffffff810afc8b: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2470)
Location: kernel/sched/core.c:6992
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810b2470-ffffffff810b248b: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b8a10)
Location: kernel/sched/core.c:7113
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810b8a10-ffffffff810b8a80: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cd370)
Location: kernel/sched/topology.c:1737
Inline: False
Direct callers:
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810cd370-ffffffff810cd3d6: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d4b80)
Location: kernel/sched/topology.c:1752
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810d4b80-ffffffff810d4be6: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dc760)
Location: kernel/sched/topology.c:1748
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810dc760-ffffffff810dc7c6: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e63c0)
Location: kernel/sched/topology.c:2023
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810e63c0-ffffffff810e6426: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ecfe0)
Location: kernel/sched/topology.c:2048
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810ecfe0-ffffffff810ed049: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f8b10)
Location: kernel/sched/topology.c:2111
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810f8b10-ffffffff810f8b79: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81102980)
Location: kernel/sched/topology.c:2096
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff81102980-ffffffff81102a05: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811015a0)
Location: kernel/sched/topology.c:2154
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff811015a0-ffffffff81101625: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81103930)
Location: kernel/sched/topology.c:2182
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff81103930-ffffffff811039b5: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81120950)
Location: kernel/sched/topology.c:2311
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff81120950-ffffffff811209d5: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114ad20)
Location: kernel/sched/topology.c:2418
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff8114ad20-ffffffff8114adab: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811796f0)
Location: kernel/sched/topology.c:2425
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff811796f0-ffffffff81179782: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a2e0)
Location: kernel/sched/topology.c:2525
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff8118a2e0-ffffffff8118a372: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81198be0)
Location: kernel/sched/topology.c:2570
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff81198be0-ffffffff81198c72: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015d5f0)
Location: kernel/sched/topology.c:2111
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
Direct callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffff80001015d1a0-ffff80001015d1d0: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a96d0)
Location: kernel/sched/topology.c:2111
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
Direct callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
c03a92a8-c03a92dc: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b2224)
Location: kernel/sched/topology.c:2111
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
Direct callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
c0000000001b1cc0-c0000000001b1cfc: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe000101df6)
Location: kernel/sched/topology.c:2111
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
Direct callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffe000101a30-ffffffe000101a66: alloc_sched_domains (STB_GLOBAL)
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
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f1f10)
Location: kernel/sched/topology.c:2111
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810f1f10-ffffffff810f1f79: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e1f80)
Location: kernel/sched/topology.c:2111
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810e1f80-ffffffff810e1fe9: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ef040)
Location: kernel/sched/topology.c:2111
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810ef040-ffffffff810ef0a9: alloc_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
cpumask_var_t *alloc_sched_domains(unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810fa080)
Location: kernel/sched/topology.c:2111
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
**Symbols:**

```
ffffffff810fa080-ffffffff810fa0e9: alloc_sched_domains (STB_GLOBAL)
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
