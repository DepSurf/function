# Function: <code>build_balance_mask</code>

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
In kernel/sched/topology.c (ffffffff810ccbed)
Location: kernel/sched/topology.c:619
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
In kernel/sched/topology.c (ffffffff810d3b67)
Location: kernel/sched/topology.c:620
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
In kernel/sched/topology.c (ffffffff810db83c)
Location: kernel/sched/topology.c:612
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
In kernel/sched/topology.c (ffffffff810e5437)
Location: kernel/sched/topology.c:811
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
In kernel/sched/topology.c (ffffffff810eb3d1)
Location: kernel/sched/topology.c:840
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
In kernel/sched/topology.c (ffffffff810f6d71)
Location: kernel/sched/topology.c:840
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
void build_balance_mask(struct sched_domain *sd, struct sched_group *sg, struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811013d0)
Location: kernel/sched/topology.c:838
Inline: False
Direct callers:
  - kernel/sched/topology.c:init_overlap_sched_group
```
**Symbols:**

```
ffffffff811013d0-ffffffff81101487: build_balance_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void build_balance_mask(struct sched_domain *sd, struct sched_group *sg, struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810fff30)
Location: kernel/sched/topology.c:899
Inline: False
Direct callers:
  - kernel/sched/topology.c:init_overlap_sched_group
```
**Symbols:**

```
ffffffff810fff30-ffffffff810fffe7: build_balance_mask (STB_LOCAL)
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
In kernel/sched/topology.c (ffffffff811023b6)
Location: kernel/sched/topology.c:870
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
In kernel/sched/topology.c (ffffffff8111ee8e)
Location: kernel/sched/topology.c:882
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
In kernel/sched/build_utility.c (ffffffff8114462d)
Location: kernel/sched/topology.c:898
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
In kernel/sched/build_utility.c (ffffffff81171488)
Location: kernel/sched/topology.c:898
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
In kernel/sched/build_utility.c (ffffffff81181cb2)
Location: kernel/sched/topology.c:905
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
In kernel/sched/build_utility.c (ffffffff81190586)
Location: kernel/sched/topology.c:920
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
In kernel/sched/topology.c (ffff80001015af7c)
Location: kernel/sched/topology.c:840
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
In kernel/sched/topology.c (c03a7ab8)
Location: kernel/sched/topology.c:840
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
In kernel/sched/topology.c (c0000000001af3f0)
Location: kernel/sched/topology.c:840
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
In kernel/sched/topology.c (ffffffe0001011bc)
Location: kernel/sched/topology.c:840
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
In kernel/sched/topology.c (ffffffff810f0171)
Location: kernel/sched/topology.c:840
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
In kernel/sched/topology.c (ffffffff810e01e1)
Location: kernel/sched/topology.c:840
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
In kernel/sched/topology.c (ffffffff810ed2a1)
Location: kernel/sched/topology.c:840
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
In kernel/sched/topology.c (ffffffff810f82e1)
Location: kernel/sched/topology.c:840
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
