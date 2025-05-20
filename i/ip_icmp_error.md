# Function: <code>ip_icmp_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81761910)
Location: net/ipv4/ip_sockglue.c:371
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81761910-ffffffff817619f1: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817cdc40)
Location: net/ipv4/ip_sockglue.c:380
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff817cdc40-ffffffff817cdd21: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817fd9a0)
Location: net/ipv4/ip_sockglue.c:398
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff817fd9a0-ffffffff817fda81: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8181dde0)
Location: net/ipv4/ip_sockglue.c:390
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff8181dde0-ffffffff8181dec1: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8189ccf0)
Location: net/ipv4/ip_sockglue.c:394
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff8189ccf0-ffffffff8189cdd1: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff818f11d0)
Location: net/ipv4/ip_sockglue.c:393
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff818f11d0-ffffffff818f12b1: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8191ed30)
Location: net/ipv4/ip_sockglue.c:390
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff8191ed30-ffffffff8191ee11: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81981640)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81981640-ffffffff81981736: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819b7e80)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff819b7e80-ffffffff819b7f76: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa27a0)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81aa27a0-ffffffff81aa2899: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aaca70)
Location: net/ipv4/ip_sockglue.c:405
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_err
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81aaca70-ffffffff81aacba3: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a97cc0)
Location: net/ipv4/ip_sockglue.c:405
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81a97cc0-ffffffff81a97df2: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b53150)
Location: net/ipv4/ip_sockglue.c:405
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81b53150-ffffffff81b53282: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cdf840)
Location: net/ipv4/ip_sockglue.c:407
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81cdf840-ffffffff81cdf982: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9e290)
Location: net/ipv4/ip_sockglue.c:407
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81e9e290-ffffffff81e9e3d2: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efca90)
Location: net/ipv4/ip_sockglue.c:414
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81efca90-ffffffff81efcbd2: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc0aa0)
Location: net/ipv4/ip_sockglue.c:412
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81fc0aa0-ffffffff81fc0be4: ip_icmp_error (STB_GLOBAL)
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
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffff800010c69288)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffff800010c69288-ffff800010c6935c: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c0d78488)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
c0d78488-c0d78558: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c000000000d6dde0)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
c000000000d6dde0-c000000000d6df10: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffe0007cf1c6)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffe0007cf1c6-ffffffe0007cf28c: ip_icmp_error (STB_GLOBAL)
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
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81957cf0)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff81957cf0-ffffffff81957de6: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819117e0)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff819117e0-ffffffff819118d6: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819c24c0)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff819c24c0-ffffffff819c25b6: ip_icmp_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip_icmp_error(struct sock *sk, struct sk_buff *skb, int err, __be16 port, u32 info, u8 *payload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819cbec0)
Location: net/ipv4/ip_sockglue.c:392
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/ping.c:ping_err
```
**Symbols:**

```
ffffffff819cbec0-ffffffff819cbfb6: ip_icmp_error (STB_GLOBAL)
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
