# Function: <code>__bpf_skc_lookup</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81926d20)
Location: net/core/filter.c:5249
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
ffffffff81926d20-ffffffff81926e61: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819593e0)
Location: net/core/filter.c:5258
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
ffffffff819593e0-ffffffff81959521: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e260)
Location: net/core/filter.c:5385
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
```
**Symbols:**

```
ffffffff81a2e260-ffffffff81a2e3dc: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2f7c0)
Location: net/core/filter.c:5937
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
```
**Symbols:**

```
ffffffff81a2f7c0-ffffffff81a2f942: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a168a0)
Location: net/core/filter.c:6039
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
```
**Symbols:**

```
ffffffff81a168a0-ffffffff81a16a21: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac7ea0)
Location: net/core/filter.c:6163
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
```
**Symbols:**

```
ffffffff81ac7ea0-ffffffff81ac8021: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c45550)
Location: net/core/filter.c:6471
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
ffffffff81c45550-ffffffff81c4576e: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df96c0)
Location: net/core/filter.c:6484
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
ffffffff81df96c0-ffffffff81df98de: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags, int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6b040)
Location: net/core/filter.c:6563
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_tc_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:__bpf_sk_lookup
```
**Symbols:**

```
ffffffff81e6b040-ffffffff81e6b269: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags, int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f29fd0)
Location: net/core/filter.c:6653
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_tc_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
  - net/core/filter.c:__bpf_sk_lookup
```
**Symbols:**

```
ffffffff81f29fd0-ffffffff81f2a1f9: __bpf_skc_lookup (STB_LOCAL)
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
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfa8a8)
Location: net/core/filter.c:5258
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
ffff800010bfa8a8-ffff800010bfaa4c: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d14388)
Location: net/core/filter.c:5258
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
c0d14388-c0d1452c: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce2cd0)
Location: net/core/filter.c:5258
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
c000000000ce2cd0-c000000000ce2ec8: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077c5ae)
Location: net/core/filter.c:5258
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
ffffffe00077c5ae-ffffffe00077c6ba: __bpf_skc_lookup (STB_LOCAL)
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
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f93b0)
Location: net/core/filter.c:5258
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
ffffffff818f93b0-ffffffff818f94f1: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b31e0)
Location: net/core/filter.c:5258
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
ffffffff818b31e0-ffffffff818b3321: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a3e0)
Location: net/core/filter.c:5258
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
ffffffff8194a3e0-ffffffff8194a521: __bpf_skc_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *__bpf_skc_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196bcf0)
Location: net/core/filter.c:5258
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_skc_lookup_tcp
  - net/core/filter.c:bpf_xdp_skc_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
**Symbols:**

```
ffffffff8196bcf0-ffffffff8196be31: __bpf_skc_lookup (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sdif</code>
</li>
</ul>
</details>
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
