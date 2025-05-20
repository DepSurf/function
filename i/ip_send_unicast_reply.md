# Function: <code>ip_send_unicast_reply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175f5e0)
Location: net/ipv4/ip_output.c:1539
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8175f5e0-ffffffff8175f910: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817cb880)
Location: net/ipv4/ip_output.c:1537
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff817cb880-ffffffff817cbbb0: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817fb4e0)
Location: net/ipv4/ip_output.c:1578
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff817fb4e0-ffffffff817fb82b: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8181b8c0)
Location: net/ipv4/ip_output.c:1591
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8181b8c0-ffffffff8181bbe5: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8189a7f0)
Location: net/ipv4/ip_output.c:1509
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8189a7f0-ffffffff8189ab1e: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818eecc0)
Location: net/ipv4/ip_output.c:1532
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff818eecc0-ffffffff818eefea: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191c460)
Location: net/ipv4/ip_output.c:1559
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8191c460-ffffffff8191c7ee: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197e790)
Location: net/ipv4/ip_output.c:1648
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8197e790-ffffffff8197eb27: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b5130)
Location: net/ipv4/ip_output.c:1656
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819b5130-ffffffff819b54b9: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9f3b0)
Location: net/ipv4/ip_output.c:1655
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81a9f3b0-ffffffff81a9f70d: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa92f0)
Location: net/ipv4/ip_output.c:1662
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81aa92f0-ffffffff81aa967b: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a94490)
Location: net/ipv4/ip_output.c:1666
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81a94490-ffffffff81a9484e: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4f910)
Location: net/ipv4/ip_output.c:1665
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81b4f910-ffffffff81b4fcce: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdd330)
Location: net/ipv4/ip_output.c:1665
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81cdd330-ffffffff81cdd7b8: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9ddf0)
Location: net/ipv4/ip_output.c:1680
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81e9ddf0-ffffffff81e9e279: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time, u32 txhash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81efc5b0)
Location: net/ipv4/ip_output.c:1580
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81efc5b0-ffffffff81efca7f: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time, u32 txhash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fc04f0)
Location: net/ipv4/ip_output.c:1586
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81fc04f0-ffffffff81fc09b7: ip_send_unicast_reply (STB_GLOBAL)
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
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c65900)
Location: net/ipv4/ip_output.c:1656
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffff800010c65900-ffff800010c65ba8: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d75554)
Location: net/ipv4/ip_output.c:1656
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
c0d75554-c0d75820: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d6a040)
Location: net/ipv4/ip_output.c:1656
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
c000000000d6a040-c000000000d6a39c: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007cd07a)
Location: net/ipv4/ip_output.c:1656
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffe0007cd07a-ffffffe0007cd2e8: ip_send_unicast_reply (STB_GLOBAL)
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
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81954fa0)
Location: net/ipv4/ip_output.c:1656
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81954fa0-ffffffff81955329: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190ea90)
Location: net/ipv4/ip_output.c:1656
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8190ea90-ffffffff8190ee19: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bf770)
Location: net/ipv4/ip_output.c:1656
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819bf770-ffffffff819bfaf9: ip_send_unicast_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip_send_unicast_reply(struct sock *sk, struct sk_buff *skb, const struct ip_options *sopt, __be32 daddr, __be32 saddr, const struct ip_reply_arg *arg, unsigned int len, u64 transmit_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c90f0)
Location: net/ipv4/ip_output.c:1656
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819c90f0-ffffffff819c94c2: ip_send_unicast_reply (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 transmit_time</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 txhash</code>
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
