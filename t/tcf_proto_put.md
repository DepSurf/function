# Function: <code>tcf_proto_put</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195eae0)
Location: net/sched/cls_api.c:232
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff8195eae0-ffffffff8195eb01: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81995410)
Location: net/sched/cls_api.c:304
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81995410-ffffffff81995439: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6e420)
Location: net/sched/cls_api.c:305
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81a6e420-ffffffff81a6e464: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a76c30)
Location: net/sched/cls_api.c:305
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81a76c30-ffffffff81a76c74: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5ea00)
Location: net/sched/cls_api.c:305
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81a5ea00-ffffffff81a5ea44: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b17bd0)
Location: net/sched/cls_api.c:305
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
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81b17bd0-ffffffff81b17c14: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9fa50)
Location: net/sched/cls_api.c:322
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81c9fa50-ffffffff81c9fabe: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5bd10)
Location: net/sched/cls_api.c:324
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81e5bd10-ffffffff81e5bd7e: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb8510)
Location: net/sched/cls_api.c:426
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81eb8510-ffffffff81eb857e: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7b5e0)
Location: net/sched/cls_api.c:426
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81f7b5e0-ffffffff81f7b64e: tcf_proto_put (STB_LOCAL)
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
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c42008)
Location: net/sched/cls_api.c:304
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffff800010c42008-ffff800010c42070: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d53d9c)
Location: net/sched/cls_api.c:304
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
c0d53d9c-c0d53de4: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3dfc0)
Location: net/sched/cls_api.c:304
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
c000000000d3dfc0-c000000000d3e004: tcf_proto_put (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffe0007b3f88)
Location: net/sched/cls_api.c:304
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81935280)
Location: net/sched/cls_api.c:304
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81935280-ffffffff819352a9: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818eed80)
Location: net/sched/cls_api.c:304
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff818eed80-ffffffff818eeda9: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81986410)
Location: net/sched/cls_api.c:304
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81986410-ffffffff81986439: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcf_proto_put(struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9410)
Location: net/sched/cls_api.c:304
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff819a9410-ffffffff819a9439: tcf_proto_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
