# Function: <code>tcf_chain_tp_delete_empty</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1763
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff8195eb80-ffffffff8195ecc3: tcf_chain_tp_delete_empty (STB_LOCAL)
ffffffff81962cc1-ffffffff81962cd4: tcf_chain_tp_delete_empty.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81995500)
Location: net/sched/cls_api.c:1707
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81995500-ffffffff819955e5: tcf_chain_tp_delete_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6e7f0)
Location: net/sched/cls_api.c:1720
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a6e7f0-ffffffff81a6e8e6: tcf_chain_tp_delete_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a77000)
Location: net/sched/cls_api.c:1722
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a77000-ffffffff81a770f6: tcf_chain_tp_delete_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5eb10)
Location: net/sched/cls_api.c:1723
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a5eb10-ffffffff81a5ebf5: tcf_chain_tp_delete_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1721
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81b17ce0-ffffffff81b17dcf: tcf_chain_tp_delete_empty (STB_LOCAL)
ffffffff81d39154-ffffffff81d3916f: tcf_chain_tp_delete_empty.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1740
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81c9fe80-ffffffff81c9ff92: tcf_chain_tp_delete_empty (STB_LOCAL)
ffffffff81f05993-ffffffff81f059ae: tcf_chain_tp_delete_empty.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1742
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81e5bec0-ffffffff81e5bfd2: tcf_chain_tp_delete_empty (STB_LOCAL)
ffffffff820ad79d-ffffffff820ad7b8: tcf_chain_tp_delete_empty.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1890
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81eb8980-ffffffff81eb8a9c: tcf_chain_tp_delete_empty (STB_LOCAL)
ffffffff8212e995-ffffffff8212e9b0: tcf_chain_tp_delete_empty.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1940
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81f7ba50-ffffffff81f7bb6c: tcf_chain_tp_delete_empty (STB_LOCAL)
ffffffff82210739-ffffffff82210754: tcf_chain_tp_delete_empty.cold (STB_LOCAL)
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
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c42140)
Location: net/sched/cls_api.c:1707
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffff800010c42140-ffff800010c42270: tcf_chain_tp_delete_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d53edc)
Location: net/sched/cls_api.c:1707
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
c0d53edc-c0d53fec: tcf_chain_tp_delete_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3e130)
Location: net/sched/cls_api.c:1707
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
c000000000d3e130-c000000000d3e2d4: tcf_chain_tp_delete_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b190a)
Location: net/sched/cls_api.c:1707
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffe0007b190a-ffffffe0007b19fe: tcf_chain_tp_delete_empty (STB_LOCAL)
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
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81935370)
Location: net/sched/cls_api.c:1707
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81935370-ffffffff81935455: tcf_chain_tp_delete_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818eee70)
Location: net/sched/cls_api.c:1707
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818eee70-ffffffff818eef55: tcf_chain_tp_delete_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81986500)
Location: net/sched/cls_api.c:1707
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81986500-ffffffff819865e5: tcf_chain_tp_delete_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9500)
Location: net/sched/cls_api.c:1707
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819a9500-ffffffff819a95e5: tcf_chain_tp_delete_empty (STB_LOCAL)
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
