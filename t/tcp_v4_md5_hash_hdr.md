# Function: <code>tcp_v4_md5_hash_hdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8177ad30)
Location: net/ipv4/tcp_ipv4.c:1043
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8177ad30-ffffffff8177ae11: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff817e80e0)
Location: net/ipv4/tcp_ipv4.c:1052
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff817e80e0-ffffffff817e81cf: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818187f0)
Location: net/ipv4/tcp_ipv4.c:1058
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff818187f0-ffffffff818188df: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81838e40)
Location: net/ipv4/tcp_ipv4.c:1125
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81838e40-ffffffff81838f2f: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818b86a0)
Location: net/ipv4/tcp_ipv4.c:1129
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff818b86a0-ffffffff818b879a: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8190ec50)
Location: net/ipv4/tcp_ipv4.c:1191
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8190ec50-ffffffff8190ed51: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193d080)
Location: net/ipv4/tcp_ipv4.c:1201
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff8193d080-ffffffff8193d181: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a14d0)
Location: net/ipv4/tcp_ipv4.c:1202
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819a14d0-ffffffff819a15ce: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819d8180)
Location: net/ipv4/tcp_ipv4.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819d8180-ffffffff819d827e: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5850)
Location: net/ipv4/tcp_ipv4.c:1276
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81ac5850-ffffffff81ac593c: tcp_v4_md5_hash_hdr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad14c0)
Location: net/ipv4/tcp_ipv4.c:1289
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81ad14c0-ffffffff81ad15ac: tcp_v4_md5_hash_hdr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abc4b0)
Location: net/ipv4/tcp_ipv4.c:1304
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81abc4b0-ffffffff81abc59c: tcp_v4_md5_hash_hdr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b795d0)
Location: net/ipv4/tcp_ipv4.c:1323
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81b795d0-ffffffff81b796bc: tcp_v4_md5_hash_hdr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d090d0)
Location: net/ipv4/tcp_ipv4.c:1331
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81d090d0-ffffffff81d091d0: tcp_v4_md5_hash_hdr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ecdf60)
Location: net/ipv4/tcp_ipv4.c:1399
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81ecdf60-ffffffff81ece060: tcp_v4_md5_hash_hdr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d3d0)
Location: net/ipv4/tcp_ipv4.c:1406
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81f2d3d0-ffffffff81f2d4d1: tcp_v4_md5_hash_hdr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1ab0)
Location: net/ipv4/tcp_ipv4.c:1581
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81ff1ab0-ffffffff81ff1bcf: tcp_v4_md5_hash_hdr.isra.0 (STB_LOCAL)
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
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8ae50)
Location: net/ipv4/tcp_ipv4.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffff800010c8ae50-ffff800010c8af48: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d9972c)
Location: net/ipv4/tcp_ipv4.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
c0d9972c-c0d9982c: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d99980)
Location: net/ipv4/tcp_ipv4.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
c000000000d99980-c000000000d99aec: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007ec502)
Location: net/ipv4/tcp_ipv4.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffe0007ec502-ffffffe0007ec5ec: tcp_v4_md5_hash_hdr (STB_LOCAL)
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
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81977ff0)
Location: net/ipv4/tcp_ipv4.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81977ff0-ffffffff819780ee: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81931ab0)
Location: net/ipv4/tcp_ipv4.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff81931ab0-ffffffff81931bae: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e27c0)
Location: net/ipv4/tcp_ipv4.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819e27c0-ffffffff819e28be: tcp_v4_md5_hash_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_v4_md5_hash_hdr(char *md5_hash, const struct tcp_md5sig_key *key, __be32 daddr, __be32 saddr, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819ec510)
Location: net/ipv4/tcp_ipv4.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
**Symbols:**

```
ffffffff819ec510-ffffffff819ec60e: tcp_v4_md5_hash_hdr (STB_LOCAL)
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
