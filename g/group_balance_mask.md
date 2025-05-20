# Function: <code>group_balance_mask</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c0692)
Location: kernel/sched/sched.h:1105
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1105
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c7da2)
Location: kernel/sched/sched.h:1119
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1119
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cfd9f)
Location: kernel/sched/sched.h:1208
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1208
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d956f)
Location: kernel/sched/sched.h:1362
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1362
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e07ed)
Location: kernel/sched/sched.h:1420
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1420
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eae7d)
Location: kernel/sched/sched.h:1430
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1430
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4f17)
Location: kernel/sched/sched.h:1474
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff811007ca)
Location: kernel/sched/sched.h:1474
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f2f87)
Location: kernel/sched/sched.h:1532
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810ff31a)
Location: kernel/sched/sched.h:1532
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f515b)
Location: kernel/sched/sched.h:1545
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff81103090)
Location: kernel/sched/sched.h:1545
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110ec4d)
Location: kernel/sched/sched.h:1833
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff8111fd19)
Location: kernel/sched/sched.h:1833
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8112ab95)
Location: kernel/sched/sched.h:1813
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_utility.c (ffffffff81149e28)
Location: kernel/sched/sched.h:1813
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81154556)
Location: kernel/sched/sched.h:1864
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_utility.c (ffffffff8117874e)
Location: kernel/sched/sched.h:1864
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116464f)
Location: kernel/sched/sched.h:1907
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_utility.c (ffffffff811893f9)
Location: kernel/sched/sched.h:1907
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811713f6)
Location: kernel/sched/sched.h:1949
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:should_we_balance
```
```
In kernel/sched/build_utility.c (ffffffff8118cb08)
Location: kernel/sched/sched.h:1949
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014afb8)
Location: kernel/sched/sched.h:1430
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1430
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0398d00)
Location: kernel/sched/sched.h:1430
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (c03a8cc0)
Location: kernel/sched/sched.h:1430
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019d520)
Location: kernel/sched/sched.h:1430
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1430
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f48fe)
Location: kernel/sched/sched.h:1430
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1430
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e4fdd)
Location: kernel/sched/sched.h:1430
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1430
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d418d)
Location: kernel/sched/sched.h:1430
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1430
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e13ad)
Location: kernel/sched/sched.h:1430
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1430
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ecf4d)
Location: kernel/sched/sched.h:1430
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1430
Inline: True
```
</details>
</li>
</ul>

## Differences
