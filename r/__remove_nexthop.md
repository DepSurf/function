# Function: <code>__remove_nexthop</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d526d)
Location: net/ipv4/nexthop.c:790
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff819d51d0-ffffffff819d5539: __remove_nexthop (STB_LOCAL)
ffffffff819d5fa5-ffffffff819d5fd3: __remove_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0bd30)
Location: net/ipv4/nexthop.c:792
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff81a0bd30-ffffffff81a0c0a8: __remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afca20)
Location: net/ipv4/nexthop.c:888
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:nexthop_add
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81afca20-ffffffff81afcb0f: __remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0a8a0)
Location: net/ipv4/nexthop.c:1025
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81b0a8a0-ffffffff81b0a98f: __remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af7f10)
Location: net/ipv4/nexthop.c:1864
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81af7f10-ffffffff81af80f8: __remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb8d4a)
Location: net/ipv4/nexthop.c:1864
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81bb8c70-ffffffff81bb8e7d: __remove_nexthop (STB_LOCAL)
ffffffff81d3e581-ffffffff81d3e5ab: __remove_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4cc72)
Location: net/ipv4/nexthop.c:1865
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81d4cb90-ffffffff81d4cdc8: __remove_nexthop (STB_LOCAL)
ffffffff81f0aeb8-ffffffff81f0aee2: __remove_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f16512)
Location: net/ipv4/nexthop.c:1865
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81f16430-ffffffff81f16668: __remove_nexthop (STB_LOCAL)
ffffffff820b274e-ffffffff820b2778: __remove_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f761c2)
Location: net/ipv4/nexthop.c:1865
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81f760e0-ffffffff81f76318: __remove_nexthop (STB_LOCAL)
ffffffff82133906-ffffffff82133930: __remove_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203c992)
Location: net/ipv4/nexthop.c:1888
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff8203c8b0-ffffffff8203cae8: __remove_nexthop (STB_LOCAL)
ffffffff82215312-ffffffff8221533c: __remove_nexthop.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc5088)
Location: net/ipv4/nexthop.c:792
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffff800010cc5088-ffff800010cc542c: __remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd0b08)
Location: net/ipv4/nexthop.c:792
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
c0dd0b08-c0dd0e70: __remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de1460)
Location: net/ipv4/nexthop.c:792
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
c000000000de1460-c000000000de19b8: __remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe000818fb0)
Location: net/ipv4/nexthop.c:792
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffe000818fb0-ffffffe0008192c2: __remove_nexthop (STB_LOCAL)
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
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819abad0)
Location: net/ipv4/nexthop.c:792
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff819abad0-ffffffff819abe48: __remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81965590)
Location: net/ipv4/nexthop.c:792
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff81965590-ffffffff81965908: __remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a16370)
Location: net/ipv4/nexthop.c:792
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff81a16370-ffffffff81a166e8: __remove_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __remove_nexthop(struct net *net, struct nexthop *nh, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a20db0)
Location: net/ipv4/nexthop.c:792
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
**Symbols:**

```
ffffffff81a20db0-ffffffff81a21128: __remove_nexthop (STB_LOCAL)
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
