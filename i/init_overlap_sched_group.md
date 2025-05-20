# Function: <code>init_overlap_sched_group</code>

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
Location: kernel/sched/topology.c:676
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
In kernel/sched/topology.c (ffffffff810d3a87)
Location: kernel/sched/topology.c:678
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
Location: kernel/sched/topology.c:670
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
Location: kernel/sched/topology.c:869
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
Location: kernel/sched/topology.c:898
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
Location: kernel/sched/topology.c:898
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
void init_overlap_sched_group(struct sched_domain *sd, struct sched_group *sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811016e0)
Location: kernel/sched/topology.c:896
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
```
**Symbols:**

```
ffffffff811016e0-ffffffff811017b0: init_overlap_sched_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_overlap_sched_group(struct sched_domain *sd, struct sched_group *sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81100240)
Location: kernel/sched/topology.c:957
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
```
**Symbols:**

```
ffffffff81100240-ffffffff81100310: init_overlap_sched_group (STB_LOCAL)
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
In kernel/sched/topology.c (ffffffff811023a0)
Location: kernel/sched/topology.c:928
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
In kernel/sched/topology.c (ffffffff8111ee78)
Location: kernel/sched/topology.c:942
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
In kernel/sched/build_utility.c (ffffffff81144617)
Location: kernel/sched/topology.c:958
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
In kernel/sched/build_utility.c (ffffffff8117147b)
Location: kernel/sched/topology.c:958
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
In kernel/sched/build_utility.c (ffffffff81181ca5)
Location: kernel/sched/topology.c:965
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
In kernel/sched/build_utility.c (ffffffff81190579)
Location: kernel/sched/topology.c:980
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
Location: kernel/sched/topology.c:898
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
Location: kernel/sched/topology.c:898
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
Location: kernel/sched/topology.c:898
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
Location: kernel/sched/topology.c:898
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
Location: kernel/sched/topology.c:898
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
Location: kernel/sched/topology.c:898
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
Location: kernel/sched/topology.c:898
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
Location: kernel/sched/topology.c:898
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
