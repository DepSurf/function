# Function: <code>devlink_trap_group_register</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_trap_group_register(struct devlink *devlink, const struct devlink_trap_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5b600)
Location: net/core/devlink.c:8972
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_groups_register
```
**Symbols:**

```
ffffffff81a5b600-ffffffff81a5b7c2: devlink_trap_group_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_trap_group_register(struct devlink *devlink, const struct devlink_trap_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a62b80)
Location: net/core/devlink.c:9926
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_groups_register
```
**Symbols:**

```
ffffffff81a62b80-ffffffff81a62d42: devlink_trap_group_register (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a454dd)
Location: net/core/devlink.c:10190
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_groups_register
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
In net/core/devlink.c (ffffffff81afe58c)
Location: net/core/devlink.c:11132
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_groups_register
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
In net/core/devlink.c (ffffffff81c8199a)
Location: net/core/devlink.c:11728
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_groups_register
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
In net/core/devlink.c (ffffffff81e39bf4)
Location: net/core/devlink.c:12583
Inline: True
Inline callers:
  - net/core/devlink.c:devl_trap_groups_register
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
In net/devlink/leftover.c (ffffffff8203c5fc)
Location: net/devlink/leftover.c:9178
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_trap_groups_register
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
In net/devlink/trap.c (ffffffff82115a46)
Location: net/devlink/trap.c:1545
Inline: True
Inline callers:
  - net/devlink/trap.c:devl_trap_groups_register
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
