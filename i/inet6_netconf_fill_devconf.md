# Function: <code>inet6_netconf_fill_devconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817ccc40)
Location: net/ipv6/addrconf.c:491
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff817ccc40-ffffffff817cce47: inet6_netconf_fill_devconf.constprop.55 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81839680)
Location: net/ipv6/addrconf.c:495
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81839680-ffffffff818398d2: inet6_netconf_fill_devconf.constprop.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186b0a0)
Location: net/ipv6/addrconf.c:522
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff8186b0a0-ffffffff8186b2f2: inet6_netconf_fill_devconf.constprop.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188f5a0)
Location: net/ipv6/addrconf.c:529
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff8188f5a0-ffffffff8188f798: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81910e80)
Location: net/ipv6/addrconf.c:529
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81910e80-ffffffff81911078: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81967d40)
Location: net/ipv6/addrconf.c:518
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81967d40-ffffffff81967f40: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199db30)
Location: net/ipv6/addrconf.c:516
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff8199db30-ffffffff8199dd2d: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81a09b50-ffffffff81a09d49: inet6_netconf_fill_devconf (STB_LOCAL)
ffffffff81a112cd-ffffffff81a112e8: inet6_netconf_fill_devconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a40840)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81a40840-ffffffff81a40a40: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b36290)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81b36290-ffffffff81b3648f: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b44710)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81b44710-ffffffff81b4490f: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b323b0)
Location: net/ipv6/addrconf.c:515
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81b323b0-ffffffff81b325b0: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf86f0)
Location: net/ipv6/addrconf.c:523
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81bf86f0-ffffffff81bf88f0: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d91bf0)
Location: net/ipv6/addrconf.c:522
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81d91bf0-ffffffff81d91dfc: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f602e0)
Location: net/ipv6/addrconf.c:522
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81f602e0-ffffffff81f604ec: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc0110)
Location: net/ipv6/addrconf.c:521
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81fc0110-ffffffff81fc031c: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208d5c0)
Location: net/ipv6/addrconf.c:525
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff8208d5c0-ffffffff8208d7cc: inet6_netconf_fill_devconf (STB_LOCAL)
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
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d01a88)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffff800010d01a88-ffff800010d01c8c: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e09c78)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
c0e09c78-c0e09e90: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2bb90)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
c000000000e2bb90-c000000000e2be60: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084b7ea)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffe00084b7ea-ffffffe00084b9bc: inet6_netconf_fill_devconf (STB_LOCAL)
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
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819dfed0)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff819dfed0-ffffffff819e00d0: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199cc90)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff8199cc90-ffffffff8199ce90: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4a950)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81a4a950-ffffffff81a4ab50: inet6_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet6_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv6_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a56880)
Location: net/ipv6/addrconf.c:513
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81a56880-ffffffff81a56a80: inet6_netconf_fill_devconf (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
