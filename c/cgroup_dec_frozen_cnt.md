# Function: <code>cgroup_dec_frozen_cnt</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8115e3fd)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
**Symbols:**

```
ffffffff8115dd40-ffffffff8115dd4d: cgroup_dec_frozen_cnt.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8116a03f)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
**Symbols:**

```
ffffffff81169930-ffffffff8116993d: cgroup_dec_frozen_cnt.part.0 (STB_LOCAL)
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
In kernel/cgroup/freezer.c (ffffffff8117bb9b)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
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
In kernel/cgroup/freezer.c (ffffffff811789eb)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
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
In kernel/cgroup/freezer.c (ffffffff8117955b)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
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
In kernel/cgroup/freezer.c (ffffffff811a0e6b)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
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
In kernel/cgroup/freezer.c (ffffffff811d167f)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
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
In kernel/cgroup/freezer.c (ffffffff8121524c)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
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
In kernel/cgroup/freezer.c (ffffffff8122ab7c)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
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
In kernel/cgroup/freezer.c (ffffffff81242b3f)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (ffff8000101dda10)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
**Symbols:**

```
ffff8000101dcd60-ffff8000101dcd7c: cgroup_dec_frozen_cnt.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (c041f5b0)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
**Symbols:**

```
c041eea8-c041eee8: cgroup_dec_frozen_cnt.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (c00000000024b778)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
**Symbols:**

```
c00000000024abc0-c00000000024abd0: cgroup_dec_frozen_cnt.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffe0001552f0)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
**Symbols:**

```
ffffffe000154aaa-ffffffe000154ac6: cgroup_dec_frozen_cnt.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8116265f)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
**Symbols:**

```
ffffffff81161f50-ffffffff81161f5d: cgroup_dec_frozen_cnt.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811558af)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
**Symbols:**

```
ffffffff811551b0-ffffffff811551bd: cgroup_dec_frozen_cnt.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8116042f)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
**Symbols:**

```
ffffffff8115fd20-ffffffff8115fd2d: cgroup_dec_frozen_cnt.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8116d78f)
Location: kernel/cgroup/freezer.c:97
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_freezer_migrate_task
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
```
**Symbols:**

```
ffffffff8116d050-ffffffff8116d05d: cgroup_dec_frozen_cnt.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
