# Function: <code>tcp_get_timestamping_opt_stats</code>

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
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81807150)
Location: net/ipv4/tcp.c:2850
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81807150-ffffffff8180723e: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81827740)
Location: net/ipv4/tcp.c:2936
Inline: False
```
**Symbols:**

```
ffffffff81827740-ffffffff81827884: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a6c90)
Location: net/ipv4/tcp.c:3028
Inline: False
```
**Symbols:**

```
ffffffff818a6c90-ffffffff818a6f3a: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818fbd90)
Location: net/ipv4/tcp.c:3214
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff818fbd90-ffffffff818fc109: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81929d10)
Location: net/ipv4/tcp.c:3254
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81929d10-ffffffff8192a149: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8198cf30)
Location: net/ipv4/tcp.c:3327
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff8198cf30-ffffffff8198d340: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c38d0)
Location: net/ipv4/tcp.c:3345
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff819c38d0-ffffffff819c3ce0: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aaf050)
Location: net/ipv4/tcp.c:3520
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81aaf050-ffffffff81aaf4bc: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk, const struct sk_buff *orig_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aba100)
Location: net/ipv4/tcp.c:3780
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81aba100-ffffffff81aba59a: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk, const struct sk_buff *orig_skb, const struct sk_buff *ack_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa5380)
Location: net/ipv4/tcp.c:3846
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81aa5380-ffffffff81aa5885: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk, const struct sk_buff *orig_skb, const struct sk_buff *ack_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b616d0)
Location: net/ipv4/tcp.c:3871
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81b616d0-ffffffff81b61bd5: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk, const struct sk_buff *orig_skb, const struct sk_buff *ack_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81cf00f0)
Location: net/ipv4/tcp.c:3892
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81cf00f0-ffffffff81cf0645: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk, const struct sk_buff *orig_skb, const struct sk_buff *ack_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eb3420)
Location: net/ipv4/tcp.c:3995
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81eb3420-ffffffff81eb39ac: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk, const struct sk_buff *orig_skb, const struct sk_buff *ack_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f11b40)
Location: net/ipv4/tcp.c:3889
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81f11b40-ffffffff81f120d5: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk, const struct sk_buff *orig_skb, const struct sk_buff *ack_skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd5de0)
Location: net/ipv4/tcp.c:3936
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81fd5de0-ffffffff81fd6375: tcp_get_timestamping_opt_stats (STB_GLOBAL)
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
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c764b8)
Location: net/ipv4/tcp.c:3345
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffff800010c764b8-ffff800010c7680c: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d84bc0)
Location: net/ipv4/tcp.c:3345
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
c0d84bc0-c0d84f10: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7e010)
Location: net/ipv4/tcp.c:3345
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
c000000000d7e010-c000000000d7e3dc: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d9648)
Location: net/ipv4/tcp.c:3345
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffe0007d9648-ffffffe0007d9932: tcp_get_timestamping_opt_stats (STB_GLOBAL)
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
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81963740)
Location: net/ipv4/tcp.c:3345
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff81963740-ffffffff81963b50: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191d230)
Location: net/ipv4/tcp.c:3345
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff8191d230-ffffffff8191d640: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cdf10)
Location: net/ipv4/tcp.c:3345
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff819cdf10-ffffffff819ce320: tcp_get_timestamping_opt_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *tcp_get_timestamping_opt_stats(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d7aa0)
Location: net/ipv4/tcp.c:3345
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
**Symbols:**

```
ffffffff819d7aa0-ffffffff819d7eb0: tcp_get_timestamping_opt_stats (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sk_buff *orig_skb</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sk_buff *ack_skb</code>
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
