# Function: <code>rtnl_create_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172a380)
Location: net/core/rtnetlink.c:2088
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff8172a380-ffffffff8172a543: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81793dc0)
Location: net/core/rtnetlink.c:2282
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff81793dc0-ffffffff81793f8c: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c1640)
Location: net/core/rtnetlink.c:2355
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff817c1640-ffffffff817c180c: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817dfe10)
Location: net/core/rtnetlink.c:2434
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff817dfe10-ffffffff817dffc7: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185a6e0)
Location: net/core/rtnetlink.c:2635
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff8185a6e0-ffffffff8185a89d: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a5f70)
Location: net/core/rtnetlink.c:2772
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff818a5f70-ffffffff818a6158: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c9520)
Location: net/core/rtnetlink.c:2890
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff818c9520-ffffffff818c97bd: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81916500)
Location: net/core/rtnetlink.c:2901
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff81916500-ffffffff81916795: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81948b30)
Location: net/core/rtnetlink.c:2923
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff81948b30-ffffffff81948ded: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18940)
Location: net/core/rtnetlink.c:3037
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff81a18940-ffffffff81a18c28: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a189f0)
Location: net/core/rtnetlink.c:3141
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff81a189f0-ffffffff81a18cd8: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819ff8e0)
Location: net/core/rtnetlink.c:3139
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff819ff8e0-ffffffff819ffbb5: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab1bb0)
Location: net/core/rtnetlink.c:3149
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff81ab1bb0-ffffffff81ab1ecd: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2ae90)
Location: net/core/rtnetlink.c:3205
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - net/core/rtnetlink.c:rtnl_newlink_create
```
**Symbols:**

```
ffffffff81c2ae90-ffffffff81c2b1d0: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3247
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - net/core/rtnetlink.c:rtnl_newlink_create
```
**Symbols:**

```
ffffffff820abe6d-ffffffff820abe82: rtnl_create_link.cold (STB_LOCAL)
ffffffff81dde7d0-ffffffff81ddeb67: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3313
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - net/core/rtnetlink.c:rtnl_newlink_create
```
**Symbols:**

```
ffffffff8212d5c4-ffffffff8212d5d9: rtnl_create_link.cold (STB_LOCAL)
ffffffff81e4f820-ffffffff81e4fc43: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3345
Inline: False
Direct callers:
  - drivers/net/netkit.c:netkit_new_link
  - net/core/rtnetlink.c:rtnl_newlink_create
```
**Symbols:**

```
ffffffff8220f311-ffffffff8220f326: rtnl_create_link.cold (STB_LOCAL)
ffffffff81f0e860-ffffffff81f0ec73: rtnl_create_link (STB_GLOBAL)
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
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bebec8)
Location: net/core/rtnetlink.c:2923
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffff800010bebec8-ffff800010bec15c: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d031a0)
Location: net/core/rtnetlink.c:2923
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
c0d031a0-c0d03414: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccd240)
Location: net/core/rtnetlink.c:2923
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
c000000000ccd240-c000000000ccd640: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076e064)
Location: net/core/rtnetlink.c:2923
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffe00076e064-ffffffe00076e220: rtnl_create_link (STB_GLOBAL)
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
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e8b00)
Location: net/core/rtnetlink.c:2923
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff818e8b00-ffffffff818e8dbd: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a2940)
Location: net/core/rtnetlink.c:2923
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_dev_create
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff818a2940-ffffffff818a2bfd: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81939b30)
Location: net/core/rtnetlink.c:2923
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff81939b30-ffffffff81939ded: rtnl_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct net_device *rtnl_create_link(struct net *net, const char *ifname, unsigned char name_assign_type, const struct rtnl_link_ops *ops, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195b210)
Location: net/core/rtnetlink.c:2923
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff8195b210-ffffffff8195b4cd: rtnl_create_link (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
