# Function: <code>build_sched_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sched_domain *build_sched_domain(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain_attr *attr, struct sched_domain *child, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aee30)
Location: kernel/sched/core.c:6930
Inline: False
Direct callers:
  - kernel/sched/core.c:build_sched_domains
```
**Symbols:**

```
ffffffff810aee30-ffffffff810af13a: build_sched_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sched_domain *build_sched_domain(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain_attr *attr, struct sched_domain *child, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b1640)
Location: kernel/sched/core.c:6865
Inline: False
Direct callers:
  - kernel/sched/core.c:build_sched_domains
```
**Symbols:**

```
ffffffff810b1640-ffffffff810b193c: build_sched_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sched_domain *build_sched_domain(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain_attr *attr, struct sched_domain *child, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7910)
Location: kernel/sched/core.c:6978
Inline: False
Direct callers:
  - kernel/sched/core.c:build_sched_domains
```
**Symbols:**

```
ffffffff810b7910-ffffffff810b7c39: build_sched_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sched_domain *build_sched_domain(struct sched_domain_topology_level *tl, const struct cpumask *cpu_map, struct sched_domain_attr *attr, struct sched_domain *child, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cc240)
Location: kernel/sched/topology.c:1598
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810cc240-ffffffff810cc560: build_sched_domain (STB_GLOBAL)
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
Location: kernel/sched/topology.c:1613
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
Location: kernel/sched/topology.c:1608
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
Location: kernel/sched/topology.c:1809
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
Location: kernel/sched/topology.c:1834
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
Location: kernel/sched/topology.c:1855
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff81101f07)
Location: kernel/sched/topology.c:1840
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff81100afc)
Location: kernel/sched/topology.c:1899
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff81102c4a)
Location: kernel/sched/topology.c:1927
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff8111f7f3)
Location: kernel/sched/topology.c:2121
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/build_utility.c (ffffffff811497f6)
Location: kernel/sched/topology.c:2177
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
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
In kernel/sched/build_utility.c (ffffffff8117819b)
Location: kernel/sched/topology.c:2177
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
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
In kernel/sched/build_utility.c (ffffffff81188e42)
Location: kernel/sched/topology.c:2277
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
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
In kernel/sched/build_utility.c (ffffffff81197737)
Location: kernel/sched/topology.c:2312
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
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
Location: kernel/sched/topology.c:1855
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
Location: kernel/sched/topology.c:1855
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
Location: kernel/sched/topology.c:1855
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
Location: kernel/sched/topology.c:1855
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
Location: kernel/sched/topology.c:1855
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
Location: kernel/sched/topology.c:1855
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
Location: kernel/sched/topology.c:1855
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
Location: kernel/sched/topology.c:1855
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
