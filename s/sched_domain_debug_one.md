# Function: <code>sched_domain_debug_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a83de)
Location: kernel/sched/core.c:5662
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aaf87)
Location: kernel/sched/core.c:5623
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b121a)
Location: kernel/sched/core.c:5657
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cb4ef)
Location: kernel/sched/topology.c:32
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d2c9e)
Location: kernel/sched/topology.c:32
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dcc15)
Location: kernel/sched/topology.c:28
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e6875)
Location: kernel/sched/topology.c:28
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sched_domain_debug_one(struct sched_domain *sd, int cpu, int level, struct cpumask *groupmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ed3e0)
Location: kernel/sched/topology.c:28
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810ed3e0-ffffffff810ed6cc: sched_domain_debug_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f9098)
Location: kernel/sched/topology.c:28
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_domain_debug_one(struct sched_domain *sd, int cpu, int level, struct cpumask *groupmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81103006)
Location: kernel/sched/topology.c:28
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81103006-ffffffff811032bf: sched_domain_debug_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sched_domain_debug_one(struct sched_domain *sd, int cpu, int level, struct cpumask *groupmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81bdc871)
Location: kernel/sched/topology.c:34
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81bdc871-ffffffff81bdcc14: sched_domain_debug_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sched_domain_debug_one(struct sched_domain *sd, int cpu, int level, struct cpumask *groupmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81bcea71)
Location: kernel/sched/topology.c:34
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81bcea71-ffffffff81bcee15: sched_domain_debug_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sched_domain_debug_one(struct sched_domain *sd, int cpu, int level, struct cpumask *groupmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81ca702c)
Location: kernel/sched/topology.c:34
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81ca702c-ffffffff81ca741d: sched_domain_debug_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sched_domain_debug_one(struct sched_domain *sd, int cpu, int level, struct cpumask *groupmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81e578fe)
Location: kernel/sched/topology.c:33
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81e578fe-ffffffff81e57ce7: sched_domain_debug_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sched_domain_debug_one(struct sched_domain *sd, int cpu, int level, struct cpumask *groupmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81170770)
Location: kernel/sched/topology.c:33
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81170770-ffffffff81170c86: sched_domain_debug_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sched_domain_debug_one(struct sched_domain *sd, int cpu, int level, struct cpumask *groupmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81181190)
Location: kernel/sched/topology.c:35
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81181190-ffffffff811816a6: sched_domain_debug_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sched_domain_debug_one(struct sched_domain *sd, int cpu, int level, struct cpumask *groupmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118f500)
Location: kernel/sched/topology.c:35
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff8118f500-ffffffff8118fa16: sched_domain_debug_one (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffff80001015d9ec)
Location: kernel/sched/topology.c:28
Inline: True
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffff80001015d9ec-ffff80001015dcfc: sched_domain_debug_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (c03a9848)
Location: kernel/sched/topology.c:28
Inline: True
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
c03a9848-c03a9b80: sched_domain_debug_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (c0000000001b2520)
Location: kernel/sched/topology.c:28
Inline: True
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
c0000000001b2520-c0000000001b2934: sched_domain_debug_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffe000101f3c)
Location: kernel/sched/topology.c:28
Inline: True
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffe000101f3c-ffffffe000102254: sched_domain_debug_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f2498)
Location: kernel/sched/topology.c:28
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e2508)
Location: kernel/sched/topology.c:28
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ef5c8)
Location: kernel/sched/topology.c:28
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810fa618)
Location: kernel/sched/topology.c:28
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
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
