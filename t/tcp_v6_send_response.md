# Function: <code>tcp_v6_send_response</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, u32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff817eee70)
Location: net/ipv6/tcp_ipv6.c:736
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff817eee70-ffffffff817ef329: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff8185d760)
Location: net/ipv6/tcp_ipv6.c:745
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff8185d760-ffffffff8185dcbe: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff8188f7a0)
Location: net/ipv6/tcp_ipv6.c:755
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff8188f7a0-ffffffff8188fd66: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff818b5de0)
Location: net/ipv6/tcp_ipv6.c:776
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff818b5de0-ffffffff818b6410: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81938b80)
Location: net/ipv6/tcp_ipv6.c:778
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81938b80-ffffffff8193919a: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819923f0)
Location: net/ipv6/tcp_ipv6.c:792
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff819923f0-ffffffff81992a8c: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819c8b30)
Location: net/ipv6/tcp_ipv6.c:796
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff819c8b30-ffffffff819c91b7: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a374c0)
Location: net/ipv6/tcp_ipv6.c:803
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81a374c0-ffffffff81a37c4b: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a6dfe0)
Location: net/ipv6/tcp_ipv6.c:805
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81a6dfe0-ffffffff81a6e783: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b67ce0)
Location: net/ipv6/tcp_ipv6.c:854
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81b67ce0-ffffffff81b68367: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b76510)
Location: net/ipv6/tcp_ipv6.c:870
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81b76510-ffffffff81b76bad: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b64e40)
Location: net/ipv6/tcp_ipv6.c:885
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81b64e40-ffffffff81b655e9: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:888
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81c2d080-ffffffff81c2d85f: tcp_v6_send_response (STB_LOCAL)
ffffffff81d40cc6-ffffffff81d40cec: tcp_v6_send_response.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:841
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81dca480-ffffffff81dcacbd: tcp_v6_send_response (STB_LOCAL)
ffffffff81f0d618-ffffffff81f0d63e: tcp_v6_send_response.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority, u32 txhash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:848
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81f9b4b0-ffffffff81f9bcfb: tcp_v6_send_response (STB_LOCAL)
ffffffff820b4a50-ffffffff820b4a76: tcp_v6_send_response.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority, u32 txhash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:845
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81ffb8d0-ffffffff81ffbfec: tcp_v6_send_response (STB_LOCAL)
ffffffff82135a14-ffffffff82135a2d: tcp_v6_send_response.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, int rst, u8 tclass, __be32 label, u32 priority, u32 txhash, struct tcp_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/tcp_ipv6.c (0)
Location: net/ipv6/tcp_ipv6.c:863
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff820c9fe0-ffffffff820ca919: tcp_v6_send_response (STB_LOCAL)
ffffffff8221761d-ffffffff82217636: tcp_v6_send_response.cold (STB_LOCAL)
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
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffff800010d37a48)
Location: net/ipv6/tcp_ipv6.c:805
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffff800010d37a48-ffff800010d37fec: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c0e3865c)
Location: net/ipv6/tcp_ipv6.c:805
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
c0e3865c-c0e38ca4: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c000000000e68ed0)
Location: net/ipv6/tcp_ipv6.c:805
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
c000000000e68ed0-c000000000e696a0: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffe000873e0c)
Location: net/ipv6/tcp_ipv6.c:805
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffe000873e0c-ffffffe0008743fa: tcp_v6_send_response (STB_LOCAL)
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
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d670)
Location: net/ipv6/tcp_ipv6.c:805
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81a0d670-ffffffff81a0de13: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819ca430)
Location: net/ipv6/tcp_ipv6.c:805
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff819ca430-ffffffff819cabd3: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a780f0)
Location: net/ipv6/tcp_ipv6.c:805
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81a780f0-ffffffff81a78893: tcp_v6_send_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock *sk, struct sk_buff *skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key *key, int rst, u8 tclass, __be32 label, u32 priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a84860)
Location: net/ipv6/tcp_ipv6.c:805
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
**Symbols:**

```
ffffffff81a84860-ffffffff81a8502f: tcp_v6_send_response (STB_LOCAL)
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
<b>Param type changed. </b>
<code>u32 label</code> ➡️ <code>__be32 label</code>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 priority</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 txhash</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>sk, skb, seq, ack, win, tsval, tsecr, oif, key, rst, tclass, label, priority, txhash</code> ➡️ <code>sk, skb, seq, ack, win, tsval, tsecr, oif, rst, tclass, label, priority, txhash, key</code>
</li>
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
