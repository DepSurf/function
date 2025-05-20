# Function: <code>tcp_v4_md5_hash_headers</code>

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
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff817e7ee0)
Location: net/ipv4/tcp_ipv4.c:1027
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff817e7ee0-ffffffff817e7f8d: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818185f0)
Location: net/ipv4/tcp_ipv4.c:1033
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff818185f0-ffffffff8181869d: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81838c40)
Location: net/ipv4/tcp_ipv4.c:1100
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff81838c40-ffffffff81838cee: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818b8480)
Location: net/ipv4/tcp_ipv4.c:1104
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff818b8480-ffffffff818b8534: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8190ea40)
Location: net/ipv4/tcp_ipv4.c:1166
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff8190ea40-ffffffff8190eaee: tcp_v4_md5_hash_headers.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193ce40)
Location: net/ipv4/tcp_ipv4.c:1176
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff8193ce40-ffffffff8193cf1a: tcp_v4_md5_hash_headers.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a1290)
Location: net/ipv4/tcp_ipv4.c:1177
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff819a1290-ffffffff819a136f: tcp_v4_md5_hash_headers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819d7f40)
Location: net/ipv4/tcp_ipv4.c:1184
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff819d7f40-ffffffff819d801f: tcp_v4_md5_hash_headers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac3f20)
Location: net/ipv4/tcp_ipv4.c:1251
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
**Symbols:**

```
ffffffff81ac3f20-ffffffff81ac4006: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81acf9b0)
Location: net/ipv4/tcp_ipv4.c:1264
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
**Symbols:**

```
ffffffff81acf9b0-ffffffff81acfa96: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abab00)
Location: net/ipv4/tcp_ipv4.c:1279
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
**Symbols:**

```
ffffffff81abab00-ffffffff81ababe6: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b77e50)
Location: net/ipv4/tcp_ipv4.c:1298
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
**Symbols:**

```
ffffffff81b77e50-ffffffff81b77f36: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d07a50)
Location: net/ipv4/tcp_ipv4.c:1306
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
**Symbols:**

```
ffffffff81d07a50-ffffffff81d07b5c: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd3a0)
Location: net/ipv4/tcp_ipv4.c:1374
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
**Symbols:**

```
ffffffff81ecd3a0-ffffffff81ecd4ac: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c070)
Location: net/ipv4/tcp_ipv4.c:1381
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
**Symbols:**

```
ffffffff81f2c070-ffffffff81f2c16e: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_sigpool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff0e30)
Location: net/ipv4/tcp_ipv4.c:1556
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
```
**Symbols:**

```
ffffffff81ff0e30-ffffffff81ff0f07: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8ac10)
Location: net/ipv4/tcp_ipv4.c:1184
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffff800010c8ac10-ffff800010c8ad14: tcp_v4_md5_hash_headers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_v4_md5_hash_headers(struct tcp_md5sig_pool *hp, __be32 daddr, __be32 saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d994e0)
Location: net/ipv4/tcp_ipv4.c:1184
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
c0d994e0-c0d995ec: tcp_v4_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d99680)
Location: net/ipv4/tcp_ipv4.c:1184
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
c000000000d99680-c000000000d997b0: tcp_v4_md5_hash_headers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007ec16e)
Location: net/ipv4/tcp_ipv4.c:1184
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffe0007ec16e-ffffffe0007ec23c: tcp_v4_md5_hash_headers.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81977db0)
Location: net/ipv4/tcp_ipv4.c:1184
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff81977db0-ffffffff81977e8f: tcp_v4_md5_hash_headers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81931870)
Location: net/ipv4/tcp_ipv4.c:1184
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff81931870-ffffffff8193194f: tcp_v4_md5_hash_headers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e2580)
Location: net/ipv4/tcp_ipv4.c:1184
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff819e2580-ffffffff819e265f: tcp_v4_md5_hash_headers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819ec2d0)
Location: net/ipv4/tcp_ipv4.c:1184
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
**Symbols:**

```
ffffffff819ec2d0-ffffffff819ec3af: tcp_v4_md5_hash_headers.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct tcp_md5sig_pool *hp</code> ➡️ <code>struct tcp_sigpool *hp</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
