# Function: <code>__skb_tstamp_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81706f20)
Location: net/core/skbuff.c:3762
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff81706f20-ffffffff81707040: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176ed50)
Location: net/core/skbuff.c:3803
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff8176ed50-ffffffff8176ee70: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179c210)
Location: net/core/skbuff.c:3838
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff8179c210-ffffffff8179c351: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bce80)
Location: net/core/skbuff.c:3926
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff817bce80-ffffffff817bd01b: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81835130)
Location: net/core/skbuff.c:4314
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff81835130-ffffffff818352cb: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187f3c0)
Location: net/core/skbuff.c:4353
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff8187f3c0-ffffffff8187f550: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a0190)
Location: net/core/skbuff.c:4373
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff818a0190-ffffffff818a0320: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818eaba0)
Location: net/core/skbuff.c:4558
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff818eaba0-ffffffff818ead36: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191cd10)
Location: net/core/skbuff.c:4570
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff8191cd10-ffffffff8191cea6: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ef000)
Location: net/core/skbuff.c:4672
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff819ef000-ffffffff819ef1ef: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eeca0)
Location: net/core/skbuff.c:4739
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff819eeca0-ffffffff819eee92: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, const struct sk_buff *ack_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d7360)
Location: net/core/skbuff.c:4825
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff819d7360-ffffffff819d7555: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, const struct sk_buff *ack_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a85ba0)
Location: net/core/skbuff.c:4893
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a85ba0-ffffffff81a85d95: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, const struct sk_buff *ack_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf9dc0)
Location: net/core/skbuff.c:4808
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81bf9dc0-ffffffff81bfa005: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, const struct sk_buff *ack_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da8c90)
Location: net/core/skbuff.c:5010
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81da8c90-ffffffff81da8ed3: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, const struct sk_buff *ack_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e19d90)
Location: net/core/skbuff.c:5201
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81e19d90-ffffffff81e1a010: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, const struct sk_buff *ack_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed7330)
Location: net/core/skbuff.c:5330
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81ed7330-ffffffff81ed75c9: __skb_tstamp_tx (STB_GLOBAL)
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
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb7400)
Location: net/core/skbuff.c:4570
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffff800010bb7400-ffff800010bb758c: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd40f0)
Location: net/core/skbuff.c:4570
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
c0cd40f0-c0cd425c: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8ef30)
Location: net/core/skbuff.c:4570
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
c000000000c8ef30-c000000000c8f1a8: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000746f38)
Location: net/core/skbuff.c:4570
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffe000746f38-ffffffe00074708e: __skb_tstamp_tx (STB_GLOBAL)
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
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bcd10)
Location: net/core/skbuff.c:4570
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff818bcd10-ffffffff818bcea6: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81876c50)
Location: net/core/skbuff.c:4570
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff81876c50-ffffffff81876de6: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190dd10)
Location: net/core/skbuff.c:4570
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff8190dd10-ffffffff8190dea6: __skb_tstamp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff *orig_skb, struct skb_shared_hwtstamps *hwtstamps, struct sock *sk, int tstype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192ee40)
Location: net/core/skbuff.c:4570
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_tstamp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
**Symbols:**

```
ffffffff8192ee40-ffffffff8192efd6: __skb_tstamp_tx (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sk_buff *ack_skb</code>
</li>
<li>
<b>Param reordered. </b>
<code>orig_skb, hwtstamps, sk, tstype</code> ➡️ <code>orig_skb, ack_skb, hwtstamps, sk, tstype</code>
</li>
</ul>
</details>
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
