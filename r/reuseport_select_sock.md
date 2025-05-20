# Function: <code>reuseport_select_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8179ffc0)
Location: net/core/sock_reuseport.c:207
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff8179ffc0-ffffffff817a027c: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817ce990)
Location: net/core/sock_reuseport.c:206
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff817ce990-ffffffff817cec4c: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817ede30)
Location: net/core/sock_reuseport.c:206
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff817ede30-ffffffff817edff4: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8186a070)
Location: net/core/sock_reuseport.c:218
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff8186a070-ffffffff8186a23d: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818b9d50)
Location: net/core/sock_reuseport.c:218
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff818b9d50-ffffffff818b9f64: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818e0ae0)
Location: net/core/sock_reuseport.c:263
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff818e0ae0-ffffffff818e0ce2: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8192f180)
Location: net/core/sock_reuseport.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff8192f180-ffffffff8192f422: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff819613f0)
Location: net/core/sock_reuseport.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff819613f0-ffffffff81961692: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a34bc0)
Location: net/core/sock_reuseport.c:257
Inline: False
```
**Symbols:**

```
ffffffff81a34bc0-ffffffff81a34c81: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a36f10)
Location: net/core/sock_reuseport.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81a36f10-ffffffff81a36fcc: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a1e070)
Location: net/core/sock_reuseport.c:257
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81a1e070-ffffffff81a1e12b: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad1cb0)
Location: net/core/sock_reuseport.c:469
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff81ad1cb0-ffffffff81ad1d69: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81c4f560)
Location: net/core/sock_reuseport.c:469
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff81c4f560-ffffffff81c4f74b: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e044f0)
Location: net/core/sock_reuseport.c:569
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff81e044f0-ffffffff81e046a0: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e76d40)
Location: net/core/sock_reuseport.c:569
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff81e76d40-ffffffff81e76ef0: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f36d00)
Location: net/core/sock_reuseport.c:569
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff81f36d00-ffffffff81f36eb0: reuseport_select_sock (STB_GLOBAL)
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
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffff800010c04c60)
Location: net/core/sock_reuseport.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffff800010c04c60-ffff800010c04f00: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c0d1e120)
Location: net/core/sock_reuseport.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
c0d1e120-c0d1e434: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c000000000ceee10)
Location: net/core/sock_reuseport.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
c000000000ceee10-c000000000cef210: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffe0007838da)
Location: net/core/sock_reuseport.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffe0007838da-ffffffe000783b24: reuseport_select_sock (STB_GLOBAL)
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
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff819013c0)
Location: net/core/sock_reuseport.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff819013c0-ffffffff81901662: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818bb1f0)
Location: net/core/sock_reuseport.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff818bb1f0-ffffffff818bb492: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff819523f0)
Location: net/core/sock_reuseport.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff819523f0-ffffffff81952692: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *reuseport_select_sock(struct sock *sk, u32 hash, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81973e30)
Location: net/core/sock_reuseport.c:265
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
**Symbols:**

```
ffffffff81973e30-ffffffff81974107: reuseport_select_sock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
