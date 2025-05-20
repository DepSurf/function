# Function: <code>nla_put_bitfield32</code>

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
In net/sched/act_api.c (ffffffff81a74411)
Location: include/net/netlink.h:1527
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a60e3c)
Location: include/net/netlink.h:1540
Inline: True
```
```
In net/sched/act_api.c (ffffffff81a7d1c3)
Location: include/net/netlink.h:1540
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4ab2a)
Location: include/net/netlink.h:1540
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/sched/act_api.c (ffffffff81a65f15)
Location: include/net/netlink.h:1540
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b02bd3)
Location: include/net/netlink.h:1540
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/sched/act_api.c (ffffffff81b1f1d1)
Location: include/net/netlink.h:1540
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c8656e)
Location: include/net/netlink.h:1540
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/sched/act_api.c (ffffffff81ca6de4)
Location: include/net/netlink.h:1540
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e4069a)
Location: include/net/netlink.h:1589
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/act_api.c (ffffffff81e63324)
Location: include/net/netlink.h:1589
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebf3b4)
Location: include/net/netlink.h:1590
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/devlink/leftover.c (ffffffff820304df)
Location: include/net/netlink.h:1590
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_port_fn_caps_fill
```
```
In net/devlink/dev.c (ffffffff82044afd)
Location: include/net/netlink.h:1590
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f82534)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
  - net/sched/act_api.c:tcf_action_dump_1
```
```
In net/devlink/dev.c (ffffffff821043bd)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
```
```
In net/devlink/port.c (ffffffff821063e6)
Location: include/net/netlink.h:1666
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_fn_caps_fill
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
