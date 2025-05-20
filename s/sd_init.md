# Function: <code>sd_init</code>

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
In kernel/sched/core.c (ffffffff810aee55)
Location: kernel/sched/core.c:6427
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domain
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
In kernel/sched/core.c (ffffffff810b1665)
Location: kernel/sched/core.c:6393
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domain
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
In kernel/sched/core.c (ffffffff810b7916)
Location: kernel/sched/core.c:6463
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domain
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
In kernel/sched/topology.c (ffffffff810cc246)
Location: kernel/sched/topology.c:1083
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domain
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
In kernel/sched/topology.c (ffffffff810d34fd)
Location: kernel/sched/topology.c:1085
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff810db1bd)
Location: kernel/sched/topology.c:1080
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff810e4dcf)
Location: kernel/sched/topology.c:1279
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ebd73)
Location: kernel/sched/topology.c:1314
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff810f7931)
Location: kernel/sched/topology.c:1315
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sched_domain *sd_init(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain *child, int dflags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81100ca0)
Location: kernel/sched/topology.c:1310
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81100ca0-ffffffff81100ed1: sd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sched_domain *sd_init(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain *child, int dflags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ff7f0)
Location: kernel/sched/topology.c:1369
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810ff7f0-ffffffff810ffa21: sd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sched_domain *sd_init(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain *child, int dflags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101a90)
Location: kernel/sched/topology.c:1400
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81101a90-ffffffff81101cc0: sd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sched_domain *sd_init(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain *child, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (0)
Location: kernel/sched/topology.c:1527
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff8111e220-ffffffff8111e601: sd_init (STB_LOCAL)
ffffffff81ca741d-ffffffff81ca744c: sd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sched_domain *sd_init(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain *child, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1540
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff81142ad0-ffffffff81142e4c: sd_init (STB_LOCAL)
ffffffff81e57d28-ffffffff81e57d58: sd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sched_domain *sd_init(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain *child, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1540
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff8116f930-ffffffff8116fcac: sd_init (STB_LOCAL)
ffffffff82057e55-ffffffff82057e85: sd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sched_domain *sd_init(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain *child, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1547
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff8117f790-ffffffff8117fb0a: sd_init (STB_LOCAL)
ffffffff820d6601-ffffffff820d6631: sd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sched_domain *sd_init(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain *child, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1573
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff8118d190-ffffffff8118d50a: sd_init (STB_LOCAL)
ffffffff821b179a-ffffffff821b17ca: sd_init.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015bce8)
Location: kernel/sched/topology.c:1315
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (c03a8720)
Location: kernel/sched/topology.c:1315
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b0480)
Location: kernel/sched/topology.c:1315
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffe000100c24)
Location: kernel/sched/topology.c:1315
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff810f0d31)
Location: kernel/sched/topology.c:1315
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff810e0da1)
Location: kernel/sched/topology.c:1315
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff810ede61)
Location: kernel/sched/topology.c:1315
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff810f8ea1)
Location: kernel/sched/topology.c:1315
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int dflags</code>
</li>
<li>
<b>Param reordered. </b>
<code>tl, cpu_map, child, dflags, cpu</code> ➡️ <code>tl, cpu_map, child, cpu</code>
</li>
</ul>
</details>
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
