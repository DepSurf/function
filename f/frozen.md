# Function: <code>frozen</code>

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
In kernel/power/process.c (0)
Location: include/linux/freezer.h:24
Inline: True
```
```
In kernel/freezer.c (ffffffff810e9d3d)
Location: include/linux/freezer.h:24
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup_freezer.c (0)
Location: include/linux/freezer.h:24
Inline: True
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
In kernel/power/process.c (0)
Location: include/linux/freezer.h:24
Inline: True
```
```
In kernel/freezer.c (ffffffff810f0a8f)
Location: include/linux/freezer.h:24
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup_freezer.c (0)
Location: include/linux/freezer.h:24
Inline: True
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
In kernel/power/process.c (0)
Location: include/linux/freezer.h:24
Inline: True
```
```
In kernel/freezer.c (ffffffff810f7bef)
Location: include/linux/freezer.h:24
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup_freezer.c (0)
Location: include/linux/freezer.h:24
Inline: True
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
In kernel/power/process.c (0)
Location: include/linux/freezer.h:24
Inline: True
```
```
In kernel/freezer.c (ffffffff810f9abf)
Location: include/linux/freezer.h:24
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/freezer.h:24
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
In kernel/power/process.c (0)
Location: include/linux/freezer.h:25
Inline: True
```
```
In kernel/freezer.c (ffffffff81104582)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (0)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff810e8c92)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8110f41e)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff81146668)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff810f428d)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8111aa5e)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/freezer.c (ffffffff81152208)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff810fc7c4)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8112515f)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115e89b)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff81108be4)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8113111f)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a4f1)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff811137de)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811404ef)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c013)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff81bdeb11)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8113c85f)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81178e4d)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff81bd0c8a)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8113daaf)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811799bd)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff81ca99af)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81160c2f)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a12dd)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff81e598d5)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811939be)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1bd6)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool frozen(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811d12e1)
Location: kernel/freezer.c:56
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
**Symbols:**

```
ffffffff811d1230-ffffffff811d124a: frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool frozen(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811e5551)
Location: kernel/freezer.c:56
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
**Symbols:**

```
ffffffff811e54a0-ffffffff811e54ba: frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool frozen(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811fb3b0)
Location: kernel/freezer.c:56
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
**Symbols:**

```
ffffffff811fb250-ffffffff811fb26a: frozen (STB_GLOBAL)
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
In kernel/power/process.c (ffff80001016fd18)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffff8000101984d4)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de014)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (c03ba9ac)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (c03e3430)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (c041ff9c)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (c0000000001c7e60)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (c0000000001f83e4)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024bdd8)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffe00010dc5a)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffe000129136)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe0001556e0)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff81101d24)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811298cf)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162b11)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff810f20e4)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8111c15f)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81155d61)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff810ff0b4)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811275ef)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811608e1)
Location: include/linux/freezer.h:25
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
In kernel/power/process.c (ffffffff8110a3b9)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81133c2f)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116dc60)
Location: include/linux/freezer.h:25
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
