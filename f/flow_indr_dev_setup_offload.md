# Function: <code>flow_indr_dev_setup_offload</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int flow_indr_dev_setup_offload(struct net_device *dev, enum tc_setup_type type, void *data, struct flow_block_offload *bo, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a36a40)
Location: net/core/flow_offload.c:466
Inline: False
```
**Symbols:**

```
ffffffff81a36a40-ffffffff81a36ae0: flow_indr_dev_setup_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int flow_indr_dev_setup_offload(struct net_device *dev, struct Qdisc *sch, enum tc_setup_type type, void *data, struct flow_block_offload *bo, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a38de0)
Location: net/core/flow_offload.c:466
Inline: False
```
**Symbols:**

```
ffffffff81a38de0-ffffffff81a38e88: flow_indr_dev_setup_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int flow_indr_dev_setup_offload(struct net_device *dev, struct Qdisc *sch, enum tc_setup_type type, void *data, struct flow_block_offload *bo, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a20090)
Location: net/core/flow_offload.c:466
Inline: False
```
**Symbols:**

```
ffffffff81a20090-ffffffff81a20138: flow_indr_dev_setup_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int flow_indr_dev_setup_offload(struct net_device *dev, struct Qdisc *sch, enum tc_setup_type type, void *data, struct flow_block_offload *bo, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81ad4760)
Location: net/core/flow_offload.c:546
Inline: False
```
**Symbols:**

```
ffffffff81ad4760-ffffffff81ad4927: flow_indr_dev_setup_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int flow_indr_dev_setup_offload(struct net_device *dev, struct Qdisc *sch, enum tc_setup_type type, void *data, struct flow_block_offload *bo, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81c52db0)
Location: net/core/flow_offload.c:570
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
**Symbols:**

```
ffffffff81c52db0-ffffffff81c52ffa: flow_indr_dev_setup_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int flow_indr_dev_setup_offload(struct net_device *dev, struct Qdisc *sch, enum tc_setup_type type, void *data, struct flow_block_offload *bo, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e083a0)
Location: net/core/flow_offload.c:598
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
**Symbols:**

```
ffffffff81e083a0-ffffffff81e085ea: flow_indr_dev_setup_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int flow_indr_dev_setup_offload(struct net_device *dev, struct Qdisc *sch, enum tc_setup_type type, void *data, struct flow_block_offload *bo, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e7acc0)
Location: net/core/flow_offload.c:598
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
**Symbols:**

```
ffffffff81e7acc0-ffffffff81e7af0a: flow_indr_dev_setup_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int flow_indr_dev_setup_offload(struct net_device *dev, struct Qdisc *sch, enum tc_setup_type type, void *data, struct flow_block_offload *bo, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81f3aef0)
Location: net/core/flow_offload.c:605
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
**Symbols:**

```
ffffffff81f3aef0-ffffffff81f3b169: flow_indr_dev_setup_offload (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct Qdisc *sch</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, type, data, bo, cleanup</code> ➡️ <code>dev, sch, type, data, bo, cleanup</code>
</li>
</ul>
</details>
</li>
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
