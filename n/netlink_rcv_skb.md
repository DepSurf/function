# Function: <code>netlink_rcv_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174ed80)
Location: net/netlink/af_netlink.c:2989
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
```
**Symbols:**

```
ffffffff8174ed80-ffffffff8174ee3d: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817bad50)
Location: net/netlink/af_netlink.c:2257
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
```
**Symbols:**

```
ffffffff817bad50-ffffffff817bae0d: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817ea6f0)
Location: net/netlink/af_netlink.c:2275
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
```
**Symbols:**

```
ffffffff817ea6f0-ffffffff817ea7ad: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8180a5e0)
Location: net/netlink/af_netlink.c:2372
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
```
**Symbols:**

```
ffffffff8180a5e0-ffffffff8180a70f: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81889510)
Location: net/netlink/af_netlink.c:2388
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
```
**Symbols:**

```
ffffffff81889510-ffffffff81889639: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818dcfa0)
Location: net/netlink/af_netlink.c:2429
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff818dcfa0-ffffffff818dd0c8: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81909970)
Location: net/netlink/af_netlink.c:2451
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff81909970-ffffffff81909a87: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8196ac70)
Location: net/netlink/af_netlink.c:2451
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff8196ac70-ffffffff8196ad87: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819a1710)
Location: net/netlink/af_netlink.c:2452
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff819a1710-ffffffff819a1827: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7b0d0)
Location: net/netlink/af_netlink.c:2443
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
```
**Symbols:**

```
ffffffff81a7b0d0-ffffffff81a7b1de: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a83f60)
Location: net/netlink/af_netlink.c:2468
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
```
**Symbols:**

```
ffffffff81a83f60-ffffffff81a84053: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6d0a0)
Location: net/netlink/af_netlink.c:2478
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
```
**Symbols:**

```
ffffffff81a6d0a0-ffffffff81a6d194: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b26710)
Location: net/netlink/af_netlink.c:2489
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
```
**Symbols:**

```
ffffffff81b26710-ffffffff81b26804: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81caf400)
Location: net/netlink/af_netlink.c:2475
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
```
**Symbols:**

```
ffffffff81caf400-ffffffff81caf502: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e6ca00)
Location: net/netlink/af_netlink.c:2548
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff81e6ca00-ffffffff81e6cb0b: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec8a60)
Location: net/netlink/af_netlink.c:2523
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff81ec8a60-ffffffff81ec8b6b: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f8bce0)
Location: net/netlink/af_netlink.c:2517
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff81f8bce0-ffffffff81f8bdeb: netlink_rcv_skb (STB_GLOBAL)
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
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4fd48)
Location: net/netlink/af_netlink.c:2452
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffff800010c4fd48-ffff800010c4fe60: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5ff60)
Location: net/netlink/af_netlink.c:2452
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
c0d5ff60-c0d60090: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4e8e0)
Location: net/netlink/af_netlink.c:2452
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
c000000000d4e8e0-c000000000d4ea78: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007bb89c)
Location: net/netlink/af_netlink.c:2452
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffe0007bb89c-ffffffe0007bb97c: netlink_rcv_skb (STB_GLOBAL)
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
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81941580)
Location: net/netlink/af_netlink.c:2452
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff81941580-ffffffff81941697: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818fb070)
Location: net/netlink/af_netlink.c:2452
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff818fb070-ffffffff818fb187: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81992710)
Location: net/netlink/af_netlink.c:2452
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - net/netfilter/nfnetlink.c:nfnetlink_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff81992710-ffffffff81992827: netlink_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netlink_rcv_skb(struct sk_buff *skb, int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b5200)
Location: net/netlink/af_netlink.c:2452
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/sock_diag.c:sock_diag_rcv
  - net/netlink/genetlink.c:genl_rcv
  - lib/kobject_uevent.c:uevent_net_rcv
```
**Symbols:**

```
ffffffff819b5200-ffffffff819b5317: netlink_rcv_skb (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>int (*cb)(struct sk_buff *, struct nlmsghdr *)</code> ➡️ <code>int (*cb)(struct sk_buff *, struct nlmsghdr *, struct netlink_ext_ack *)</code>
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
