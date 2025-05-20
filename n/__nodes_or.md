# Function: <code>__nodes_or</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111b693)
Location: include/linux/nodemask.h:159
Inline: True
```
```
In mm/mempolicy.c (ffffffff811e0b67)
Location: include/linux/nodemask.h:159
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112357b)
Location: include/linux/nodemask.h:161
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/mempolicy.c (ffffffff811ff51f)
Location: include/linux/nodemask.h:161
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cpuset.c (ffffffff8112b268)
Location: include/linux/nodemask.h:161
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/mempolicy.c (ffffffff8120fcde)
Location: include/linux/nodemask.h:161
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8112c581)
Location: include/linux/nodemask.h:161
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811393b1)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff81148481)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff81153fa1)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811604f1)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8116c1c1)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8117e0f1)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8117af61)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8117c7e1)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811a4371)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/migrate.c (ffffffff8133e29b)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
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
In kernel/cgroup/cpuset.c (ffffffff811d3e20)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/migrate.c (ffffffff813b10be)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
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
In kernel/cgroup/cpuset.c (ffffffff81217be0)
Location: include/linux/nodemask.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory-tiers.c (ffffffff81436c18)
Location: include/linux/nodemask.h:172
Inline: True
Inline callers:
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:nodelist_show
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
In kernel/cgroup/cpuset.c (ffffffff8122d400)
Location: include/linux/nodemask.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory-tiers.c (ffffffff8146c8d8)
Location: include/linux/nodemask.h:172
Inline: True
Inline callers:
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:nodelist_show
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
In kernel/cgroup/cpuset.c (ffffffff812456d0)
Location: include/linux/nodemask.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory-tiers.c (ffffffff8149ba28)
Location: include/linux/nodemask.h:172
Inline: True
Inline callers:
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:nodelist_show
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
In kernel/cgroup/cpuset.c (ffff8000101e10a4)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (c0421d34)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (c00000000024f040)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffe000157dd4)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811647e1)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff81157a2b)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811625b1)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8116fb31)
Location: include/linux/nodemask.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
</details>
</li>
</ul>

## Differences
