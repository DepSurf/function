# Function: <code>devlink_nl_trap_group_fill</code>

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
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81983490)
Location: net/core/devlink.c:5598
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff81983490-ffffffff81983597: devlink_nl_trap_group_fill.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5b140)
Location: net/core/devlink.c:6203
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff81a5b140-ffffffff81a5b29c: devlink_nl_trap_group_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a626c0)
Location: net/core/devlink.c:7049
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff81a626c0-ffffffff81a62819: devlink_nl_trap_group_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a44e50)
Location: net/core/devlink.c:7252
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff81a44e50-ffffffff81a44fa1: devlink_nl_trap_group_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7931
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff81afdda0-ffffffff81afdfca: devlink_nl_trap_group_fill (STB_LOCAL)
ffffffff81d38820-ffffffff81d38835: devlink_nl_trap_group_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:8424
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff81c812b0-ffffffff81c814fd: devlink_nl_trap_group_fill (STB_LOCAL)
ffffffff81f0519b-ffffffff81f051b0: devlink_nl_trap_group_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:8953
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff81e394f0-ffffffff81e3973d: devlink_nl_trap_group_fill (STB_LOCAL)
ffffffff820ad17c-ffffffff820ad191: devlink_nl_trap_group_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:5805
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff8203bda0-ffffffff8203c045: devlink_nl_trap_group_fill (STB_LOCAL)
ffffffff82136573-ffffffff82136588: devlink_nl_trap_group_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/trap.c (0)
Location: net/devlink/trap.c:475
Inline: False
Direct callers:
  - net/devlink/trap.c:devlink_nl_trap_group_get_dump_one
  - net/devlink/trap.c:devlink_nl_trap_group_get_doit
```
**Symbols:**

```
ffffffff821152f0-ffffffff82115595: devlink_nl_trap_group_fill (STB_LOCAL)
ffffffff82218736-ffffffff8221874b: devlink_nl_trap_group_fill.cold (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c2bac8)
Location: net/core/devlink.c:5598
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffff800010c2bac8-ffff800010c2bc00: devlink_nl_trap_group_fill.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_nl_trap_group_fill(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_group_item *group_item, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d4267c)
Location: net/core/devlink.c:5598
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
c0d4267c-c0d427a8: devlink_nl_trap_group_fill (STB_LOCAL)
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
In net/core/devlink.c (c000000000d22340)
Location: net/core/devlink.c:5598
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
c000000000d22340-c000000000d224b4: devlink_nl_trap_group_fill.isra.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffe0007a31d4)
Location: net/core/devlink.c:5598
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffe0007a31d4-ffffffe0007a32d8: devlink_nl_trap_group_fill.isra.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81923300)
Location: net/core/devlink.c:5598
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff81923300-ffffffff81923407: devlink_nl_trap_group_fill.isra.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff818dd0b0)
Location: net/core/devlink.c:5598
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff818dd0b0-ffffffff818dd1b7: devlink_nl_trap_group_fill.isra.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81974490)
Location: net/core/devlink.c:5598
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff81974490-ffffffff81974597: devlink_nl_trap_group_fill.isra.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81996980)
Location: net/core/devlink.c:5598
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff81996980-ffffffff81996a87: devlink_nl_trap_group_fill.isra.0 (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
