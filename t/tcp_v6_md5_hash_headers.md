# Function: <code>tcp_v6_md5_hash_headers</code>

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
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool *hp, const struct in6_addr *daddr, const struct in6_addr *saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff8185d540)
Location: net/ipv6/tcp_ipv6.c:533
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff8185d540-ffffffff8185d5f7: tcp_v6_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool *hp, const struct in6_addr *daddr, const struct in6_addr *saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff8188f580)
Location: net/ipv6/tcp_ipv6.c:542
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff8188f580-ffffffff8188f637: tcp_v6_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool *hp, const struct in6_addr *daddr, const struct in6_addr *saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff818b5bb0)
Location: net/ipv6/tcp_ipv6.c:565
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff818b5bb0-ffffffff818b5c71: tcp_v6_md5_hash_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool *hp, const struct in6_addr *daddr, const struct in6_addr *saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81938950)
Location: net/ipv6/tcp_ipv6.c:567
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81938950-ffffffff81938a17: tcp_v6_md5_hash_headers (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81992060)
Location: net/ipv6/tcp_ipv6.c:581
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81992060-ffffffff81992111: tcp_v6_md5_hash_headers.isra.22 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff819c88d0)
Location: net/ipv6/tcp_ipv6.c:584
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff819c88d0-ffffffff819c89b1: tcp_v6_md5_hash_headers.isra.25 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81a37250)
Location: net/ipv6/tcp_ipv6.c:591
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81a37250-ffffffff81a3733a: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81a6dd70)
Location: net/ipv6/tcp_ipv6.c:593
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81a6dd70-ffffffff81a6de5a: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81b67320)
Location: net/ipv6/tcp_ipv6.c:636
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81b67320-ffffffff81b67416: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81b75b20)
Location: net/ipv6/tcp_ipv6.c:647
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81b75b20-ffffffff81b75c16: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81b64550)
Location: net/ipv6/tcp_ipv6.c:662
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81b64550-ffffffff81b64646: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81c2bef0)
Location: net/ipv6/tcp_ipv6.c:665
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81c2bef0-ffffffff81c2bfe6: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81dc9560)
Location: net/ipv6/tcp_ipv6.c:669
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81dc9560-ffffffff81dc967c: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81f9a300)
Location: net/ipv6/tcp_ipv6.c:676
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81f9a300-ffffffff81f9a41c: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81ffad20)
Location: net/ipv6/tcp_ipv6.c:673
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81ffad20-ffffffff81ffae2b: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff820c8740)
Location: net/ipv6/tcp_ipv6.c:693
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff820c8740-ffffffff820c8824: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffff800010d36568)
Location: net/ipv6/tcp_ipv6.c:593
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffff800010d36568-ffff800010d36670: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool *hp, const struct in6_addr *daddr, const struct in6_addr *saddr, const struct tcphdr *th, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c0e383f8)
Location: net/ipv6/tcp_ipv6.c:593
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
c0e383f8-c0e38518: tcp_v6_md5_hash_headers (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (c000000000e68ba0)
Location: net/ipv6/tcp_ipv6.c:593
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
c000000000e68ba0-c000000000e68cf4: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffe000873bd4)
Location: net/ipv6/tcp_ipv6.c:593
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffe000873bd4-ffffffe000873ce6: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81a0d400)
Location: net/ipv6/tcp_ipv6.c:593
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81a0d400-ffffffff81a0d4ea: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff819ca1c0)
Location: net/ipv6/tcp_ipv6.c:593
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff819ca1c0-ffffffff819ca2aa: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81a77e80)
Location: net/ipv6/tcp_ipv6.c:593
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81a77e80-ffffffff81a77f6a: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81a845f0)
Location: net/ipv6/tcp_ipv6.c:593
Inline: True
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
**Symbols:**

```
ffffffff81a845f0-ffffffff81a846da: tcp_v6_md5_hash_headers.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
