# Function: <code>tcp_make_synack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, bool attach_req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81774ab0)
Location: net/ipv4/tcp_output.c:2942
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81774ab0-ffffffff81774e7c: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e1a30)
Location: net/ipv4/tcp_output.c:2986
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff817e1a30-ffffffff817e1e15: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81811f30)
Location: net/ipv4/tcp_output.c:3110
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81811f30-ffffffff8181231d: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81832280)
Location: net/ipv4/tcp_output.c:3135
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81832280-ffffffff81832691: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b13b0)
Location: net/ipv4/tcp_output.c:3194
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff818b13b0-ffffffff818b17e3: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81906bf0)
Location: net/ipv4/tcp_output.c:3175
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81906bf0-ffffffff8190703a: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81934dc0)
Location: net/ipv4/tcp_output.c:3207
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81934dc0-ffffffff819351e7: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81998d60)
Location: net/ipv4/tcp_output.c:3234
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81998d60-ffffffff819991b8: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819cf880)
Location: net/ipv4/tcp_output.c:3266
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff819cf880-ffffffff819cfcd8: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abc1b0)
Location: net/ipv4/tcp_output.c:3339
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81abc1b0-ffffffff81abc52a: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac7a20)
Location: net/ipv4/tcp_output.c:3512
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81ac7a20-ffffffff81ac7de0: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab2a80)
Location: net/ipv4/tcp_output.c:3509
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81ab2a80-ffffffff81ab2e3b: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b6f950)
Location: net/ipv4/tcp_output.c:3510
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81b6f950-ffffffff81b6fd29: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81cfef90)
Location: net/ipv4/tcp_output.c:3516
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81cfef90-ffffffff81cff3fc: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec3ff0)
Location: net/ipv4/tcp_output.c:3518
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81ec3ff0-ffffffff81ec445c: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f22300)
Location: net/ipv4/tcp_output.c:3600
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff81f22300-ffffffff81f22750: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3664
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff8221205b-ffffffff8221207c: tcp_make_synack.cold (STB_LOCAL)
ffffffff81fe6ef0-ffffffff81fe7441: tcp_make_synack (STB_GLOBAL)
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
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c82aa8)
Location: net/ipv4/tcp_output.c:3266
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffff800010c82aa8-ffff800010c82ec0: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d91480)
Location: net/ipv4/tcp_output.c:3266
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
c0d91480-c0d918cc: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d8d890)
Location: net/ipv4/tcp_output.c:3266
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
c000000000d8d890-c000000000d8de40: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e42c4)
Location: net/ipv4/tcp_output.c:3266
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffe0007e42c4-ffffffe0007e46f2: tcp_make_synack (STB_GLOBAL)
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
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8196f6f0)
Location: net/ipv4/tcp_output.c:3266
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff8196f6f0-ffffffff8196fb48: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819291c0)
Location: net/ipv4/tcp_output.c:3266
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff819291c0-ffffffff81929618: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d9ec0)
Location: net/ipv4/tcp_output.c:3266
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff819d9ec0-ffffffff819da318: tcp_make_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *tcp_make_synack(const struct sock *sk, struct dst_entry *dst, struct request_sock *req, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e3b30)
Location: net/ipv4/tcp_output.c:3266
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
**Symbols:**

```
ffffffff819e3b30-ffffffff819e3f92: tcp_make_synack (STB_GLOBAL)
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
<code>enum tcp_synack_type synack_type</code>
</li>
<li>
<b>Param removed. </b>
<code>bool attach_req</code>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff *syn_skb</code>
</li>
</ul>
</details>
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
