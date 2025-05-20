# Function: <code>tcp_v4_send_ack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_v4_send_ack(struct net *net, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8177ae20)
Location: net/ipv4/tcp_ipv4.c:713
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
**Symbols:**

```
ffffffff8177ae20-ffffffff8177b056: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_v4_send_ack(struct net *net, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff817e8660)
Location: net/ipv4/tcp_ipv4.c:715
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff817e8660-ffffffff817e88b9: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8181a970)
Location: net/ipv4/tcp_ipv4.c:719
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff8181a970-ffffffff8181ac1c: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8183b150)
Location: net/ipv4/tcp_ipv4.c:733
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff8183b150-ffffffff8183b419: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818bae60)
Location: net/ipv4/tcp_ipv4.c:737
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff818bae60-ffffffff818bb129: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81910480)
Location: net/ipv4/tcp_ipv4.c:793
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff81910480-ffffffff8191079e: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193de20)
Location: net/ipv4/tcp_ipv4.c:798
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff8193de20-ffffffff8193e13e: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a2240)
Location: net/ipv4/tcp_ipv4.c:797
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff819a2240-ffffffff819a2594: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819d8e10)
Location: net/ipv4/tcp_ipv4.c:802
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff819d8e10-ffffffff819d9188: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5980)
Location: net/ipv4/tcp_ipv4.c:823
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff81ac5980-ffffffff81ac5cd6: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad15f0)
Location: net/ipv4/tcp_ipv4.c:824
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff81ad15f0-ffffffff81ad1946: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abc5e0)
Location: net/ipv4/tcp_ipv4.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff81abc5e0-ffffffff81abc970: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff81b7a220-ffffffff81b7a5ab: tcp_v4_send_ack (STB_LOCAL)
ffffffff81d3b770-ffffffff81d3b796: tcp_v4_send_ack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:845
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff81d0a3c0-ffffffff81d0a7b6: tcp_v4_send_ack (STB_LOCAL)
ffffffff81f07ff1-ffffffff81f08017: tcp_v4_send_ack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:856
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff81ecfc50-ffffffff81ed0046: tcp_v4_send_ack (STB_LOCAL)
ffffffff820afa9a-ffffffff820afac0: tcp_v4_send_ack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos, u32 txhash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:862
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff81f2e8f0-ffffffff81f2ecf0: tcp_v4_send_ack (STB_LOCAL)
ffffffff82130e07-ffffffff82130e20: tcp_v4_send_ack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_key *key, int reply_flags, u8 tos, u32 txhash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:918
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
```
**Symbols:**

```
ffffffff81ff3750-ffffffff81ff3cf4: tcp_v4_send_ack (STB_LOCAL)
ffffffff82212611-ffffffff8221262a: tcp_v4_send_ack.cold (STB_LOCAL)
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
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8c340)
Location: net/ipv4/tcp_ipv4.c:802
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffff800010c8c340-ffff800010c8c630: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d9bc80)
Location: net/ipv4/tcp_ipv4.c:802
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
```
**Symbols:**

```
c0d9bc80-c0d9bfec: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d9a7b0)
Location: net/ipv4/tcp_ipv4.c:802
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
c000000000d9a7b0-c000000000d9ac08: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed308)
Location: net/ipv4/tcp_ipv4.c:802
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffe0007ed308-ffffffe0007ed6a0: tcp_v4_send_ack (STB_LOCAL)
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
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81978c80)
Location: net/ipv4/tcp_ipv4.c:802
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff81978c80-ffffffff81978ff8: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81932740)
Location: net/ipv4/tcp_ipv4.c:802
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff81932740-ffffffff81932ab8: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e3450)
Location: net/ipv4/tcp_ipv4.c:802
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff819e3450-ffffffff819e37c8: tcp_v4_send_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int reply_flags, u8 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819ed570)
Location: net/ipv4/tcp_ipv4.c:802
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
**Symbols:**

```
ffffffff819ed570-ffffffff819ed8e8: tcp_v4_send_ack (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock *sk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net *net</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct tcp_md5sig_key *key</code> ➡️ <code>struct tcp_key *key</code>
</li>
</ul>
</details>
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
