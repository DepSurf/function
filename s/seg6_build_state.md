# Function: <code>seg6_build_state</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int seg6_build_state(struct net_device *dev, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff818a3f10)
Location: net/ipv6/seg6_iptunnel.c:306
Inline: False
```
**Symbols:**

```
ffffffff818a3f10-ffffffff818a4061: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca480)
Location: net/ipv6/seg6_iptunnel.c:327
Inline: False
```
**Symbols:**

```
ffffffff818ca480-ffffffff818ca5d5: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff8194dc10)
Location: net/ipv6/seg6_iptunnel.c:361
Inline: False
```
**Symbols:**

```
ffffffff8194dc10-ffffffff8194dda9: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff819a6e90)
Location: net/ipv6/seg6_iptunnel.c:381
Inline: False
```
**Symbols:**

```
ffffffff819a6e90-ffffffff819a702c: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff819dd9f0)
Location: net/ipv6/seg6_iptunnel.c:384
Inline: False
```
**Symbols:**

```
ffffffff819dd9f0-ffffffff819ddb8c: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c560)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
ffffffff81a4c560-ffffffff81a4c701: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83130)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
ffffffff81a83130-ffffffff81a832d1: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seg6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7dfd0)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
ffffffff81b7dfd0-ffffffff81b7e175: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seg6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8cfe0)
Location: net/ipv6/seg6_iptunnel.c:396
Inline: False
```
**Symbols:**

```
ffffffff81b8cfe0-ffffffff81b8d185: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seg6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7be90)
Location: net/ipv6/seg6_iptunnel.c:396
Inline: False
```
**Symbols:**

```
ffffffff81b7be90-ffffffff81b7c035: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seg6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81c46d50)
Location: net/ipv6/seg6_iptunnel.c:472
Inline: False
```
**Symbols:**

```
ffffffff81c46d50-ffffffff81c46ef5: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seg6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6050)
Location: net/ipv6/seg6_iptunnel.c:475
Inline: False
```
**Symbols:**

```
ffffffff81de6050-ffffffff81de6210: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seg6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb89f0)
Location: net/ipv6/seg6_iptunnel.c:607
Inline: False
```
**Symbols:**

```
ffffffff81fb89f0-ffffffff81fb8bb8: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seg6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff82019150)
Location: net/ipv6/seg6_iptunnel.c:606
Inline: False
```
**Symbols:**

```
ffffffff82019150-ffffffff8201931c: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seg6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8120)
Location: net/ipv6/seg6_iptunnel.c:606
Inline: False
```
**Symbols:**

```
ffffffff820e8120-ffffffff820e82f0: seg6_build_state (STB_LOCAL)
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
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffff800010d4ef38)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
ffff800010d4ef38-ffff800010d4f100: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (c0e4fcc4)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
c0e4fcc4-c0e4fe6c: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (c000000000e86240)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
c000000000e86240-c000000000e864dc: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffe0008877c4)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
ffffffe0008877c4-ffffffe00088791a: seg6_build_state (STB_LOCAL)
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
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81a227c0)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
ffffffff81a227c0-ffffffff81a22961: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff819df580)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
ffffffff819df580-ffffffff819df721: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d240)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
ffffffff81a8d240-ffffffff81a8d3e1: seg6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seg6_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81a99f30)
Location: net/ipv6/seg6_iptunnel.c:379
Inline: False
```
**Symbols:**

```
ffffffff81a99f30-ffffffff81a9a0d1: seg6_build_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, nla, family, cfg, ts</code> ➡️ <code>nla, family, cfg, ts, extack</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>nla, family, cfg, ts, extack</code> ➡️ <code>net, nla, family, cfg, ts, extack</code>
</li>
</ul>
</details>
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
