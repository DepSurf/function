# Function: <code>__tcp_retransmit_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81778400)
Location: net/ipv4/tcp_output.c:2555
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81778400-ffffffff8177899d: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e5460)
Location: net/ipv4/tcp_output.c:2594
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff817e5460-ffffffff817e5add: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818158f0)
Location: net/ipv4/tcp_output.c:2714
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff818158f0-ffffffff81815f5d: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81835cb0)
Location: net/ipv4/tcp_output.c:2789
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81835cb0-ffffffff81836318: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b52a0)
Location: net/ipv4/tcp_output.c:2838
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff818b52a0-ffffffff818b597d: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190a950)
Location: net/ipv4/tcp_output.c:2813
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff8190a950-ffffffff8190b10b: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81938bf0)
Location: net/ipv4/tcp_output.c:2843
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81938bf0-ffffffff81939399: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199ce30)
Location: net/ipv4/tcp_output.c:2870
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff8199ce30-ffffffff8199d67c: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d38f0)
Location: net/ipv4/tcp_output.c:2897
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff819d38f0-ffffffff819d414b: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac0480)
Location: net/ipv4/tcp_output.c:2966
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81ac0480-ffffffff81ac09bc: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acbee0)
Location: net/ipv4/tcp_output.c:3138
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81acbee0-ffffffff81acc426: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab7120)
Location: net/ipv4/tcp_output.c:3143
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81ab7120-ffffffff81ab761b: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3143
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81d3b335-ffffffff81d3b395: __tcp_retransmit_skb.cold (STB_LOCAL)
ffffffff81b74310-ffffffff81b74815: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3139
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81f07c1c-ffffffff81f07c7c: __tcp_retransmit_skb.cold (STB_LOCAL)
ffffffff81d03a00-ffffffff81d03f75: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3141
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff820af694-ffffffff820af6e4: __tcp_retransmit_skb.cold (STB_LOCAL)
ffffffff81ec8970-ffffffff81ec8eb3: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3223
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff82130a6f-ffffffff82130aad: __tcp_retransmit_skb.cold (STB_LOCAL)
ffffffff81f27490-ffffffff81f279d7: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fec3c0)
Location: net/ipv4/tcp_output.c:3281
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81febe80-ffffffff81fec3a7: __tcp_retransmit_skb.part.0 (STB_LOCAL)
ffffffff82212243-ffffffff82212281: __tcp_retransmit_skb.part.0.cold (STB_LOCAL)
ffffffff81fec3c0-ffffffff81fec461: __tcp_retransmit_skb (STB_GLOBAL)
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
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c86430)
Location: net/ipv4/tcp_output.c:2897
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffff800010c86430-ffff800010c86c40: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d95774)
Location: net/ipv4/tcp_output.c:2897
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
c0d95774-c0d9600c: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d92900)
Location: net/ipv4/tcp_output.c:2897
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
c000000000d92900-c000000000d93400: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e7a88)
Location: net/ipv4/tcp_output.c:2897
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffe0007e7a88-ffffffe0007e81a2: __tcp_retransmit_skb (STB_GLOBAL)
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
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81973760)
Location: net/ipv4/tcp_output.c:2897
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81973760-ffffffff81973fbb: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192d230)
Location: net/ipv4/tcp_output.c:2897
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff8192d230-ffffffff8192da8b: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819ddf30)
Location: net/ipv4/tcp_output.c:2897
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff819ddf30-ffffffff819de78b: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e7bb0)
Location: net/ipv4/tcp_output.c:2897
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff819e7bb0-ffffffff819e8424: __tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int segs</code>
</li>
</ul>
</details>
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
