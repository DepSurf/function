# Function: <code>inet_netconf_get_devconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81790460)
Location: net/ipv4/devinet.c:1832
Inline: False
```
**Symbols:**

```
ffffffff81790460-ffffffff817905e3: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817fd8e0)
Location: net/ipv4/devinet.c:1864
Inline: False
```
**Symbols:**

```
ffffffff817fd8e0-ffffffff817fda63: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182e840)
Location: net/ipv4/devinet.c:1864
Inline: False
```
**Symbols:**

```
ffffffff8182e840-ffffffff8182e9c3: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8184f980)
Location: net/ipv4/devinet.c:1908
Inline: False
```
**Symbols:**

```
ffffffff8184f980-ffffffff8184faff: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818cf5b0)
Location: net/ipv4/devinet.c:1917
Inline: False
```
**Symbols:**

```
ffffffff818cf5b0-ffffffff818cf72f: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81925ff0)
Location: net/ipv4/devinet.c:1927
Inline: False
```
**Symbols:**

```
ffffffff81925ff0-ffffffff81926168: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81955010)
Location: net/ipv4/devinet.c:2066
Inline: False
```
**Symbols:**

```
ffffffff81955010-ffffffff8195519b: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:2158
Inline: False
```
**Symbols:**

```
ffffffff819b9800-ffffffff819b9a3f: inet_netconf_get_devconf (STB_LOCAL)
ffffffff819bcc65-ffffffff819bcc78: inet_netconf_get_devconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f0500)
Location: net/ipv4/devinet.c:2153
Inline: False
```
**Symbols:**

```
ffffffff819f0500-ffffffff819f072f: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ade470)
Location: net/ipv4/devinet.c:2159
Inline: False
```
**Symbols:**

```
ffffffff81ade470-ffffffff81ade69d: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aeb250)
Location: net/ipv4/devinet.c:2158
Inline: False
```
**Symbols:**

```
ffffffff81aeb250-ffffffff81aeb47d: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad7f70)
Location: net/ipv4/devinet.c:2159
Inline: False
```
**Symbols:**

```
ffffffff81ad7f70-ffffffff81ad81c1: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81b96dd0)
Location: net/ipv4/devinet.c:2160
Inline: False
```
**Symbols:**

```
ffffffff81b96dd0-ffffffff81b97021: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81d28990)
Location: net/ipv4/devinet.c:2167
Inline: False
```
**Symbols:**

```
ffffffff81d28990-ffffffff81d28c00: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ef03e0)
Location: net/ipv4/devinet.c:2168
Inline: False
```
**Symbols:**

```
ffffffff81ef03e0-ffffffff81ef0650: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f4fe30)
Location: net/ipv4/devinet.c:2171
Inline: False
```
**Symbols:**

```
ffffffff81f4fe30-ffffffff81f500a5: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff82015fe0)
Location: net/ipv4/devinet.c:2202
Inline: False
```
**Symbols:**

```
ffffffff82015fe0-ffffffff82016255: inet_netconf_get_devconf (STB_LOCAL)
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
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca6340)
Location: net/ipv4/devinet.c:2153
Inline: False
```
**Symbols:**

```
ffff800010ca6340-ffff800010ca65ac: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db2e28)
Location: net/ipv4/devinet.c:2153
Inline: False
```
**Symbols:**

```
c0db2e28-c0db308c: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbaaf0)
Location: net/ipv4/devinet.c:2153
Inline: False
```
**Symbols:**

```
c000000000dbaaf0-c000000000dbae00: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe000801ba2)
Location: net/ipv4/devinet.c:2153
Inline: False
```
**Symbols:**

```
ffffffe000801ba2-ffffffe000801d52: inet_netconf_get_devconf (STB_LOCAL)
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
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819902a0)
Location: net/ipv4/devinet.c:2153
Inline: False
```
**Symbols:**

```
ffffffff819902a0-ffffffff819904cf: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81949d60)
Location: net/ipv4/devinet.c:2153
Inline: False
```
**Symbols:**

```
ffffffff81949d60-ffffffff81949f8f: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fab40)
Location: net/ipv4/devinet.c:2153
Inline: False
```
**Symbols:**

```
ffffffff819fab40-ffffffff819fad6f: inet_netconf_get_devconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet_netconf_get_devconf(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a04e90)
Location: net/ipv4/devinet.c:2153
Inline: False
```
**Symbols:**

```
ffffffff81a04e90-ffffffff81a050bf: inet_netconf_get_devconf (STB_LOCAL)
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
