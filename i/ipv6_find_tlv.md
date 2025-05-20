# Function: <code>ipv6_find_tlv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_find_tlv(struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff817ffaf0)
Location: net/ipv6/exthdrs_core.c:115
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff817ffaf0-ffffffff817ffb73: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff818711a0)
Location: net/ipv6/exthdrs_core.c:115
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff818711a0-ffffffff81871220: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff818a56f0)
Location: net/ipv6/exthdrs_core.c:115
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff818a56f0-ffffffff818a5770: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff818cc180)
Location: net/ipv6/exthdrs_core.c:115
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff818cc180-ffffffff818cc200: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81950f30)
Location: net/ipv6/exthdrs_core.c:115
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81950f30-ffffffff81950fb0: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819aa4b0)
Location: net/ipv6/exthdrs_core.c:115
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff819aa4b0-ffffffff819aa52e: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819e0fc0)
Location: net/ipv6/exthdrs_core.c:115
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff819e0fc0-ffffffff819e103e: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a4fd70)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81a4fd70-ffffffff81a4fdf6: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a869c0)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81a869c0-ffffffff81a86a46: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b81c70)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81b81c70-ffffffff81b81d00: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b91360)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81b91360-ffffffff81b913ec: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b80560)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81b80560-ffffffff81b805ec: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81c4c580)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81c4c580-ffffffff81c4c60c: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81dec930)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81dec930-ffffffff81dec9ca: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81fc0700)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81fc0700-ffffffff81fc079a: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff82021670)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff82021670-ffffffff8202170f: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff820f07a0)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff820f07a0-ffffffff820f083f: ipv6_find_tlv (STB_GLOBAL)
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
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffff800010d53008)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffff800010d53008-ffff800010d530c0: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (c0e53998)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
c0e53998-c0e53a34: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (c000000000e8b660)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
c000000000e8b660-c000000000e8b714: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffe00088adf0)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffe00088adf0-ffffffe00088ae70: ipv6_find_tlv (STB_GLOBAL)
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
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a26050)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81a26050-ffffffff81a260d6: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819e2e10)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff819e2e10-ffffffff819e2e96: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a91c00)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81a91c00-ffffffff81a91c86: ipv6_find_tlv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_find_tlv(const struct sk_buff *skb, int offset, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a9dcb0)
Location: net/ipv6/exthdrs_core.c:116
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/calipso.c:calipso_skbuff_optptr
  - net/ipv6/output_core.c:ip6_find_1stfragopt
```
**Symbols:**

```
ffffffff81a9dcb0-ffffffff81a9dd36: ipv6_find_tlv (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>struct sk_buff *skb</code> ➡️ <code>const struct sk_buff *skb</code>
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
