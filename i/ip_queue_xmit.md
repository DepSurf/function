# Function: <code>ip_queue_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175e400)
Location: net/ipv4/ip_output.c:380
Inline: False
```
**Symbols:**

```
ffffffff8175e400-ffffffff8175e77d: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817ca650)
Location: net/ipv4/ip_output.c:378
Inline: False
```
**Symbols:**

```
ffffffff817ca650-ffffffff817ca9eb: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817fa2d0)
Location: net/ipv4/ip_output.c:422
Inline: False
```
**Symbols:**

```
ffffffff817fa2d0-ffffffff817fa69f: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8181a6d0)
Location: net/ipv4/ip_output.c:426
Inline: False
```
**Symbols:**

```
ffffffff8181a6d0-ffffffff8181aaab: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818996b0)
Location: net/ipv4/ip_output.c:426
Inline: False
```
**Symbols:**

```
ffffffff818996b0-ffffffff81899a8b: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818edb10)
Location: net/ipv4/ip_output.c:426
Inline: False
```
**Symbols:**

```
ffffffff818edb10-ffffffff818edf18: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193c2d0)
Location: include/net/ip.h:195
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c87a0)
Location: include/net/ip.h:195
Inline: False
```
**Symbols:**

```
ffffffff8193c2d0-ffffffff8193c2e2: ip_queue_xmit (STB_LOCAL)
ffffffff819c87a0-ffffffff819c87b2: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a0710)
Location: include/net/ip.h:233
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37140)
Location: include/net/ip.h:233
Inline: False
```
**Symbols:**

```
ffffffff819a0710-ffffffff819a0722: ip_queue_xmit (STB_LOCAL)
ffffffff81a37140-ffffffff81a37152: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819d72d0)
Location: include/net/ip.h:234
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6dcd0)
Location: include/net/ip.h:234
Inline: False
```
**Symbols:**

```
ffffffff819d72d0-ffffffff819d72e2: ip_queue_xmit (STB_LOCAL)
ffffffff81a6dcd0-ffffffff81a6dce2: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4260)
Location: include/net/ip.h:234
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66960)
Location: include/net/ip.h:234
Inline: False
```
**Symbols:**

```
ffffffff81ac4260-ffffffff81ac4272: ip_queue_xmit (STB_LOCAL)
ffffffff81b66960-ffffffff81b66972: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa8340)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81aa8340-ffffffff81aa8357: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a93330)
Location: net/ipv4/ip_output.c:545
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81a93330-ffffffff81a93347: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4e760)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81b4e760-ffffffff81b4e777: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdc040)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81cdc040-ffffffff81cdc063: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9ca50)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81e9ca50-ffffffff81e9ca73: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81efb680)
Location: net/ipv4/ip_output.c:546
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81efb680-ffffffff81efb6a3: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fbf5d0)
Location: net/ipv4/ip_output.c:547
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81fbf5d0-ffffffff81fbf5f3: ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8a328)
Location: include/net/ip.h:234
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36470)
Location: include/net/ip.h:234
Inline: False
```
**Symbols:**

```
ffff800010c8a328-ffff800010c8a340: ip_queue_xmit (STB_LOCAL)
ffff800010d36470-ffff800010d36488: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d99c64)
Location: include/net/ip.h:234
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (c0e393b0)
Location: include/net/ip.h:234
Inline: False
```
**Symbols:**

```
c0d99c64-c0d99c7c: ip_queue_xmit (STB_LOCAL)
c0e393b0-c0e393c8: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d97cf0)
Location: include/net/ip.h:234
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (c000000000e68a30)
Location: include/net/ip.h:234
Inline: False
```
**Symbols:**

```
c000000000d97cf0-c000000000d97d20: ip_queue_xmit (STB_LOCAL)
c000000000e68a30-c000000000e68a60: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb27e)
Location: include/net/ip.h:234
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000873abc)
Location: include/net/ip.h:234
Inline: False
```
**Symbols:**

```
ffffffe0007eb27e-ffffffe0007eb29a: ip_queue_xmit (STB_LOCAL)
ffffffe000873abc-ffffffe000873ad8: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81977140)
Location: include/net/ip.h:234
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d360)
Location: include/net/ip.h:234
Inline: False
```
**Symbols:**

```
ffffffff81977140-ffffffff81977152: ip_queue_xmit (STB_LOCAL)
ffffffff81a0d360-ffffffff81a0d372: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81930c00)
Location: include/net/ip.h:234
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca120)
Location: include/net/ip.h:234
Inline: False
```
**Symbols:**

```
ffffffff81930c00-ffffffff81930c12: ip_queue_xmit (STB_LOCAL)
ffffffff819ca120-ffffffff819ca132: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e1910)
Location: include/net/ip.h:234
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a77de0)
Location: include/net/ip.h:234
Inline: False
```
**Symbols:**

```
ffffffff819e1910-ffffffff819e1922: ip_queue_xmit (STB_LOCAL)
ffffffff81a77de0-ffffffff81a77df2: ip_queue_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate ⚠️</summary>

```c
int ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819eb640)
Location: include/net/ip.h:234
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84550)
Location: include/net/ip.h:234
Inline: False
```
**Symbols:**

```
ffffffff819eb640-ffffffff819eb652: ip_queue_xmit (STB_LOCAL)
ffffffff81a84550-ffffffff81a84562: ip_queue_xmit (STB_LOCAL)
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
