# Function: <code>skb_condense</code>

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
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817a12c0)
Location: net/core/skbuff.c:4949
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff817a12c0-ffffffff817a1320: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817be200)
Location: net/core/skbuff.c:5043
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff817be200-ffffffff817be261: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81837910)
Location: net/core/skbuff.c:5474
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff81837910-ffffffff81837971: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81881de0)
Location: net/core/skbuff.c:5553
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff81881de0-ffffffff81881e41: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a28f0)
Location: net/core/skbuff.c:5576
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff818a28f0-ffffffff818a294b: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ed540)
Location: net/core/skbuff.c:5936
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff818ed540-ffffffff818ed59b: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191f640)
Location: net/core/skbuff.c:5953
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff8191f640-ffffffff8191f69b: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f2bb0)
Location: net/core/skbuff.c:6063
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff819f2bb0-ffffffff819f2c19: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f2ba0)
Location: net/core/skbuff.c:6200
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff819f2ba0-ffffffff819f2c00: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d8dd0)
Location: net/core/skbuff.c:6288
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff819d8dd0-ffffffff819d8e39: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a88d70)
Location: net/core/skbuff.c:6363
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81a88d70-ffffffff81a88dd9: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfe0b0)
Location: net/core/skbuff.c:6276
Inline: True
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81bfe0b0-ffffffff81bfe13d: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81daad40)
Location: net/core/skbuff.c:6476
Inline: True
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81daad40-ffffffff81daadcd: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1a8c0)
Location: net/core/skbuff.c:6521
Inline: True
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81e1a8c0-ffffffff81e1a94d: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed7e80)
Location: net/core/skbuff.c:6668
Inline: True
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81ed7e80-ffffffff81ed7f0d: skb_condense (STB_GLOBAL)
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
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bba040)
Location: net/core/skbuff.c:5953
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffff800010bba040-ffff800010bba0c0: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd68f0)
Location: net/core/skbuff.c:5953
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
c0cd68f0-c0cd6964: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c92980)
Location: net/core/skbuff.c:5953
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
c000000000c92980-c000000000c92a24: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000749412)
Location: net/core/skbuff.c:5953
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffe000749412-ffffffe000749482: skb_condense (STB_GLOBAL)
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
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bf640)
Location: net/core/skbuff.c:5953
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff818bf640-ffffffff818bf69b: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81879580)
Location: net/core/skbuff.c:5953
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff81879580-ffffffff818795db: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81910640)
Location: net/core/skbuff.c:5953
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff81910640-ffffffff8191069b: skb_condense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_condense(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819317a0)
Location: net/core/skbuff.c:5953
Inline: False
Direct callers:
  - net/core/skbuff.c:___pskb_trim
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff819317a0-ffffffff819317fb: skb_condense (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
