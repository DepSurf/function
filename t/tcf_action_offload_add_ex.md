# Function: <code>tcf_action_offload_add_ex</code>

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
int tcf_action_offload_add_ex(struct tc_action *action, struct netlink_ext_ack *extack, flow_indr_block_bind_cb_t *cb, void *cb_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca4950)
Location: net/sched/act_api.c:249
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81ca4950-ffffffff81ca4b54: tcf_action_offload_add_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_action_offload_add_ex(struct tc_action *action, struct netlink_ext_ack *extack, flow_indr_block_bind_cb_t *cb, void *cb_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e613a0)
Location: net/sched/act_api.c:250
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81e613a0-ffffffff81e615c5: tcf_action_offload_add_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_action_offload_add_ex(struct tc_action *action, struct netlink_ext_ack *extack, flow_indr_block_bind_cb_t *cb, void *cb_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebd3f0)
Location: net/sched/act_api.c:246
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81ebd3f0-ffffffff81ebd5c5: tcf_action_offload_add_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_action_offload_add_ex(struct tc_action *action, struct netlink_ext_ack *extack, flow_indr_block_bind_cb_t *cb, void *cb_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f805e0)
Location: net/sched/act_api.c:246
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81f805e0-ffffffff81f807b5: tcf_action_offload_add_ex (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
