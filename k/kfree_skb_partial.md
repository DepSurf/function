# Function: <code>kfree_skb_partial</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81706100)
Location: net/core/skbuff.c:4183
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81706100-ffffffff81706139: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176e590)
Location: net/core/skbuff.c:4224
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff8176e590-ffffffff8176e5c9: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179ba50)
Location: net/core/skbuff.c:4268
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff8179ba50-ffffffff8179ba89: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bdc20)
Location: net/core/skbuff.c:4362
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff817bdc20-ffffffff817bdc59: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81837270)
Location: net/core/skbuff.c:4750
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81837270-ffffffff818372a9: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81881730)
Location: net/core/skbuff.c:4789
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81881730-ffffffff81881769: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a2250)
Location: net/core/skbuff.c:4811
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff818a2250-ffffffff818a2289: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ecf20)
Location: net/core/skbuff.c:4996
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff818ecf20-ffffffff818ecf59: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191f040)
Location: net/core/skbuff.c:5008
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff8191f040-ffffffff8191f079: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819edae0)
Location: net/core/skbuff.c:5110
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff819edae0-ffffffff819edb31: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed7a0)
Location: net/core/skbuff.c:5177
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff819ed7a0-ffffffff819ed7f1: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d5300)
Location: net/core/skbuff.c:5265
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff819d5300-ffffffff819d5351: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a850d0)
Location: net/core/skbuff.c:5333
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff81a850d0-ffffffff81a85121: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfb0e0)
Location: net/core/skbuff.c:5247
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff81bfb0e0-ffffffff81bfb141: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da9dd0)
Location: net/core/skbuff.c:5449
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff81da9dd0-ffffffff81da9e36: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e18b60)
Location: net/core/skbuff.c:5647
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff81e18b60-ffffffff81e18bcc: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed5ff0)
Location: net/core/skbuff.c:5778
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/mptcp/protocol.c:mptcp_try_coalesce
```
**Symbols:**

```
ffffffff81ed5ff0-ffffffff81ed605c: kfree_skb_partial (STB_GLOBAL)
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
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb9978)
Location: net/core/skbuff.c:5008
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffff800010bb9978-ffff800010bb99d4: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd62c0)
Location: net/core/skbuff.c:5008
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
c0cd62c0-c0cd630c: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c91f40)
Location: net/core/skbuff.c:5008
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
c000000000c91f40-c000000000c91fbc: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000748e60)
Location: net/core/skbuff.c:5008
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffe000748e60-ffffffe000748ec4: kfree_skb_partial (STB_GLOBAL)
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
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bf040)
Location: net/core/skbuff.c:5008
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff818bf040-ffffffff818bf079: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81878f80)
Location: net/core/skbuff.c:5008
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff81878f80-ffffffff81878fb9: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81910040)
Location: net/core/skbuff.c:5008
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff81910040-ffffffff81910079: kfree_skb_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_partial(struct sk_buff *skb, bool head_stolen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81931190)
Location: net/core/skbuff.c:5008
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
```
**Symbols:**

```
ffffffff81931190-ffffffff819311c9: kfree_skb_partial (STB_GLOBAL)
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
