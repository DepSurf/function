# Function: <code>devlink_trap_group_item_destroy</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198392b)
Location: net/core/devlink.c:7711
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_group_item_put
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void devlink_trap_group_item_destroy(struct devlink *devlink, struct devlink_trap_group_item *group_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2bf48)
Location: net/core/devlink.c:7711
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffff800010c2bf48-ffff800010c2bfb0: devlink_trap_group_item_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_trap_group_item_destroy(struct devlink *devlink, struct devlink_trap_group_item *group_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d42aec)
Location: net/core/devlink.c:7711
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
c0d42aec-c0d42b3c: devlink_trap_group_item_destroy (STB_LOCAL)
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
In net/core/devlink.c (c000000000d229f8)
Location: net/core/devlink.c:7711
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_group_item_put
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_trap_group_item_destroy(struct devlink *devlink, struct devlink_trap_group_item *group_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a358e)
Location: net/core/devlink.c:7711
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffe0007a358e-ffffffe0007a35ec: devlink_trap_group_item_destroy (STB_LOCAL)
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
In net/core/devlink.c (ffffffff8192379b)
Location: net/core/devlink.c:7711
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_group_item_put
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
In net/core/devlink.c (ffffffff818dd54b)
Location: net/core/devlink.c:7711
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_group_item_put
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
In net/core/devlink.c (ffffffff8197492b)
Location: net/core/devlink.c:7711
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_group_item_put
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
In net/core/devlink.c (ffffffff81996e1b)
Location: net/core/devlink.c:7711
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_group_item_put
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
