# Function: <code>tcf_proto_destroy</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81801880)
Location: net/sched/cls_api.c:182
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81801880-ffffffff818018b2: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187f6e0)
Location: net/sched/cls_api.c:175
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff8187f6e0-ffffffff8187f718: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d2530)
Location: net/sched/cls_api.c:176
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff818d2530-ffffffff818d2568: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fdac0)
Location: net/sched/cls_api.c:188
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff818fdac0-ffffffff818fdafb: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195ea80)
Location: net/sched/cls_api.c:223
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_put
```
**Symbols:**

```
ffffffff8195ea80-ffffffff8195ead1: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81995360)
Location: net/sched/cls_api.c:293
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81995360-ffffffff81995402: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6e1b0)
Location: net/sched/cls_api.c:294
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_proto_put
```
**Symbols:**

```
ffffffff81a6e1b0-ffffffff81a6e252: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a76b80)
Location: net/sched/cls_api.c:294
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_proto_put
```
**Symbols:**

```
ffffffff81a76b80-ffffffff81a76c22: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5e950)
Location: net/sched/cls_api.c:294
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_proto_put
```
**Symbols:**

```
ffffffff81a5e950-ffffffff81a5e9f2: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b17b20)
Location: net/sched/cls_api.c:294
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_proto_put
```
**Symbols:**

```
ffffffff81b17b20-ffffffff81b17bc2: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9f990)
Location: net/sched/cls_api.c:311
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81c9f990-ffffffff81c9fa43: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5bc40)
Location: net/sched/cls_api.c:313
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81e5bc40-ffffffff81e5bcf3: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb8440)
Location: net/sched/cls_api.c:415
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81eb8440-ffffffff81eb84f1: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7b510)
Location: net/sched/cls_api.c:415
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81f7b510-ffffffff81f7b5c1: tcf_proto_destroy (STB_LOCAL)
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
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c41f48)
Location: net/sched/cls_api.c:293
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_put
```
**Symbols:**

```
ffff800010c41f48-ffff800010c42004: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d53cf0)
Location: net/sched/cls_api.c:293
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_put
```
**Symbols:**

```
c0d53cf0-c0d53d9c: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3ded0)
Location: net/sched/cls_api.c:293
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_put
```
**Symbols:**

```
c000000000d3ded0-c000000000d3dfc0: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b179e)
Location: net/sched/cls_api.c:293
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffe0007b179e-ffffffe0007b183c: tcf_proto_destroy (STB_LOCAL)
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
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819351d0)
Location: net/sched/cls_api.c:293
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819351d0-ffffffff81935272: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818eecd0)
Location: net/sched/cls_api.c:293
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818eecd0-ffffffff818eed72: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81986360)
Location: net/sched/cls_api.c:293
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81986360-ffffffff81986402: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcf_proto_destroy(struct tcf_proto *tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9360)
Location: net/sched/cls_api.c:293
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819a9360-ffffffff819a9402: tcf_proto_destroy (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rtnl_held</code>
</li>
<li>
<b>Param reordered. </b>
<code>tp, extack</code> ➡️ <code>tp, rtnl_held, extack</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool sig_destroy</code>
</li>
<li>
<b>Param reordered. </b>
<code>tp, rtnl_held, extack</code> ➡️ <code>tp, rtnl_held, sig_destroy, extack</code>
</li>
</ul>
</details>
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
