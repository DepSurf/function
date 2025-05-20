# Function: <code>sched_group_span</code>

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
In kernel/sched/fair.c (ffffffff810c05f5)
Location: kernel/sched/sched.h:1097
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1097
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
In kernel/sched/fair.c (ffffffff810c7d05)
Location: kernel/sched/sched.h:1111
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810d4079)
Location: kernel/sched/sched.h:1111
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810cfd37)
Location: kernel/sched/sched.h:1200
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810dbd44)
Location: kernel/sched/sched.h:1200
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810d94e6)
Location: kernel/sched/sched.h:1354
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810e59eb)
Location: kernel/sched/sched.h:1354
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff810e0756)
Location: kernel/sched/sched.h:1412
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810ec5b2)
Location: kernel/sched/sched.h:1412
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
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
In kernel/sched/fair.c (ffffffff810eade6)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810f804e)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/fair.c (ffffffff810f4e84)
Location: kernel/sched/sched.h:1466
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/topology.c (ffffffff81100759)
Location: kernel/sched/sched.h:1466
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:build_balance_mask
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
In kernel/sched/fair.c (ffffffff810f2ef4)
Location: kernel/sched/sched.h:1524
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/topology.c (ffffffff810ff2a9)
Location: kernel/sched/sched.h:1524
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:build_balance_mask
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
In kernel/sched/fair.c (ffffffff810f50d0)
Location: kernel/sched/sched.h:1537
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/topology.c (ffffffff81103017)
Location: kernel/sched/sched.h:1537
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff8110ebc4)
Location: kernel/sched/sched.h:1825
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/topology.c (ffffffff8111fca0)
Location: kernel/sched/sched.h:1825
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff8112ab09)
Location: kernel/sched/sched.h:1805
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/build_utility.c (ffffffff81149daf)
Location: kernel/sched/sched.h:1805
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
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
In kernel/sched/fair.c (ffffffff811544d3)
Location: kernel/sched/sched.h:1856
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_utility.c (ffffffff811786d9)
Location: kernel/sched/sched.h:1856
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1899
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81189384)
Location: kernel/sched/sched.h:1899
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:get_group
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1941
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8118ca48)
Location: kernel/sched/sched.h:1941
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:get_group
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
In kernel/sched/fair.c (ffff80001014af34)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1422
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
In kernel/sched/fair.c (c0398c6c)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (c03a8f90)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
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
In kernel/sched/fair.c (c00000000019d458)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (0)
Location: kernel/sched/sched.h:1422
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
In kernel/sched/fair.c (ffffffe0000f47fa)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffe000101716)
Location: kernel/sched/sched.h:1422
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e4f46)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810f144e)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/fair.c (ffffffff810d40f6)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810e14be)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/fair.c (ffffffff810e1316)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810ee57e)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/fair.c (ffffffff810eceb6)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810f95be)
Location: kernel/sched/sched.h:1422
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
</details>
</li>
</ul>

## Differences
