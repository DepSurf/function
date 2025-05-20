# Function: <code>__devlink_trap_action_set</code>

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
In net/core/devlink.c (ffffffff8197d684)
Location: net/core/devlink.c:5504
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
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
In net/core/devlink.c (ffffffff81a52fda)
Location: net/core/devlink.c:6096
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __devlink_trap_action_set(struct devlink *devlink, struct devlink_trap_item *trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a565c0)
Location: net/core/devlink.c:6947
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
```
**Symbols:**

```
ffffffff81a565c0-ffffffff81a56616: __devlink_trap_action_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __devlink_trap_action_set(struct devlink *devlink, struct devlink_trap_item *trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a39d80)
Location: net/core/devlink.c:7150
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
```
**Symbols:**

```
ffffffff81a39d80-ffffffff81a39def: __devlink_trap_action_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __devlink_trap_action_set(struct devlink *devlink, struct devlink_trap_item *trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81aefab0)
Location: net/core/devlink.c:7829
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
```
**Symbols:**

```
ffffffff81aefab0-ffffffff81aefb1f: __devlink_trap_action_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __devlink_trap_action_set(struct devlink *devlink, struct devlink_trap_item *trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c72f10)
Location: net/core/devlink.c:8322
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
```
**Symbols:**

```
ffffffff81c72f10-ffffffff81c72f8b: __devlink_trap_action_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __devlink_trap_action_set(struct devlink *devlink, struct devlink_trap_item *trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2b920)
Location: net/core/devlink.c:8851
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
```
**Symbols:**

```
ffffffff81e2b920-ffffffff81e2b99b: __devlink_trap_action_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __devlink_trap_action_set(struct devlink *devlink, struct devlink_trap_item *trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202f8d0)
Location: net/devlink/leftover.c:5703
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_set_doit
```
**Symbols:**

```
ffffffff8202f8d0-ffffffff8202f94b: __devlink_trap_action_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __devlink_trap_action_set(struct devlink *devlink, struct devlink_trap_item *trap_item, enum devlink_trap_action trap_action, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82114770)
Location: net/devlink/trap.c:374
Inline: False
Direct callers:
  - net/devlink/trap.c:devlink_nl_trap_group_set_doit
  - net/devlink/trap.c:devlink_nl_trap_set_doit
```
**Symbols:**

```
ffffffff82114770-ffffffff821147eb: __devlink_trap_action_set (STB_LOCAL)
```
</details>
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
In net/core/devlink.c (ffff800010c251f4)
Location: net/core/devlink.c:5504
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
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
In net/core/devlink.c (c0d3a444)
Location: net/core/devlink.c:5504
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
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
In net/core/devlink.c (c000000000d19054)
Location: net/core/devlink.c:5504
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
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
In net/core/devlink.c (ffffffe00079d6b8)
Location: net/core/devlink.c:5504
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
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
In net/core/devlink.c (ffffffff8191d4f4)
Location: net/core/devlink.c:5504
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
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
In net/core/devlink.c (ffffffff818d72a4)
Location: net/core/devlink.c:5504
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
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
In net/core/devlink.c (ffffffff8196e684)
Location: net/core/devlink.c:5504
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
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
In net/core/devlink.c (ffffffff81990b34)
Location: net/core/devlink.c:5504
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
