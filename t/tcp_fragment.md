# Function: <code>tcp_fragment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81775330)
Location: net/ipv4/tcp_output.c:1135
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
**Symbols:**

```
ffffffff81775330-ffffffff81775691: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e2260)
Location: net/ipv4/tcp_output.c:1149
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff817e2260-ffffffff817e25cd: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818128a0)
Location: net/ipv4/tcp_output.c:1168
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff818128a0-ffffffff81812c28: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81832b10)
Location: net/ipv4/tcp_output.c:1244
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81832b10-ffffffff81832e75: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b1f60)
Location: net/ipv4/tcp_output.c:1295
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff818b1f60-ffffffff818b22f5: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819074e0)
Location: net/ipv4/tcp_output.c:1298
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff819074e0-ffffffff81907804: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819357a0)
Location: net/ipv4/tcp_output.c:1286
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff819357a0-ffffffff81935aac: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:1284
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff8199ebf8-ffffffff8199ec10: tcp_fragment.cold (STB_LOCAL)
ffffffff81999a90-ffffffff81999e30: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d0480)
Location: net/ipv4/tcp_output.c:1303
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff819d0480-ffffffff819d0838: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abd470)
Location: net/ipv4/tcp_output.c:1366
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff81abd470-ffffffff81abd828: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac8bc0)
Location: net/ipv4/tcp_output.c:1533
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff81ac8bc0-ffffffff81ac9047: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab3ae0)
Location: net/ipv4/tcp_output.c:1533
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff81ab3ae0-ffffffff81ab3f54: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b70960)
Location: net/ipv4/tcp_output.c:1533
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff81b70960-ffffffff81b70df7: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81cffde0)
Location: net/ipv4/tcp_output.c:1530
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff81cffde0-ffffffff81d00270: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec4eb0)
Location: net/ipv4/tcp_output.c:1527
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff81ec4eb0-ffffffff81ec5340: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f23810)
Location: net/ipv4/tcp_output.c:1529
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff81f23810-ffffffff81f23c39: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fe7f70)
Location: net/ipv4/tcp_output.c:1590
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff81fe7f70-ffffffff81fe83a2: tcp_fragment (STB_GLOBAL)
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
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c83078)
Location: net/ipv4/tcp_output.c:1303
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffff800010c83078-ffff800010c83424: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d922a8)
Location: net/ipv4/tcp_output.c:1303
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
c0d922a8-c0d92634: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d8e7a0)
Location: net/ipv4/tcp_output.c:1303
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
c000000000d8e7a0-c000000000d8ec1c: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e4d32)
Location: net/ipv4/tcp_output.c:1303
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffe0007e4d32-ffffffe0007e503e: tcp_fragment (STB_GLOBAL)
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
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819702f0)
Location: net/ipv4/tcp_output.c:1303
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff819702f0-ffffffff819706a8: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81929dc0)
Location: net/ipv4/tcp_output.c:1303
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff81929dc0-ffffffff8192a178: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819daac0)
Location: net/ipv4/tcp_output.c:1303
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff819daac0-ffffffff819dae78: tcp_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_fragment(struct sock *sk, enum tcp_queue tcp_queue, struct sk_buff *skb, u32 len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e4750)
Location: net/ipv4/tcp_output.c:1303
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
  - net/ipv4/tcp_output.c:tcp_write_wakeup
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff819e4750-ffffffff819e4afa: tcp_fragment (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum tcp_queue tcp_queue</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, len, mss_now, gfp</code> ➡️ <code>sk, tcp_queue, skb, len, mss_now, gfp</code>
</li>
</ul>
</details>
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
