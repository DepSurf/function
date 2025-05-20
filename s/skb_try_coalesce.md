# Function: <code>skb_try_coalesce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8170b890)
Location: net/core/skbuff.c:4201
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff8170b890-ffffffff8170bcc0: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81773270)
Location: net/core/skbuff.c:4242
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81773270-ffffffff817736b0: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817a0480)
Location: net/core/skbuff.c:4286
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff817a0480-ffffffff817a08e0: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817babe0)
Location: net/core/skbuff.c:4380
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff817babe0-ffffffff817bafef: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81832cb0)
Location: net/core/skbuff.c:4768
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81832cb0-ffffffff81833061: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187d1d0)
Location: net/core/skbuff.c:4807
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff8187d1d0-ffffffff8187d569: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189ddc0)
Location: net/core/skbuff.c:4829
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff8189ddc0-ffffffff8189e13b: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e8590)
Location: net/core/skbuff.c:5014
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff818e8590-ffffffff818e88ff: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191a7d0)
Location: net/core/skbuff.c:5026
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff8191a7d0-ffffffff8191ab3f: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ece00)
Location: net/core/skbuff.c:5128
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff819ece00-ffffffff819ed173: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ecac0)
Location: net/core/skbuff.c:5195
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff819ecac0-ffffffff819ece33: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d2fa0)
Location: net/core/skbuff.c:5283
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff819d2fa0-ffffffff819d3310: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5351
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff81d351c1-ffffffff81d351d7: skb_try_coalesce.cold (STB_LOCAL)
ffffffff81a82c80-ffffffff81a83033: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5265
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff81f0171e-ffffffff81f01734: skb_try_coalesce.cold (STB_LOCAL)
ffffffff81bf7970-ffffffff81bf7e2a: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da66d0)
Location: net/core/skbuff.c:5467
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff81da66d0-ffffffff81da6ba3: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5665
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff8212c1a3-ffffffff8212c1ec: skb_try_coalesce.cold (STB_LOCAL)
ffffffff81e157f0-ffffffff81e15df7: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5796
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff8220de83-ffffffff8220decc: skb_try_coalesce.cold (STB_LOCAL)
ffffffff81ed2b90-ffffffff81ed3224: skb_try_coalesce (STB_GLOBAL)
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
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb4b30)
Location: net/core/skbuff.c:5026
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffff800010bb4b30-ffff800010bb4e84: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd1c54)
Location: net/core/skbuff.c:5026
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
c0cd1c54-c0cd1fc4: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8b640)
Location: net/core/skbuff.c:5026
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
c000000000c8b640-c000000000c8bad0: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000744bbe)
Location: net/core/skbuff.c:5026
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffe000744bbe-ffffffe000744e5e: skb_try_coalesce (STB_GLOBAL)
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
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ba7d0)
Location: net/core/skbuff.c:5026
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff818ba7d0-ffffffff818bab3f: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81874720)
Location: net/core/skbuff.c:5026
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff81874720-ffffffff81874a8f: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190b7d0)
Location: net/core/skbuff.c:5026
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff8190b7d0-ffffffff8190bb3f: skb_try_coalesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool skb_try_coalesce(struct sk_buff *to, struct sk_buff *from, bool *fragstolen, int *delta_truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192c8f0)
Location: net/core/skbuff.c:5026
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff8192c8f0-ffffffff8192cc5f: skb_try_coalesce (STB_GLOBAL)
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
