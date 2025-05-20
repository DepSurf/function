# Function: <code>devl_trap_groups_unregister</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devl_trap_groups_unregister(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e39f48)
Location: net/core/devlink.c:12711
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_groups_unregister
```
**Symbols:**

```
ffffffff81e39b00-ffffffff81e39b4d: devl_trap_groups_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devl_trap_groups_unregister(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203c92c)
Location: net/devlink/leftover.c:9306
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_trap_groups_unregister
```
**Symbols:**

```
ffffffff8203c4f0-ffffffff8203c545: devl_trap_groups_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devl_trap_groups_unregister(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82115dac)
Location: net/devlink/trap.c:1673
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_trap_groups_unregister
```
**Symbols:**

```
ffffffff82115940-ffffffff82115995: devl_trap_groups_unregister (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
