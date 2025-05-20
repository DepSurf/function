# Function: <code>inet_netconf_fill_devconf</code>

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
In net/ipv4/devinet.c (ffffffff81790200)
Location: net/ipv4/devinet.c:1750
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81790200-ffffffff81790452: inet_netconf_fill_devconf.constprop.22 (STB_LOCAL)
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
In net/ipv4/devinet.c (ffffffff817fd640)
Location: net/ipv4/devinet.c:1779
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff817fd640-ffffffff817fd8e0: inet_netconf_fill_devconf.constprop.24 (STB_LOCAL)
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
In net/ipv4/devinet.c (ffffffff8182e5a0)
Location: net/ipv4/devinet.c:1779
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff8182e5a0-ffffffff8182e840: inet_netconf_fill_devconf.constprop.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8184f1c0)
Location: net/ipv4/devinet.c:1819
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff8184f1c0-ffffffff8184f42a: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818cedf0)
Location: net/ipv4/devinet.c:1828
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff818cedf0-ffffffff818cf05a: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81925bb0)
Location: net/ipv4/devinet.c:1838
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81925bb0-ffffffff81925df1: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81954b40)
Location: net/ipv4/devinet.c:1973
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81954b40-ffffffff81954dbf: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:2026
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff819b8ab0-ffffffff819b8d2a: inet_netconf_fill_devconf (STB_LOCAL)
ffffffff819bcc29-ffffffff819bcc43: inet_netconf_fill_devconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819ef7b0)
Location: net/ipv4/devinet.c:2021
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff819ef7b0-ffffffff819efa31: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81addbf0)
Location: net/ipv4/devinet.c:2027
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81addbf0-ffffffff81adde78: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aea9d0)
Location: net/ipv4/devinet.c:2026
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81aea9d0-ffffffff81aeac58: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad6110)
Location: net/ipv4/devinet.c:2027
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81ad6110-ffffffff81ad6397: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81b94e40)
Location: net/ipv4/devinet.c:2028
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81b94e40-ffffffff81b950c7: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81d26aa0)
Location: net/ipv4/devinet.c:2035
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81d26aa0-ffffffff81d26d26: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81eee440)
Location: net/ipv4/devinet.c:2036
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81eee440-ffffffff81eee6c6: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f4de00)
Location: net/ipv4/devinet.c:2039
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81f4de00-ffffffff81f4e084: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff82013f30)
Location: net/ipv4/devinet.c:2070
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff82013f30-ffffffff820141b4: inet_netconf_fill_devconf (STB_LOCAL)
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
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca5628)
Location: net/ipv4/devinet.c:2021
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffff800010ca5628-ffff800010ca5898: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db1f70)
Location: net/ipv4/devinet.c:2021
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
c0db1f70-c0db2204: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000db94d0)
Location: net/ipv4/devinet.c:2021
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
c000000000db94d0-c000000000db9850: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe000800f18)
Location: net/ipv4/devinet.c:2021
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffe000800f18-ffffffe000801170: inet_netconf_fill_devconf (STB_LOCAL)
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
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8198f550)
Location: net/ipv4/devinet.c:2021
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff8198f550-ffffffff8198f7d1: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81949010)
Location: net/ipv4/devinet.c:2021
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81949010-ffffffff81949291: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f9df0)
Location: net/ipv4/devinet.c:2021
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff819f9df0-ffffffff819fa071: inet_netconf_fill_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet_netconf_fill_devconf(struct sk_buff *skb, int ifindex, struct ipv4_devconf *devconf, u32 portid, u32 seq, int event, unsigned int flags, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a04100)
Location: net/ipv4/devinet.c:2021
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
```
**Symbols:**

```
ffffffff81a04100-ffffffff81a04381: inet_netconf_fill_devconf (STB_LOCAL)
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
