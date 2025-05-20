# Function: <code>skb_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81707350)
Location: net/core/skbuff.c:1087
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - net/core/skbuff.c:skb_cow_data
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/ipv4/tcp_output.c:tcp_send_synack
```
**Symbols:**

```
ffffffff81707350-ffffffff817073fd: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176d600)
Location: net/core/skbuff.c:1092
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff8176d600-ffffffff8176d6a5: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179a790)
Location: net/core/skbuff.c:1092
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff8179a790-ffffffff8179a835: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817ba730)
Location: net/core/skbuff.c:1094
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff817ba730-ffffffff817ba7d5: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81832b20)
Location: net/core/skbuff.c:1338
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff81832b20-ffffffff81832bc5: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187d040)
Location: net/core/skbuff.c:1340
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff8187d040-ffffffff8187d0e3: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189dc50)
Location: net/core/skbuff.c:1350
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff8189dc50-ffffffff8189dce7: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e8410)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff818e8410-ffffffff818e84ac: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191a650)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff8191a650-ffffffff8191a6ec: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ecb70)
Location: net/core/skbuff.c:1508
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff819ecb70-ffffffff819ecc0c: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ec830)
Location: net/core/skbuff.c:1519
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff819ec830-ffffffff819ec8cc: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d2d20)
Location: net/core/skbuff.c:1561
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/core/selftests.c:net_test_loopback_validate
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff819d2d20-ffffffff819d2dbb: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1582
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/core/selftests.c:net_test_loopback_validate
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff81d3519b-ffffffff81d351ae: skb_copy.cold (STB_LOCAL)
ffffffff81a829a0-ffffffff81a82a65: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1576
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - net/core/skbuff.c:skb_cow_data
  - net/core/selftests.c:net_test_loopback_validate
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff81f016f8-ffffffff81f0170b: skb_copy.cold (STB_LOCAL)
ffffffff81bf7390-ffffffff81bf7459: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da63d0)
Location: net/core/skbuff.c:1775
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - net/core/skbuff.c:skb_cow_data
  - net/core/selftests.c:net_test_loopback_validate
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff81da63d0-ffffffff81da64a8: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e154c0)
Location: net/core/skbuff.c:1927
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - net/core/skbuff.c:skb_cow_data
  - net/core/selftests.c:net_test_loopback_validate
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff81e154c0-ffffffff81e1559f: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed2860)
Location: net/core/skbuff.c:2015
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - net/core/skbuff.c:skb_cow_data
  - net/core/selftests.c:net_test_loopback_validate
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff81ed2860-ffffffff81ed293f: skb_copy (STB_GLOBAL)
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
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb4978)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffff800010bb4978-ffff800010bb4a2c: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd14d4)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
c0cd14d4-c0cd1580: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8b420)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
c000000000c8b420-c000000000c8b500: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe00074397c)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffe00074397c-ffffffe000743a1c: skb_copy (STB_GLOBAL)
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
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ba650)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff818ba650-ffffffff818ba6ec: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818745a0)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff818745a0-ffffffff8187463c: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190b650)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff8190b650-ffffffff8190b6ec: skb_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *skb_copy(const struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192c770)
Location: net/core/skbuff.c:1509
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_cow_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
**Symbols:**

```
ffffffff8192c770-ffffffff8192c80c: skb_copy (STB_GLOBAL)
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
