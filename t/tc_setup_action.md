# Function: <code>tc_setup_action</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int tc_setup_action(struct flow_action *flow_action, struct tc_action **actions, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca3fd0)
Location: net/sched/cls_api.c:3532
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
**Symbols:**

```
ffffffff81ca3fd0-ffffffff81ca421d: tc_setup_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tc_setup_action(struct flow_action *flow_action, struct tc_action **actions, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e60910)
Location: net/sched/cls_api.c:3532
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
**Symbols:**

```
ffffffff81e60910-ffffffff81e60b5d: tc_setup_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tc_setup_action(struct flow_action *flow_action, struct tc_action **actions, u32 miss_cookie_base, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ebc870)
Location: net/sched/cls_api.c:3739
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_offload_action
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
**Symbols:**

```
ffffffff81ebc870-ffffffff81ebcaea: tc_setup_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tc_setup_action(struct flow_action *flow_action, struct tc_action **actions, u32 miss_cookie_base, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7fa70)
Location: net/sched/cls_api.c:3795
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_setup_offload_action
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
**Symbols:**

```
ffffffff81f7fa70-ffffffff81f7fcea: tc_setup_action (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 miss_cookie_base</code>
</li>
<li>
<b>Param reordered. </b>
<code>flow_action, actions, extack</code> ➡️ <code>flow_action, actions, miss_cookie_base, extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
