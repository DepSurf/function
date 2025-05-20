# Function: <code>sock_queue_err_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81706170)
Location: net/core/skbuff.c:3629
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
```
**Symbols:**

```
ffffffff81706170-ffffffff81706227: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176cb70)
Location: net/core/skbuff.c:3670
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff8176cb70-ffffffff8176cc27: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799d40)
Location: net/core/skbuff.c:3696
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81799d40-ffffffff81799df7: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b92a0)
Location: net/core/skbuff.c:3775
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff817b92a0-ffffffff817b9368: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81831bb0)
Location: net/core/skbuff.c:4159
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81831bb0-ffffffff81831caf: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187c060)
Location: net/core/skbuff.c:4198
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff8187c060-ffffffff8187c154: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189c8c0)
Location: net/core/skbuff.c:4218
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff8189c8c0-ffffffff8189c9b4: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e78c0)
Location: net/core/skbuff.c:4403
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff818e78c0-ffffffff818e79aa: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81919ca0)
Location: net/core/skbuff.c:4415
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81919ca0-ffffffff81919d8c: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb690)
Location: net/core/skbuff.c:4517
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff819eb690-ffffffff819eb7b9: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb3b0)
Location: net/core/skbuff.c:4584
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff819eb3b0-ffffffff819eb4d9: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d18c0)
Location: net/core/skbuff.c:4670
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff819d18c0-ffffffff819d19e9: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a81490)
Location: net/core/skbuff.c:4738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81a81490-ffffffff81a815ed: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf5160)
Location: net/core/skbuff.c:4654
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81bf5160-ffffffff81bf52dc: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da3680)
Location: net/core/skbuff.c:4856
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81da3680-ffffffff81da37fc: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e12270)
Location: net/core/skbuff.c:5047
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81e12270-ffffffff81e123ff: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecf430)
Location: net/core/skbuff.c:5173
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81ecf430-ffffffff81ecf5bf: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb3fa0)
Location: net/core/skbuff.c:4415
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffff800010bb3fa0-ffff800010bb40f0: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd0ba0)
Location: net/core/skbuff.c:4415
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
c0cd0ba0-c0cd0ccc: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c866b0)
Location: net/core/skbuff.c:4415
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
c000000000c866b0-c000000000c86828: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000744070)
Location: net/core/skbuff.c:4415
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffe000744070-ffffffe00074413e: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b9ca0)
Location: net/core/skbuff.c:4415
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff818b9ca0-ffffffff818b9d8c: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81873bf0)
Location: net/core/skbuff.c:4415
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81873bf0-ffffffff81873cdc: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190aca0)
Location: net/core/skbuff.c:4415
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff8190aca0-ffffffff8190ad8c: sock_queue_err_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sock_queue_err_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192bda0)
Location: net/core/skbuff.c:4415
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/ipv4/ip_sockglue.c:ip_local_error
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_local_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff8192bda0-ffffffff8192be8c: sock_queue_err_skb (STB_GLOBAL)
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
