# Function: <code>init_numa_topology_type</code>

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
In kernel/sched/core.c (ffffffff81f7ddcc)
Location: kernel/sched/core.c:6611
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
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
In kernel/sched/core.c (ffffffff81fa6c82)
Location: kernel/sched/core.c:6577
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
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
In kernel/sched/core.c (ffffffff81fe2803)
Location: kernel/sched/core.c:6674
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
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
In kernel/sched/topology.c (ffffffff810cbcfb)
Location: kernel/sched/topology.c:1294
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
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
In kernel/sched/topology.c (ffffffff810d4522)
Location: kernel/sched/topology.c:1297
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
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
In kernel/sched/topology.c (ffffffff810dc44b)
Location: kernel/sched/topology.c:1292
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
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
In kernel/sched/topology.c (ffffffff810e6078)
Location: kernel/sched/topology.c:1496
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
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
In kernel/sched/topology.c (ffffffff810ecc88)
Location: kernel/sched/topology.c:1521
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
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
In kernel/sched/topology.c (ffffffff810f8728)
Location: kernel/sched/topology.c:1522
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_numa_topology_type();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81100520)
Location: kernel/sched/topology.c:1507
Inline: False
Direct callers:
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff81100520-ffffffff811006a3: init_numa_topology_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_numa_topology_type();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ff070)
Location: kernel/sched/topology.c:1566
Inline: False
Direct callers:
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff810ff070-ffffffff810ff1f3: init_numa_topology_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_numa_topology_type();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811015a0)
Location: kernel/sched/topology.c:1597
Inline: False
Direct callers:
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff811015a0-ffffffff81101702: init_numa_topology_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_numa_topology_type();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111da00)
Location: kernel/sched/topology.c:1728
Inline: False
Direct callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
```
**Symbols:**

```
ffffffff8111da00-ffffffff8111db62: init_numa_topology_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void init_numa_topology_type(int offline_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:1767
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_init_numa
```
**Symbols:**

```
ffffffff81141000-ffffffff81141189: init_numa_topology_type (STB_LOCAL)
ffffffff81e578cb-ffffffff81e578de: init_numa_topology_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_numa_topology_type(int offline_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81168430)
Location: kernel/sched/topology.c:1767
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_init_numa
```
**Symbols:**

```
ffffffff81168430-ffffffff811685a1: init_numa_topology_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_numa_topology_type(int offline_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81178a80)
Location: kernel/sched/topology.c:1774
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_init_numa
```
**Symbols:**

```
ffffffff81178a80-ffffffff81178bf1: init_numa_topology_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_numa_topology_type(int offline_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811867d0)
Location: kernel/sched/topology.c:1800
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_init_numa
```
**Symbols:**

```
ffffffff811867d0-ffffffff81186941: init_numa_topology_type (STB_LOCAL)
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
In kernel/sched/topology.c (ffff80001015cd60)
Location: kernel/sched/topology.c:1522
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b1738)
Location: kernel/sched/topology.c:1522
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/sched/topology.c (ffffffff810f1b28)
Location: kernel/sched/topology.c:1522
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
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
In kernel/sched/topology.c (ffffffff810e1b98)
Location: kernel/sched/topology.c:1522
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
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
In kernel/sched/topology.c (ffffffff810eec58)
Location: kernel/sched/topology.c:1522
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
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
In kernel/sched/topology.c (ffffffff810f9c98)
Location: kernel/sched/topology.c:1522
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int offline_node</code>
</li>
</ul>
</details>
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
