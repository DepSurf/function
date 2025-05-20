# Function: <code>partition_sched_domains_locked</code>

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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f8c40)
Location: kernel/sched/topology.c:2221
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810f8c40-ffffffff810f8f8d: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:2206
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81103514-ffffffff81103544: partition_sched_domains_locked.cold (STB_LOCAL)
ffffffff81102b10-ffffffff81102fbc: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:2264
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81bdce8f-ffffffff81bdcebf: partition_sched_domains_locked.cold (STB_LOCAL)
ffffffff81101730-ffffffff81101be5: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:2291
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81bceffb-ffffffff81bcf02b: partition_sched_domains_locked.cold (STB_LOCAL)
ffffffff81103ab0-ffffffff81103f5a: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:2421
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81ca7728-ffffffff81ca779b: partition_sched_domains_locked.cold (STB_LOCAL)
ffffffff81120ad0-ffffffff8112101b: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:2528
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81e594df-ffffffff81e5954c: partition_sched_domains_locked.cold (STB_LOCAL)
ffffffff8114aed0-ffffffff8114b495: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:2535
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8205818a-ffffffff820581c7: partition_sched_domains_locked.cold (STB_LOCAL)
ffffffff811798f0-ffffffff81179eee: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:2635
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff820d6a6c-ffffffff820d6abf: partition_sched_domains_locked.cold (STB_LOCAL)
ffffffff8118a3f0-ffffffff8118aa47: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:2683
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff821b1d02-ffffffff821b1d55: partition_sched_domains_locked.cold (STB_LOCAL)
ffffffff81198cf0-ffffffff8119935d: partition_sched_domains_locked (STB_GLOBAL)
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015d2c0)
Location: kernel/sched/topology.c:2221
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffff80001015d2c0-ffff80001015d690: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a9390)
Location: kernel/sched/topology.c:2221
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
```
**Symbols:**

```
c03a9390-c03a97fc: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b1e70)
Location: kernel/sched/topology.c:2221
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
c0000000001b1e70-c0000000001b2318: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe000101b4e)
Location: kernel/sched/topology.c:2221
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
```
**Symbols:**

```
ffffffe000101b4e-ffffffe000101ee2: partition_sched_domains_locked (STB_GLOBAL)
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
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f2040)
Location: kernel/sched/topology.c:2221
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810f2040-ffffffff810f238d: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e20b0)
Location: kernel/sched/topology.c:2221
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810e20b0-ffffffff810e23fd: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ef170)
Location: kernel/sched/topology.c:2221
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810ef170-ffffffff810ef4bd: partition_sched_domains_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void partition_sched_domains_locked(int ndoms_new, cpumask_var_t *doms_new, struct sched_domain_attr *dattr_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810fa1b0)
Location: kernel/sched/topology.c:2221
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff810fa1b0-ffffffff810fa507: partition_sched_domains_locked (STB_GLOBAL)
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
