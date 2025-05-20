# Function: <code>is_tcf_pedit</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195d141)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffff819935d1)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
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
In net/sched/cls_api.c (ffffffff81a6b6ce)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffff81a73e3e)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffff81a5c9de)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffff81b15b8e)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffff81c9d11c)
Location: include/net/tc_act/tc_pedit.h:24
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
```
```
In net/sched/act_api.c (ffffffff81ca49c4)
Location: include/net/tc_act/tc_pedit.h:24
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_offload_add_ex
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
In net/sched/cls_api.c (ffffffff81e599b8)
Location: include/net/tc_act/tc_pedit.h:31
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
```
```
In net/sched/act_api.c (ffffffff81e61449)
Location: include/net/tc_act/tc_pedit.h:31
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_offload_add_ex
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
In net/sched/cls_api.c (ffffffff81eb53f8)
Location: include/net/tc_act/tc_pedit.h:31
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
```
```
In net/sched/act_api.c (ffffffff81ebd489)
Location: include/net/tc_act/tc_pedit.h:31
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_offload_add_ex
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
In net/sched/cls_api.c (ffffffff81f78108)
Location: include/net/tc_act/tc_pedit.h:31
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
```
```
In net/sched/act_api.c (ffffffff81f80679)
Location: include/net/tc_act/tc_pedit.h:31
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_offload_add_ex
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
In net/sched/cls_api.c (ffff800010c3fa7c)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
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
In net/sched/cls_api.c (c0d515d0)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
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
In net/sched/cls_api.c (c000000000d3a010)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
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
In net/sched/cls_api.c (ffffffe0007af536)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
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
In net/sched/cls_api.c (ffffffff81933441)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
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
In net/sched/cls_api.c (ffffffff818ecf41)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
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
In net/sched/cls_api.c (ffffffff819845d1)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
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
In net/sched/cls_api.c (ffffffff819a6c91)
Location: include/net/tc_act/tc_pedit.h:23
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
```
</details>
</li>
</ul>

## Differences
