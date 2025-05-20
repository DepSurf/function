# Function: <code>partition_sched_domains</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afca0)
Location: kernel/sched/core.c:7159
Inline: False
Direct callers:
  - kernel/cpuset.c:rebuild_sched_domains_locked
  - kernel/cpuset.c:cpuset_update_active_cpus
```
**Symbols:**

```
ffffffff810afca0-ffffffff810b0046: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b24a0)
Location: kernel/sched/core.c:7094
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/cpuset.c:cpuset_update_active_cpus
  - kernel/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810b24a0-ffffffff810b281f: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b8a80)
Location: kernel/sched/core.c:7215
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/cpuset.c:cpuset_update_active_cpus
  - kernel/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810b8a80-ffffffff810b8e0f: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cd490)
Location: kernel/sched/topology.c:1843
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810cd490-ffffffff810cd775: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d4ca0)
Location: kernel/sched/topology.c:1858
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810d4ca0-ffffffff810d4fca: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dc880)
Location: kernel/sched/topology.c:1855
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810dc880-ffffffff810dcb50: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e64e0)
Location: kernel/sched/topology.c:2130
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810e64e0-ffffffff810e67b0: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ed110)
Location: kernel/sched/topology.c:2154
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810ed110-ffffffff810ed3e0: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f8f90)
Location: kernel/sched/topology.c:2327
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810f8f90-ffffffff810f8fd6: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81102fc0)
Location: kernel/sched/topology.c:2312
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81102fc0-ffffffff81103006: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101bf0)
Location: kernel/sched/topology.c:2370
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81101bf0-ffffffff81101c36: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81103f60)
Location: kernel/sched/topology.c:2394
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81103f60-ffffffff81103fa6: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81121020)
Location: kernel/sched/topology.c:2527
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81121020-ffffffff81121066: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114b4a0)
Location: kernel/sched/topology.c:2634
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff8114b4a0-ffffffff8114b4ec: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81179f00)
Location: kernel/sched/topology.c:2641
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81179f00-ffffffff81179f4c: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118aa60)
Location: kernel/sched/topology.c:2741
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff8118aa60-ffffffff8118aaac: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81199370)
Location: kernel/sched/topology.c:2789
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff81199370-ffffffff811993bc: partition_sched_domains (STB_GLOBAL)
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
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015d690)
Location: kernel/sched/topology.c:2327
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffff80001015d690-ffff80001015d6f0: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a97fc)
Location: kernel/sched/topology.c:2327
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
c03a97fc-c03a9848: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b2320)
Location: kernel/sched/topology.c:2327
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
c0000000001b2320-c0000000001b2398: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe000101ee2)
Location: kernel/sched/topology.c:2327
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffe000101ee2-ffffffe000101f3c: partition_sched_domains (STB_GLOBAL)
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
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f2390)
Location: kernel/sched/topology.c:2327
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810f2390-ffffffff810f23d6: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e2400)
Location: kernel/sched/topology.c:2327
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810e2400-ffffffff810e2446: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ef4c0)
Location: kernel/sched/topology.c:2327
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810ef4c0-ffffffff810ef506: partition_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void partition_sched_domains(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810fa510)
Location: kernel/sched/topology.c:2327
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
**Symbols:**

```
ffffffff810fa510-ffffffff810fa556: partition_sched_domains (STB_GLOBAL)
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
