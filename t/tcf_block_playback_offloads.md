# Function: <code>tcf_block_playback_offloads</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, tc_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fd5f0)
Location: net/sched/cls_api.c:1180
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_cb_unregister
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff818fd5f0-ffffffff818fd6e2: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195ed10)
Location: net/sched/cls_api.c:1521
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff8195ed10-ffffffff8195ee62: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81996170)
Location: net/sched/cls_api.c:1435
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81996170-ffffffff819962c2: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6e990)
Location: net/sched/cls_api.c:1398
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_unbind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81a6e990-ffffffff81a6eae2: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a77370)
Location: net/sched/cls_api.c:1399
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_unbind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81a77370-ffffffff81a774c2: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5f970)
Location: net/sched/cls_api.c:1399
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_unbind
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81a5f970-ffffffff81a5fad5: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b18b80)
Location: net/sched/cls_api.c:1400
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_unbind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81b18b80-ffffffff81b18ce5: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca0240)
Location: net/sched/cls_api.c:1417
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_unbind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81ca0240-ffffffff81ca03bc: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5c1f0)
Location: net/sched/cls_api.c:1419
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_unbind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81e5c1f0-ffffffff81e5c36c: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb8d80)
Location: net/sched/cls_api.c:1524
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_unbind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81eb8d80-ffffffff81eb8efc: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7be50)
Location: net/sched/cls_api.c:1548
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_unbind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81f7be50-ffffffff81f7c047: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c42a00)
Location: net/sched/cls_api.c:1435
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffff800010c42a00-ffff800010c42b78: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d53fec)
Location: net/sched/cls_api.c:1435
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
c0d53fec-c0d54164: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3e350)
Location: net/sched/cls_api.c:1435
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
c000000000d3e350-c000000000d3e574: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b1a6e)
Location: net/sched/cls_api.c:1435
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffe0007b1a6e-ffffffe0007b1bd0: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81935fe0)
Location: net/sched/cls_api.c:1435
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81935fe0-ffffffff81936132: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818efae0)
Location: net/sched/cls_api.c:1435
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff818efae0-ffffffff818efc32: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81987170)
Location: net/sched/cls_api.c:1435
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff81987170-ffffffff819872c2: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_block_playback_offloads(struct tcf_block *block, flow_setup_cb_t *cb, void *cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9630)
Location: net/sched/cls_api.c:1435
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_playback_offloads
```
**Symbols:**

```
ffffffff819a9630-ffffffff819a9782: tcf_block_playback_offloads (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>tc_setup_cb_t *cb</code> ➡️ <code>flow_setup_cb_t *cb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
