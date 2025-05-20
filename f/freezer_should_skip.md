# Function: <code>freezer_should_skip</code>

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
In kernel/power/process.c (ffffffff810cd972)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff810e9cd1)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup_freezer.c (ffffffff8111a07f)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
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
In kernel/power/process.c (ffffffff810d2438)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff810f0a2f)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup_freezer.c (ffffffff81121ea8)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
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
In kernel/power/process.c (ffffffff810d8fe8)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff810f7b8f)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup_freezer.c (ffffffff8112a4de)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
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
In kernel/power/process.c (ffffffff810d7fe8)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff810f9a5f)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8112b1aa)
Location: include/linux/freezer.h:148
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_read
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
In kernel/power/process.c (ffffffff810e00d8)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8110451f)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff81137d60)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff810e87a7)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8110f31f)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8114666e)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff810f3db7)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8111a961)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff8115220e)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff810fc291)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81125062)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115e8a1)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff811086b1)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81131022)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a4f7)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff811132b1)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811403f2)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c019)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff81110301)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8113c762)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81178e53)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff81110d41)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8113d9b2)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811799c3)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff81130821)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81160b32)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a12e3)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff81152025)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811938b1)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1bdd)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/power/process.c (ffff80001016fa90)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffff80001019832c)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de01c)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (c03ba6b0)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (c03e331c)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (c041ffa8)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
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
In kernel/power/process.c (c0000000001c7ad4)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (c0000000001f8254)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024bde4)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffe00010db68)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffe000129042)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe0001556e2)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff811017f1)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811297d2)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162b17)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff810f1bb1)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8111c062)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81155d67)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff810feb81)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811274f2)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811608e7)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
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
In kernel/power/process.c (ffffffff81109e45)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81133b32)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116dc66)
Location: include/linux/freezer.h:149
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
</details>
</li>
</ul>

## Differences
