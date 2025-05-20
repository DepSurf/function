# Function: <code>devlink_trap_policer_item_lookup</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5fc0f)
Location: net/core/devlink.c:5837
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_unregister
  - net/core/devlink.c:devlink_trap_policer_register
  - net/core/devlink.c:devlink_trap_group_register
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a683ff)
Location: net/core/devlink.c:6688
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policer_unregister
  - net/core/devlink.c:devlink_trap_policer_register
  - net/core/devlink.c:devlink_trap_group_register
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff81a43573)
Location: net/core/devlink.c:6891
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policers_register
  - net/core/devlink.c:devlink_trap_policer_unregister
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff81af9a53)
Location: net/core/devlink.c:7517
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policers_register
  - net/core/devlink.c:devlink_trap_policer_unregister
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff81c7c7db)
Location: net/core/devlink.c:8010
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_policers_register
  - net/core/devlink.c:devlink_trap_policer_unregister
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff81e410d4)
Location: net/core/devlink.c:8545
Inline: True
Inline callers:
  - net/core/devlink.c:devl_trap_policers_register
  - net/core/devlink.c:devlink_trap_policer_unregister
  - net/core/devlink.c:devl_trap_groups_register
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/devlink/leftover.c (ffffffff82037d89)
Location: net/devlink/leftover.c:5401
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_trap_policers_register
  - net/devlink/leftover.c:devlink_trap_policer_unregister
  - net/devlink/leftover.c:devl_trap_groups_register
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_set_doit
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
In net/devlink/trap.c (ffffffff821150d0)
Location: net/devlink/trap.c:73
Inline: True
Inline callers:
  - net/devlink/trap.c:devl_trap_policers_register
  - net/devlink/trap.c:devlink_trap_policer_unregister
  - net/devlink/trap.c:devl_trap_groups_register
  - net/devlink/trap.c:devlink_nl_trap_policer_set_doit
  - net/devlink/trap.c:devlink_nl_trap_policer_get_doit
  - net/devlink/trap.c:devlink_nl_trap_group_set_doit
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
