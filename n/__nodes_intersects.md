# Function: <code>__nodes_intersects</code>

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
In kernel/cpuset.c (ffffffff8111b6e8)
Location: include/linux/nodemask.h:199
Inline: True
```
```
In mm/mempolicy.c (ffffffff811e1fa6)
Location: include/linux/nodemask.h:199
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cpuset.c (ffffffff81125715)
Location: include/linux/nodemask.h:201
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/mempolicy.c (ffffffff81200996)
Location: include/linux/nodemask.h:201
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cpuset.c (ffffffff8112f0f6)
Location: include/linux/nodemask.h:201
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff812123a6)
Location: include/linux/nodemask.h:201
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff81130776)
Location: include/linux/nodemask.h:201
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8121d736)
Location: include/linux/nodemask.h:201
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff8113d6a6)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff81238926)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff8114bfd5)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8125be49)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff81158c25)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff81270709)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff81165305)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8128c007)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff811711f5)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8129bbd7)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff81182f05)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff812cf7d7)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff8117fe75)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff812db2a7)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff81180955)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff812e2b17)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff811a8745)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff81329eb9)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811d98d5)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff81399321)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8121ed75)
Location: include/linux/nodemask.h:212
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff81419191)
Location: include/linux/nodemask.h:212
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff81234ea5)
Location: include/linux/nodemask.h:212
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff8144c671)
Location: include/linux/nodemask.h:212
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8124eac5)
Location: include/linux/nodemask.h:212
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff814858f1)
Location: include/linux/nodemask.h:212
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
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
In kernel/cgroup/cpuset.c (ffff8000101e4864)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffff80001033ab54)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (c042569c)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
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
In kernel/cgroup/cpuset.c (c000000000254ffc)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (c000000000415564)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffe00015aa62)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
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
In kernel/cgroup/cpuset.c (ffffffff81169815)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff812941b7)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff8115ca15)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff81285dc7)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff811675e5)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff81291fc7)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In kernel/cgroup/cpuset.c (ffffffff81174c65)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff812a1dd7)
Location: include/linux/nodemask.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
</details>
</li>
</ul>

## Differences
