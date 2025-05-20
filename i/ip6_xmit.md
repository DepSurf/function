# Function: <code>ip6_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, struct ipv6_txoptions *opt, int tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c4c20)
Location: net/ipv6/ip6_output.c:157
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff817c4c20-ffffffff817c5109: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, struct ipv6_txoptions *opt, int tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff818321e0)
Location: net/ipv6/ip6_output.c:157
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff818321e0-ffffffff818326e1: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81863730)
Location: net/ipv6/ip6_output.c:174
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81863730-ffffffff81863c77: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81888cc0)
Location: net/ipv6/ip6_output.c:175
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81888cc0-ffffffff81889247: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819090b0)
Location: net/ipv6/ip6_output.c:191
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff819090b0-ffffffff8190968d: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819603f0)
Location: net/ipv6/ip6_output.c:191
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff819603f0-ffffffff819609a6: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819951d0)
Location: net/ipv6/ip6_output.c:191
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff819951d0-ffffffff8199578a: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a01ab0)
Location: net/ipv6/ip6_output.c:195
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81a01ab0-ffffffff81a02095: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a38820)
Location: net/ipv6/ip6_output.c:195
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81a38820-ffffffff81a38de4: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2d650)
Location: net/ipv6/ip6_output.c:196
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81b2d650-ffffffff81b2dc0e: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3c080)
Location: net/ipv6/ip6_output.c:235
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81b3c080-ffffffff81b3c655: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2c210)
Location: net/ipv6/ip6_output.c:264
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81b2c210-ffffffff81b2c831: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:245
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81d3f504-ffffffff81d3f530: ip6_xmit.cold (STB_LOCAL)
ffffffff81bf23a0-ffffffff81bf2975: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:248
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81f0bec8-ffffffff81f0beea: ip6_xmit.cold (STB_LOCAL)
ffffffff81d8ae60-ffffffff81d8b524: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:248
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff820b36fd-ffffffff820b371f: ip6_xmit.cold (STB_LOCAL)
ffffffff81f58e60-ffffffff81f59523: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:249
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff82134839-ffffffff82134852: ip6_xmit.cold (STB_LOCAL)
ffffffff81fb8b30-ffffffff81fb91de: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:263
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff822163bf-ffffffff822163d8: ip6_xmit.cold (STB_LOCAL)
ffffffff820860b0-ffffffff82086756: ip6_xmit (STB_GLOBAL)
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
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cfa828)
Location: net/ipv6/ip6_output.c:195
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffff800010cfa828-ffff800010cfada8: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0dfec3c)
Location: net/ipv6/ip6_output.c:195
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
c0dfec3c-c0dff388: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e1f9c0)
Location: net/ipv6/ip6_output.c:195
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
c000000000e1f9c0-c000000000e20168: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe000843704)
Location: net/ipv6/ip6_output.c:195
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffe000843704-ffffffe000843c5c: ip6_xmit (STB_GLOBAL)
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
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819d7eb0)
Location: net/ipv6/ip6_output.c:195
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff819d7eb0-ffffffff819d8474: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81994c70)
Location: net/ipv6/ip6_output.c:195
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81994c70-ffffffff81995234: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a42930)
Location: net/ipv6/ip6_output.c:195
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81a42930-ffffffff81a42ef4: ip6_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_xmit(const struct sock *sk, struct sk_buff *skb, struct flowi6 *fl6, __u32 mark, struct ipv6_txoptions *opt, int tclass, u32 priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a4e5c0)
Location: net/ipv6/ip6_output.c:195
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
**Symbols:**

```
ffffffff81a4e5c0-ffffffff81a4eba0: ip6_xmit (STB_GLOBAL)
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
<code>__u32 mark</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, fl6, opt, tclass</code> ➡️ <code>sk, skb, fl6, mark, opt, tclass</code>
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
