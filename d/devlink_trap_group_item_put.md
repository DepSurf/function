# Function: <code>devlink_trap_group_item_put</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_trap_group_item_put(struct devlink *devlink, struct devlink_trap_group_item *group_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81983910)
Location: net/core/devlink.c:7737
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff81983910-ffffffff81983974: devlink_trap_group_item_put (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2c9a0)
Location: net/core/devlink.c:7737
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
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
In net/core/devlink.c (c0d43604)
Location: net/core/devlink.c:7737
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_trap_group_item_put(struct devlink *devlink, struct devlink_trap_group_item *group_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d229b0)
Location: net/core/devlink.c:7737
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
c000000000d229b0-c000000000d22a70: devlink_trap_group_item_put (STB_LOCAL)
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
In net/core/devlink.c (ffffffe0007a3c9e)
Location: net/core/devlink.c:7737
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void devlink_trap_group_item_put(struct devlink *devlink, struct devlink_trap_group_item *group_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81923780)
Location: net/core/devlink.c:7737
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff81923780-ffffffff819237e4: devlink_trap_group_item_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_trap_group_item_put(struct devlink *devlink, struct devlink_trap_group_item *group_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dd530)
Location: net/core/devlink.c:7737
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff818dd530-ffffffff818dd594: devlink_trap_group_item_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_trap_group_item_put(struct devlink *devlink, struct devlink_trap_group_item *group_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81974910)
Location: net/core/devlink.c:7737
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff81974910-ffffffff81974974: devlink_trap_group_item_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_trap_group_item_put(struct devlink *devlink, struct devlink_trap_group_item *group_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81996e00)
Location: net/core/devlink.c:7737
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
**Symbols:**

```
ffffffff81996e00-ffffffff81996e64: devlink_trap_group_item_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
