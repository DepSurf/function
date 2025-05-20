# Function: <code>cpufreq_policy_apply_limits</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81717044)
Location: include/linux/cpufreq.h:526
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d440e)
Location: include/linux/cpufreq.h:530
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81748da1)
Location: include/linux/cpufreq.h:530
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d357e)
Location: include/linux/cpufreq.h:534
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81767441)
Location: include/linux/cpufreq.h:534
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810db14e)
Location: include/linux/cpufreq.h:543
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817dd371)
Location: include/linux/cpufreq.h:543
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810e338e)
Location: include/linux/cpufreq.h:543
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81825ff3)
Location: include/linux/cpufreq.h:543
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810eda5e)
Location: include/linux/cpufreq.h:535
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81851ed3)
Location: include/linux/cpufreq.h:535
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f47eb)
Location: include/linux/cpufreq.h:564
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81895413)
Location: include/linux/cpufreq.h:564
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff811004ab)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c7423)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110ab4b)
Location: include/linux/cpufreq.h:583
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81999773)
Location: include/linux/cpufreq.h:583
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81107a5b)
Location: include/linux/cpufreq.h:636
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c853)
Location: include/linux/cpufreq.h:636
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81109b2b)
Location: include/linux/cpufreq.h:630
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81981523)
Location: include/linux/cpufreq.h:630
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8112824c)
Location: include/linux/cpufreq.h:627
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a773)
Location: include/linux/cpufreq.h:627
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/build_utility.c (ffffffff8113dfd7)
Location: include/linux/cpufreq.h:643
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b94aa3)
Location: include/linux/cpufreq.h:643
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/build_utility.c (ffffffff81168767)
Location: include/linux/cpufreq.h:643
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d34b93)
Location: include/linux/cpufreq.h:643
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/build_utility.c (ffffffff81178de7)
Location: include/linux/cpufreq.h:646
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9df03)
Location: include/linux/cpufreq.h:646
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/build_utility.c (ffffffff81186b37)
Location: include/linux/cpufreq.h:641
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55c83)
Location: include/linux/cpufreq.h:641
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffff800010164c10)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b257c0)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (c03b1238)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bff7a0)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (c0000000001bbb54)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (c000000000c1a8e0)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f97bb)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186bb43)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810e999b)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818347f3)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f69db)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bc8d3)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81101a3b)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_limits
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d8bc3)
Location: include/linux/cpufreq.h:581
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_limits
```
</details>
</li>
</ul>

## Differences
