# Function: <code>offload_action_init</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca54e2)
Location: net/sched/act_api.c:184
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_offload_del_ex
  - net/sched/act_api.c:tcf_action_update_hw_stats
  - net/sched/act_api.c:tcf_action_offload_add_ex
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
In net/sched/act_api.c (ffffffff81e61fd2)
Location: net/sched/act_api.c:185
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_offload_del_ex
  - net/sched/act_api.c:tcf_action_update_hw_stats
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int offload_action_init(struct flow_offload_action *fl_action, struct tc_action *act, enum offload_act_command cmd, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebcba0)
Location: net/sched/act_api.c:180
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_offload_del_ex
  - net/sched/act_api.c:tcf_action_update_hw_stats
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
**Symbols:**

```
ffffffff81ebcba0-ffffffff81ebcc2c: offload_action_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int offload_action_init(struct flow_offload_action *fl_action, struct tc_action *act, enum offload_act_command cmd, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f7fda0)
Location: net/sched/act_api.c:180
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_offload_del_ex
  - net/sched/act_api.c:tcf_action_update_hw_stats
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
**Symbols:**

```
ffffffff81f7fda0-ffffffff81f7fe2c: offload_action_init (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
