# Function: <code>devlink_trap_groups_register</code>

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
int devlink_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5b8f0)
Location: net/core/devlink.c:9042
Inline: False
```
**Symbols:**

```
ffffffff81a5b8f0-ffffffff81a5ba3a: devlink_trap_groups_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a62e70)
Location: net/core/devlink.c:9996
Inline: False
```
**Symbols:**

```
ffffffff81a62e70-ffffffff81a62fba: devlink_trap_groups_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a45450)
Location: net/core/devlink.c:10260
Inline: False
```
**Symbols:**

```
ffffffff81a45450-ffffffff81a4573c: devlink_trap_groups_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:11202
Inline: False
```
**Symbols:**

```
ffffffff81d38835-ffffffff81d3884a: devlink_trap_groups_register.cold (STB_LOCAL)
ffffffff81afe4e0-ffffffff81afe840: devlink_trap_groups_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:11798
Inline: False
```
**Symbols:**

```
ffffffff81f051b0-ffffffff81f051c5: devlink_trap_groups_register.cold (STB_LOCAL)
ffffffff81c818f0-ffffffff81c81c49: devlink_trap_groups_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e39eb0)
Location: net/core/devlink.c:12692
Inline: False
```
**Symbols:**

```
ffffffff81e39eb0-ffffffff81e39f05: devlink_trap_groups_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203c8b0)
Location: net/devlink/leftover.c:9287
Inline: False
```
**Symbols:**

```
ffffffff8203c8b0-ffffffff8203c8f9: devlink_trap_groups_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_trap_groups_register(struct devlink *devlink, const struct devlink_trap_group *groups, size_t groups_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82115d30)
Location: net/devlink/trap.c:1654
Inline: False
```
**Symbols:**

```
ffffffff82115d30-ffffffff82115d79: devlink_trap_groups_register (STB_GLOBAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
