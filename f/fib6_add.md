# Function: <code>fib6_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct rt6_info *rt, struct nl_info *info, struct mx6_config *mxc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817db020)
Location: net/ipv6/ip6_fib.c:943
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff817db020-ffffffff817dba82: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct rt6_info *rt, struct nl_info *info, struct mx6_config *mxc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81849030)
Location: net/ipv6/ip6_fib.c:945
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff81849030-ffffffff81849a25: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct rt6_info *rt, struct nl_info *info, struct mx6_config *mxc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8187ae80)
Location: net/ipv6/ip6_fib.c:951
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff8187ae80-ffffffff8187b8ba: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct rt6_info *rt, struct nl_info *info, struct mx6_config *mxc, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818a0810)
Location: net/ipv6/ip6_fib.c:986
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff818a0810-ffffffff818a12b6: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct rt6_info *rt, struct nl_info *info, struct mx6_config *mxc, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81923040)
Location: net/ipv6/ip6_fib.c:1132
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff81923040-ffffffff81923be0: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1199
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff8197c6b7-ffffffff8197c71d: fib6_add.cold.37 (STB_LOCAL)
ffffffff8197b4d0-ffffffff8197bf99: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1233
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff819b23d7-ffffffff819b243d: fib6_add.cold.38 (STB_LOCAL)
ffffffff819b11b0-ffffffff819b1c79: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1302
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff81a209fa-ffffffff81a20a3f: fib6_add.cold (STB_LOCAL)
ffffffff81a1fd80-ffffffff81a20188: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1303
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff81a574f6-ffffffff81a57515: fib6_add.cold (STB_LOCAL)
ffffffff81a569e0-ffffffff81a56df3: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1368
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_ins_rt
```
**Symbols:**

```
ffffffff81b4f666-ffffffff81b4f681: fib6_add.cold (STB_LOCAL)
ffffffff81b4eb90-ffffffff81b4f124: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1371
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_ins_rt
```
**Symbols:**

```
ffffffff81c32ddd-ffffffff81c32df8: fib6_add.cold (STB_LOCAL)
ffffffff81b5d810-ffffffff81b5dda4: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1372
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_ins_rt
```
**Symbols:**

```
ffffffff81c250de-ffffffff81c250f9: fib6_add.cold (STB_LOCAL)
ffffffff81b4ba70-ffffffff81b4c01d: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1374
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_ins_rt
```
**Symbols:**

```
ffffffff81d40369-ffffffff81d40380: fib6_add.cold (STB_LOCAL)
ffffffff81c12dd0-ffffffff81c1331f: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1375
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_ins_rt
```
**Symbols:**

```
ffffffff81f0ccf0-ffffffff81f0cd07: fib6_add.cold (STB_LOCAL)
ffffffff81dae360-ffffffff81dae8d2: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7de80)
Location: net/ipv6/ip6_fib.c:1374
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_ins_rt
```
**Symbols:**

```
ffffffff81f7de80-ffffffff81f7e3dd: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fde090)
Location: net/ipv6/ip6_fib.c:1374
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_ins_rt
```
**Symbols:**

```
ffffffff81fde090-ffffffff81fde5e4: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820abc10)
Location: net/ipv6/ip6_fib.c:1374
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_ins_rt
```
**Symbols:**

```
ffffffff820abc10-ffffffff820ac162: fib6_add (STB_GLOBAL)
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
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1b528)
Location: net/ipv6/ip6_fib.c:1303
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffff800010d1b528-ffff800010d1b8bc: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e20944)
Location: net/ipv6/ip6_fib.c:1303
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
c0e20944-c0e20d28: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e49b60)
Location: net/ipv6/ip6_fib.c:1303
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
c000000000e49b60-c000000000e4a158: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085f622)
Location: net/ipv6/ip6_fib.c:1303
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffe00085f622-ffffffe00085f97a: fib6_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1303
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff819f6b86-ffffffff819f6ba5: fib6_add.cold (STB_LOCAL)
ffffffff819f6070-ffffffff819f6483: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1303
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff819b3946-ffffffff819b3965: fib6_add.cold (STB_LOCAL)
ffffffff819b2e30-ffffffff819b3243: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1303
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff81a61606-ffffffff81a61625: fib6_add.cold (STB_LOCAL)
ffffffff81a60af0-ffffffff81a60f03: fib6_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fib6_add(struct fib6_node *root, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1303
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_ins_rt
```
**Symbols:**

```
ffffffff81a6dac6-ffffffff81a6dae5: fib6_add.cold (STB_LOCAL)
ffffffff81a6cfb0-ffffffff81a6d3c3: fib6_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mx6_config *mxc</code>
</li>
<li>
<b>Param reordered. </b>
<code>root, rt, info, mxc, extack</code> ➡️ <code>root, rt, info, extack</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt6_info *rt</code> ➡️ <code>struct fib6_info *rt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
