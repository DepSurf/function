# Function: <code>build_group_from_child_sched_domain</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cca28)
Location: kernel/sched/topology.c:656
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/topology.c (ffffffff810d3ae0)
Location: kernel/sched/topology.c:657
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
In kernel/sched/topology.c (ffffffff810db791)
Location: kernel/sched/topology.c:649
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
In kernel/sched/topology.c (ffffffff810e538c)
Location: kernel/sched/topology.c:848
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
In kernel/sched/topology.c (ffffffff810eb329)
Location: kernel/sched/topology.c:877
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
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
In kernel/sched/topology.c (ffffffff810f6cc9)
Location: kernel/sched/topology.c:877
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sched_group *build_group_from_child_sched_domain(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101330)
Location: kernel/sched/topology.c:875
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
```
**Symbols:**

```
ffffffff81101330-ffffffff811013c3: build_group_from_child_sched_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sched_group *build_group_from_child_sched_domain(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ffe90)
Location: kernel/sched/topology.c:936
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
```
**Symbols:**

```
ffffffff810ffe90-ffffffff810fff23: build_group_from_child_sched_domain (STB_LOCAL)
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
In kernel/sched/topology.c (ffffffff81102316)
Location: kernel/sched/topology.c:907
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
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
In kernel/sched/topology.c (ffffffff8111edd6)
Location: kernel/sched/topology.c:919
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
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
In kernel/sched/build_utility.c (ffffffff81144567)
Location: kernel/sched/topology.c:935
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_overlap_sched_groups
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
In kernel/sched/build_utility.c (ffffffff811713cc)
Location: kernel/sched/topology.c:935
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_overlap_sched_groups
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
In kernel/sched/build_utility.c (ffffffff81181bc9)
Location: kernel/sched/topology.c:942
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_overlap_sched_groups
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
In kernel/sched/build_utility.c (ffffffff81190499)
Location: kernel/sched/topology.c:957
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_overlap_sched_groups
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
In kernel/sched/topology.c (ffff80001015aeec)
Location: kernel/sched/topology.c:877
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
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
In kernel/sched/topology.c (c03a7a50)
Location: kernel/sched/topology.c:877
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
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
In kernel/sched/topology.c (c0000000001af358)
Location: kernel/sched/topology.c:877
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
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
In kernel/sched/topology.c (ffffffe00010110e)
Location: kernel/sched/topology.c:877
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
In kernel/sched/topology.c (ffffffff810f00c9)
Location: kernel/sched/topology.c:877
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
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
In kernel/sched/topology.c (ffffffff810e0139)
Location: kernel/sched/topology.c:877
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
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
In kernel/sched/topology.c (ffffffff810ed1f9)
Location: kernel/sched/topology.c:877
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
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
In kernel/sched/topology.c (ffffffff810f8239)
Location: kernel/sched/topology.c:877
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
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
</ul>
