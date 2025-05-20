# Function: <code>fib6_add_rt2node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817db165)
Location: net/ipv6/ip6_fib.c:732
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81849179)
Location: net/ipv6/ip6_fib.c:734
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8187afca)
Location: net/ipv6/ip6_fib.c:734
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818a0946)
Location: net/ipv6/ip6_fib.c:763
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81923210)
Location: net/ipv6/ip6_fib.c:877
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8197b672)
Location: net/ipv6/ip6_fib.c:934
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b1352)
Location: net/ipv6/ip6_fib.c:968
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1009
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a1f4a0-ffffffff81a1fca2: fib6_add_rt2node (STB_LOCAL)
ffffffff81a209ae-ffffffff81a209fa: fib6_add_rt2node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1009
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a56120-ffffffff81a5690b: fib6_add_rt2node (STB_LOCAL)
ffffffff81a574bf-ffffffff81a574f6: fib6_add_rt2node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1060
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81b4dc40-ffffffff81b4e62f: fib6_add_rt2node (STB_LOCAL)
ffffffff81b4f627-ffffffff81b4f666: fib6_add_rt2node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1063
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81b5c8b0-ffffffff81b5d29a: fib6_add_rt2node (STB_LOCAL)
ffffffff81c32d9e-ffffffff81c32ddd: fib6_add_rt2node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1064
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81b4aab0-ffffffff81b4b4d5: fib6_add_rt2node (STB_LOCAL)
ffffffff81c25099-ffffffff81c250de: fib6_add_rt2node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1066
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81c11df0-ffffffff81c12815: fib6_add_rt2node (STB_LOCAL)
ffffffff81d40324-ffffffff81d40369: fib6_add_rt2node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1067
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81dad2c0-ffffffff81dadd13: fib6_add_rt2node (STB_LOCAL)
ffffffff81f0cca3-ffffffff81f0ccf0: fib6_add_rt2node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7cd30)
Location: net/ipv6/ip6_fib.c:1066
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81f7cd30-ffffffff81f7d7c7: fib6_add_rt2node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fdcf40)
Location: net/ipv6/ip6_fib.c:1066
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81fdcf40-ffffffff81fdd9d4: fib6_add_rt2node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820ab080)
Location: net/ipv6/ip6_fib.c:1066
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff820ab080-ffffffff820abad3: fib6_add_rt2node (STB_LOCAL)
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
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1acd8)
Location: net/ipv6/ip6_fib.c:1009
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffff800010d1acd8-ffff800010d1b3c0: fib6_add_rt2node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e20078)
Location: net/ipv6/ip6_fib.c:1009
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
c0e20078-c0e20860: fib6_add_rt2node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e49080)
Location: net/ipv6/ip6_fib.c:1009
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
c000000000e49080-c000000000e499b8: fib6_add_rt2node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085ef48)
Location: net/ipv6/ip6_fib.c:1009
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffe00085ef48-ffffffe00085f51c: fib6_add_rt2node (STB_LOCAL)
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
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1009
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819f57b0-ffffffff819f5f9b: fib6_add_rt2node (STB_LOCAL)
ffffffff819f6b4f-ffffffff819f6b86: fib6_add_rt2node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1009
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819b2570-ffffffff819b2d5b: fib6_add_rt2node (STB_LOCAL)
ffffffff819b390f-ffffffff819b3946: fib6_add_rt2node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1009
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a60230-ffffffff81a60a1b: fib6_add_rt2node (STB_LOCAL)
ffffffff81a615cf-ffffffff81a61606: fib6_add_rt2node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fib6_add_rt2node(struct fib6_node *fn, struct fib6_info *rt, struct nl_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:1009
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a6c6f0-ffffffff81a6cedb: fib6_add_rt2node (STB_LOCAL)
ffffffff81a6da8f-ffffffff81a6dac6: fib6_add_rt2node.cold (STB_LOCAL)
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
