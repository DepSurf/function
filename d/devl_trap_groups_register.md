# Function: <code>devl_trap_groups_register</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devl_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:12653
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_groups_register
```
**Symbols:**

```
ffffffff820ad191-ffffffff820ad1a6: devl_trap_groups_register.cold (STB_LOCAL)
ffffffff81e39b60-ffffffff81e39e93: devl_trap_groups_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devl_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:9248
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_trap_groups_register
```
**Symbols:**

```
ffffffff82136588-ffffffff8213659d: devl_trap_groups_register.cold (STB_LOCAL)
ffffffff8203c560-ffffffff8203c89b: devl_trap_groups_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devl_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/trap.c (0)
Location: net/devlink/trap.c:1615
Inline: False
Direct callers:
  - net/devlink/trap.c:devlink_trap_groups_register
```
**Symbols:**

```
ffffffff8221874b-ffffffff82218760: devl_trap_groups_register.cold (STB_LOCAL)
ffffffff821159b0-ffffffff82115d14: devl_trap_groups_register (STB_GLOBAL)
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
