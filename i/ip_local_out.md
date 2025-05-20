# Function: <code>ip_local_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175e200)
Location: net/ipv4/ip_output.c:110
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff8175e200-ffffffff8175e23c: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817ca440)
Location: net/ipv4/ip_output.c:106
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff817ca440-ffffffff817ca47c: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817fa0c0)
Location: net/ipv4/ip_output.c:118
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff817fa0c0-ffffffff817fa0fc: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8181a4c0)
Location: net/ipv4/ip_output.c:118
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff8181a4c0-ffffffff8181a4fc: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81899490)
Location: net/ipv4/ip_output.c:118
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff81899490-ffffffff818994d2: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818ed8e0)
Location: net/ipv4/ip_output.c:118
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff818ed8e0-ffffffff818ed922: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191b090)
Location: net/ipv4/ip_output.c:118
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff8191b090-ffffffff8191b0d2: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197d330)
Location: net/ipv4/ip_output.c:119
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff8197d330-ffffffff8197d375: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b3ce0)
Location: net/ipv4/ip_output.c:119
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff819b3ce0-ffffffff819b3d25: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9f227)
Location: net/ipv4/ip_output.c:120
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
Direct callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff81a9dde0-ffffffff81a9de25: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa9167)
Location: net/ipv4/ip_output.c:120
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
Direct callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff81aa7cc0-ffffffff81aa7d05: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a942e7)
Location: net/ipv4/ip_output.c:120
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff81a92eb0-ffffffff81a92f13: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4f767)
Location: net/ipv4/ip_output.c:120
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff81b4e2b0-ffffffff81b4e313: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdd117)
Location: net/ipv4/ip_output.c:120
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff81cdbb70-ffffffff81cdbbda: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9dba7)
Location: net/ipv4/ip_output.c:120
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff81e9c560-ffffffff81e9c5ca: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81efc367)
Location: net/ipv4/ip_output.c:121
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff81efb150-ffffffff81efb1ba: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fc02a7)
Location: net/ipv4/ip_output.c:123
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_push_pending_frames
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
Direct callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff81fbf060-ffffffff81fbf0ca: ip_local_out (STB_GLOBAL)
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
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c644c0)
Location: net/ipv4/ip_output.c:119
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffff800010c644c0-ffff800010c64528: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d74028)
Location: net/ipv4/ip_output.c:119
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
c0d74028-c0d74074: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d684f0)
Location: net/ipv4/ip_output.c:119
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
c000000000d684f0-c000000000d68574: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007cbe5e)
Location: net/ipv4/ip_output.c:119
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffe0007cbe5e-ffffffe0007cbeac: ip_local_out (STB_GLOBAL)
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
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81953b50)
Location: net/ipv4/ip_output.c:119
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff81953b50-ffffffff81953b95: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190d640)
Location: net/ipv4/ip_output.c:119
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff8190d640-ffffffff8190d685: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819be320)
Location: net/ipv4/ip_output.c:119
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff819be320-ffffffff819be365: ip_local_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_local_out(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c7c50)
Location: net/ipv4/ip_output.c:119
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_sendpack
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
**Symbols:**

```
ffffffff819c7c50-ffffffff819c7c95: ip_local_out (STB_GLOBAL)
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
