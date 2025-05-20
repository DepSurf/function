# Function: <code>ip_local_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81761a00)
Location: net/ipv4/ip_sockglue.c:400
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81761a00-ffffffff81761b3a: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817cdd30)
Location: net/ipv4/ip_sockglue.c:409
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff817cdd30-ffffffff817cde6a: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817fda90)
Location: net/ipv4/ip_sockglue.c:427
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff817fda90-ffffffff817fdbca: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8181ded0)
Location: net/ipv4/ip_sockglue.c:419
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff8181ded0-ffffffff8181dff1: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8189cde0)
Location: net/ipv4/ip_sockglue.c:423
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff8189cde0-ffffffff8189cf01: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff818f12c0)
Location: net/ipv4/ip_sockglue.c:422
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff818f12c0-ffffffff818f13ef: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8191ee20)
Location: net/ipv4/ip_sockglue.c:419
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff8191ee20-ffffffff8191ef46: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81981740)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81981740-ffffffff81981882: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819b7f80)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff819b7f80-ffffffff819b80c2: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa28a0)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81aa28a0-ffffffff81aa29e4: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aacbb0)
Location: net/ipv4/ip_sockglue.c:437
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81aacbb0-ffffffff81aaccf4: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a97e00)
Location: net/ipv4/ip_sockglue.c:437
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81a97e00-ffffffff81a97f44: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b53290)
Location: net/ipv4/ip_sockglue.c:437
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81b53290-ffffffff81b533d4: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cdf990)
Location: net/ipv4/ip_sockglue.c:439
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81cdf990-ffffffff81cdfadd: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9fd30)
Location: net/ipv4/ip_sockglue.c:440
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81e9fd30-ffffffff81e9fe7d: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efe580)
Location: net/ipv4/ip_sockglue.c:447
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81efe580-ffffffff81efe6cd: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc27a0)
Location: net/ipv4/ip_sockglue.c:445
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81fc27a0-ffffffff81fc28f0: ip_local_error (STB_GLOBAL)
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
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffff800010c69360)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffff800010c69360-ffff800010c69474: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c0d78558)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
c0d78558-c0d7864c: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c000000000d6df10)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
c000000000d6df10-c000000000d6e094: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffe0007cf28c)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffe0007cf28c-ffffffe0007cf374: ip_local_error (STB_GLOBAL)
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
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81957df0)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff81957df0-ffffffff81957f32: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819118e0)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff819118e0-ffffffff81911a22: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819c25c0)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff819c25c0-ffffffff819c2702: ip_local_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip_local_error(struct sock *sk, int err, __be32 daddr, __be16 port, u32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819cbfc0)
Location: net/ipv4/ip_sockglue.c:421
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/xfrm4_output.c:xfrm4_local_error
```
**Symbols:**

```
ffffffff819cbfc0-ffffffff819cc102: ip_local_error (STB_GLOBAL)
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
