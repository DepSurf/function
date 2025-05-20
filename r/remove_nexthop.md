# Function: <code>remove_nexthop</code>

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
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d5140)
Location: net/ipv4/nexthop.c:808
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
**Symbols:**

```
ffffffff819d5140-ffffffff819d51c1: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0bca0)
Location: net/ipv4/nexthop.c:810
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
**Symbols:**

```
ffffffff81a0bca0-ffffffff81a0bd21: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afce06)
Location: net/ipv4/nexthop.c:906
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
Direct callers:
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81afcb10-ffffffff81afcbb4: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0ac06)
Location: net/ipv4/nexthop.c:1043
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
Direct callers:
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81b0a5a0-ffffffff81b0a651: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af8496)
Location: net/ipv4/nexthop.c:1882
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
Direct callers:
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81af8100-ffffffff81af81b1: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb9636)
Location: net/ipv4/nexthop.c:1882
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
Direct callers:
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81bb8e80-ffffffff81bb8f31: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4d607)
Location: net/ipv4/nexthop.c:1883
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
Direct callers:
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81d4cdd0-ffffffff81d4ceb9: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f16f07)
Location: net/ipv4/nexthop.c:1883
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
Direct callers:
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81f16680-ffffffff81f16769: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f76be7)
Location: net/ipv4/nexthop.c:1883
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
Direct callers:
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff81f76330-ffffffff81f76419: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203d3b7)
Location: net/ipv4/nexthop.c:1906
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
Direct callers:
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
  - net/ipv4/nexthop.c:remove_nh_grp_entry
```
**Symbols:**

```
ffffffff8203cb00-ffffffff8203cbe9: remove_nexthop (STB_LOCAL)
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
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc4fe0)
Location: net/ipv4/nexthop.c:810
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
**Symbols:**

```
ffff800010cc4fe0-ffff800010cc5084: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd0a80)
Location: net/ipv4/nexthop.c:810
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
**Symbols:**

```
c0dd0a80-c0dd0b08: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de1360)
Location: net/ipv4/nexthop.c:810
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
**Symbols:**

```
c000000000de1360-c000000000de1460: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe0008192c2)
Location: net/ipv4/nexthop.c:810
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
**Symbols:**

```
ffffffe0008192c2-ffffffe00081935e: remove_nexthop (STB_LOCAL)
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
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819aba40)
Location: net/ipv4/nexthop.c:810
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
**Symbols:**

```
ffffffff819aba40-ffffffff819abac1: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81965500)
Location: net/ipv4/nexthop.c:810
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
**Symbols:**

```
ffffffff81965500-ffffffff81965581: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a162e0)
Location: net/ipv4/nexthop.c:810
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
**Symbols:**

```
ffffffff81a162e0-ffffffff81a16361: remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a20d20)
Location: net/ipv4/nexthop.c:810
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_del_nexthop
  - net/ipv4/nexthop.c:nexthop_flush_dev
```
**Symbols:**

```
ffffffff81a20d20-ffffffff81a20da1: remove_nexthop (STB_LOCAL)
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
