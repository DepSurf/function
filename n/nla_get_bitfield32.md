# Function: <code>nla_get_bitfield32</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81882474)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d5f83)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81902784)
Location: include/net/netlink.h:1395
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819639e9)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199a569)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a70ff2)
Location: include/net/netlink.h:1720
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (ffffffff81a734c7)
Location: include/net/netlink.h:1720
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
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
In net/core/devlink.c (ffffffff81a632bf)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/sched/cls_api.c (ffffffff81a799d2)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (ffffffff81a7c0c7)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
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
In net/core/devlink.c (ffffffff81a4719f)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/sched/cls_api.c (ffffffff81a62b93)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (ffffffff81a64cf8)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
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
In net/core/devlink.c (ffffffff81afd0af)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/sched/cls_api.c (ffffffff81b1bea3)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (ffffffff81b1dfc8)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
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
In net/core/devlink.c (ffffffff81c8008f)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/sched/cls_api.c (ffffffff81ca1641)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (ffffffff81ca59a1)
Location: include/net/netlink.h:1733
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
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
In net/core/devlink.c (ffffffff81e391c7)
Location: include/net/netlink.h:1782
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/sched/cls_api.c (ffffffff81e5e051)
Location: include/net/netlink.h:1782
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (ffffffff81e63a41)
Location: include/net/netlink.h:1782
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
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
In net/sched/cls_api.c (ffffffff81ebbb81)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (ffffffff81ebfad7)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/devlink/leftover.c (ffffffff8203d4ed)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_port_function_set
  - net/devlink/leftover.c:devlink_port_function_set
```
```
In net/devlink/dev.c (ffffffff820452b7)
Location: include/net/netlink.h:1783
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_flash_update
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
In net/sched/cls_api.c (ffffffff81f7eda1)
Location: include/net/netlink.h:1881
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
```
In net/sched/act_api.c (ffffffff81f82c87)
Location: include/net/netlink.h:1881
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/devlink/dev.c (ffffffff82104bb7)
Location: include/net/netlink.h:1881
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_flash_update_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
```
```
In net/devlink/port.c (ffffffff82106f73)
Location: include/net/netlink.h:1881
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_function_set
  - net/devlink/port.c:devlink_port_function_validate
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
In net/sched/act_api.c (ffff800010c47784)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
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
In net/sched/act_api.c (c0d58580)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
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
In net/sched/act_api.c (c000000000d44644)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
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
In net/sched/act_api.c (ffffffe0007b54bc)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
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
In net/sched/act_api.c (ffffffff8193a3d9)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
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
In net/sched/act_api.c (ffffffff818f3ed9)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
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
In net/sched/act_api.c (ffffffff8198b569)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
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
In net/sched/act_api.c (ffffffff819addd9)
Location: include/net/netlink.h:1653
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
</details>
</li>
</ul>

## Differences
