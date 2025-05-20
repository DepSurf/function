# Function: <code>tcf_pedit_nkeys</code>

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
In net/sched/cls_api.c (ffffffff8195d14c)
Location: include/net/tc_act/tc_pedit.h:32
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
In net/sched/cls_api.c (ffffffff819935dc)
Location: include/net/tc_act/tc_pedit.h:32
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffff81a6b6dc)
Location: include/net/tc_act/tc_pedit.h:32
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
In net/sched/cls_api.c (ffffffff81a73e4c)
Location: include/net/tc_act/tc_pedit.h:32
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
In net/sched/cls_api.c (ffffffff81a5c9ec)
Location: include/net/tc_act/tc_pedit.h:32
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
In net/sched/cls_api.c (ffffffff81b15b9c)
Location: include/net/tc_act/tc_pedit.h:32
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
In net/sched/cls_api.c (ffffffff81c9d12a)
Location: include/net/tc_act/tc_pedit.h:33
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
```
```
In net/sched/act_api.c (ffffffff81ca4b0c)
Location: include/net/tc_act/tc_pedit.h:33
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
In net/sched/cls_api.c (ffffffff81e599c7)
Location: include/net/tc_act/tc_pedit.h:40
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
```
```
In net/sched/act_api.c (ffffffff81e61585)
Location: include/net/tc_act/tc_pedit.h:40
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
In net/sched/cls_api.c (ffffffff81eb5407)
Location: include/net/tc_act/tc_pedit.h:40
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
```
```
In net/sched/act_api.c (ffffffff81ebd58b)
Location: include/net/tc_act/tc_pedit.h:40
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
In net/sched/cls_api.c (ffffffff81f78117)
Location: include/net/tc_act/tc_pedit.h:40
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
```
```
In net/sched/act_api.c (ffffffff81f8077b)
Location: include/net/tc_act/tc_pedit.h:40
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
In net/sched/cls_api.c (ffff800010c3faa8)
Location: include/net/tc_act/tc_pedit.h:32
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (c0d531b8)
Location: include/net/tc_act/tc_pedit.h:32
Inline: True
Inline callers:
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
In net/sched/cls_api.c (c000000000d3a050)
Location: include/net/tc_act/tc_pedit.h:32
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffe0007af55c)
Location: include/net/tc_act/tc_pedit.h:32
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffff8193344c)
Location: include/net/tc_act/tc_pedit.h:32
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffff818ecf4c)
Location: include/net/tc_act/tc_pedit.h:32
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffff819845dc)
Location: include/net/tc_act/tc_pedit.h:32
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
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
In net/sched/cls_api.c (ffffffff819a6c9c)
Location: include/net/tc_act/tc_pedit.h:32
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_num_actions
  - net/sched/cls_api.c:tc_setup_flow_action
```
</details>
</li>
</ul>

## Differences
