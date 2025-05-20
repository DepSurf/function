# Function: <code>build_sched_domains</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af140)
Location: kernel/sched/core.c:6968
Inline: False
Direct callers:
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810af140-ffffffff810afc5b: build_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b1940)
Location: kernel/sched/core.c:6903
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810b1940-ffffffff810b245b: build_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7c40)
Location: kernel/sched/core.c:7012
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810b7c40-ffffffff810b89ba: build_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cc560)
Location: kernel/sched/topology.c:1633
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810cc560-ffffffff810cd31a: build_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d3250)
Location: kernel/sched/topology.c:1648
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810d3250-ffffffff810d4276: build_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1643
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810daf10-ffffffff810dbe84: build_sched_domains (STB_LOCAL)
ffffffff810dcf0d-ffffffff810dcf6f: build_sched_domains.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1903
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810e4ac0-ffffffff810e5ab4: build_sched_domains (STB_LOCAL)
ffffffff810e6b6d-ffffffff810e6bd5: build_sched_domains.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1928
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810eba80-ffffffff810ec701: build_sched_domains (STB_LOCAL)
ffffffff810ed7b0-ffffffff810ed866: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1985
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810f7430-ffffffff810f81a4: build_sched_domains (STB_LOCAL)
ffffffff810f9398-ffffffff810f9407: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1970
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81101cf0-ffffffff811021b8: build_sched_domains (STB_LOCAL)
ffffffff8110346f-ffffffff811034f2: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:2029
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff811008e0-ffffffff81100dc2: build_sched_domains (STB_LOCAL)
ffffffff81bdcdde-ffffffff81bdce6d: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:2057
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff81102a20-ffffffff8110318a: build_sched_domains (STB_LOCAL)
ffffffff81bcef59-ffffffff81bcefd9: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:2192
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff8111f610-ffffffff8111ff6b: build_sched_domains (STB_LOCAL)
ffffffff81ca7647-ffffffff81ca76dc: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:2248
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
```
**Symbols:**

```
ffffffff81149650-ffffffff8114a088: build_sched_domains (STB_LOCAL)
ffffffff81e593ea-ffffffff81e5947b: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:2248
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
```
**Symbols:**

```
ffffffff81177fc0-ffffffff811789d1: build_sched_domains (STB_LOCAL)
ffffffff82058134-ffffffff82058148: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:2348
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
```
**Symbols:**

```
ffffffff81188c60-ffffffff8118967c: build_sched_domains (STB_LOCAL)
ffffffff820d6a2b-ffffffff820d6a3f: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:2383
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
```
**Symbols:**

```
ffffffff81197530-ffffffff81197f75: build_sched_domains (STB_LOCAL)
ffffffff821b1cc1-ffffffff821b1cd5: build_sched_domains.cold (STB_LOCAL)
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
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015b790)
Location: kernel/sched/topology.c:1985
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffff80001015b790-ffff80001015c6d0: build_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a81d8)
Location: kernel/sched/topology.c:1985
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
c03a81d8-c03a9148: build_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001afe00)
Location: kernel/sched/topology.c:1985
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
c0000000001afe00-c0000000001b0f2c: build_sched_domains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe000100a2e)
Location: kernel/sched/topology.c:1985
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffe000100a2e-ffffffe0001018fc: build_sched_domains (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1985
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810f0830-ffffffff810f15a4: build_sched_domains (STB_LOCAL)
ffffffff810f2798-ffffffff810f2807: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1985
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810e08a0-ffffffff810e1614: build_sched_domains (STB_LOCAL)
ffffffff810e2808-ffffffff810e2877: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1985
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810ed960-ffffffff810ee6d4: build_sched_domains (STB_LOCAL)
ffffffff810ef8c8-ffffffff810ef937: build_sched_domains.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int build_sched_domains(const struct cpumask *cpu_map, struct sched_domain_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1985
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
```
**Symbols:**

```
ffffffff810f89a0-ffffffff810f971e: build_sched_domains (STB_LOCAL)
ffffffff810fa918-ffffffff810fa987: build_sched_domains.cold (STB_LOCAL)
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
