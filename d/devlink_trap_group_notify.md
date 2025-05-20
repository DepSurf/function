# Function: <code>devlink_trap_group_notify</code>

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
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81983840)
Location: net/core/devlink.c:7642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_group_item_put
```
**Symbols:**

```
ffffffff81983840-ffffffff81983904: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5b550)
Location: net/core/devlink.c:8667
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_group_register
```
**Symbols:**

```
ffffffff81a5b550-ffffffff81a5b5fe: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a62ad0)
Location: net/core/devlink.c:9625
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_group_register
```
**Symbols:**

```
ffffffff81a62ad0-ffffffff81a62b7d: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a45280)
Location: net/core/devlink.c:9889
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_groups_register
```
**Symbols:**

```
ffffffff81a45280-ffffffff81a4532d: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afe310)
Location: net/core/devlink.c:10831
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_groups_register
```
**Symbols:**

```
ffffffff81afe310-ffffffff81afe3bd: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c81690)
Location: net/core/devlink.c:11423
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
```
**Symbols:**

```
ffffffff81c81690-ffffffff81c817a4: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e398f0)
Location: net/core/devlink.c:12239
Inline: True
Direct callers:
  - net/core/devlink.c:devl_trap_groups_register
  - net/core/devlink.c:devlink_notify_unregister
  - net/core/devlink.c:devlink_notify_register
```
**Symbols:**

```
ffffffff81e398f0-ffffffff81e39a04: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203c2e0)
Location: net/devlink/leftover.c:8834
Inline: True
Direct callers:
  - net/devlink/leftover.c:devl_trap_groups_register
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_register
```
**Symbols:**

```
ffffffff8203c2e0-ffffffff8203c3f5: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82115690)
Location: net/devlink/trap.c:1167
Inline: True
Direct callers:
  - net/devlink/trap.c:devl_trap_groups_register
  - net/devlink/trap.c:devlink_trap_groups_notify_unregister
  - net/devlink/trap.c:devlink_trap_groups_notify_register
```
**Symbols:**

```
ffffffff82115690-ffffffff82115846: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2be80)
Location: net/core/devlink.c:7642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_group_item_destroy
```
**Symbols:**

```
ffff800010c2be80-ffff800010c2bf44: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d42a04)
Location: net/core/devlink.c:7642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_group_item_destroy
```
**Symbols:**

```
c0d42a04-c0d42aec: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d22870)
Location: net/core/devlink.c:7642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_group_item_put
```
**Symbols:**

```
c000000000d22870-c000000000d229a8: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a34ee)
Location: net/core/devlink.c:7642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_group_item_destroy
```
**Symbols:**

```
ffffffe0007a34ee-ffffffe0007a358e: devlink_trap_group_notify (STB_LOCAL)
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
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819236b0)
Location: net/core/devlink.c:7642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_group_item_put
```
**Symbols:**

```
ffffffff819236b0-ffffffff81923774: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dd460)
Location: net/core/devlink.c:7642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_group_item_put
```
**Symbols:**

```
ffffffff818dd460-ffffffff818dd524: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81974840)
Location: net/core/devlink.c:7642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_group_item_put
```
**Symbols:**

```
ffffffff81974840-ffffffff81974904: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_trap_group_notify(struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81996d30)
Location: net/core/devlink.c:7642
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_group_item_put
```
**Symbols:**

```
ffffffff81996d30-ffffffff81996df4: devlink_trap_group_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
