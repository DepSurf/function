# Function: <code>tcf_action_reoffload_cb</code>

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
int tcf_action_reoffload_cb(flow_indr_block_bind_cb_t *cb, void *cb_priv, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca80d0)
Location: net/sched/act_api.c:1792
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_indr_dev_register
```
**Symbols:**

```
ffffffff81ca80d0-ffffffff81ca82c6: tcf_action_reoffload_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_action_reoffload_cb(flow_indr_block_bind_cb_t *cb, void *cb_priv, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e64eb0)
Location: net/sched/act_api.c:1818
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_indr_dev_register
```
**Symbols:**

```
ffffffff81e64eb0-ffffffff81e650a6: tcf_action_reoffload_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_action_reoffload_cb(flow_indr_block_bind_cb_t *cb, void *cb_priv, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ec0df0)
Location: net/sched/act_api.c:1815
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_indr_dev_register
```
**Symbols:**

```
ffffffff81ec0df0-ffffffff81ec0fe6: tcf_action_reoffload_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_action_reoffload_cb(flow_indr_block_bind_cb_t *cb, void *cb_priv, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f84020)
Location: net/sched/act_api.c:1857
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
  - net/core/flow_offload.c:flow_indr_dev_register
```
**Symbols:**

```
ffffffff81f84020-ffffffff81f842ec: tcf_action_reoffload_cb (STB_GLOBAL)
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
