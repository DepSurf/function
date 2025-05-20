# Function: <code>seg6_push_hmac</code>

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
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff818a4f50)
Location: net/ipv6/seg6_hmac.c:330
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff818a4f50-ffffffff818a4ff5: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff818cb9b0)
Location: net/ipv6/seg6_hmac.c:330
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff818cb9b0-ffffffff818cba5a: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81950750)
Location: net/ipv6/seg6_hmac.c:331
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81950750-ffffffff819507fa: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff819a9c40)
Location: net/ipv6/seg6_hmac.c:331
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff819a9c40-ffffffff819a9cf5: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff819e0760)
Location: net/ipv6/seg6_hmac.c:332
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff819e0760-ffffffff819e0815: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a4f3c0)
Location: net/ipv6/seg6_hmac.c:327
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81a4f3c0-ffffffff81a4f461: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a86050)
Location: net/ipv6/seg6_hmac.c:327
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81a86050-ffffffff81a860f1: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81b81080)
Location: net/ipv6/seg6_hmac.c:326
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81b81080-ffffffff81b81121: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81b908a0)
Location: net/ipv6/seg6_hmac.c:325
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81b908a0-ffffffff81b90951: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81b7fac0)
Location: net/ipv6/seg6_hmac.c:325
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81b7fac0-ffffffff81b7fb71: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81c4b360)
Location: net/ipv6/seg6_hmac.c:325
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81c4b360-ffffffff81c4b411: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81deacc0)
Location: net/ipv6/seg6_hmac.c:325
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81deacc0-ffffffff81deada1: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81fbe890)
Location: net/ipv6/seg6_hmac.c:325
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81fbe890-ffffffff81fbe971: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff8201f730)
Location: net/ipv6/seg6_hmac.c:325
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff8201f730-ffffffff8201f811: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff820ee860)
Location: net/ipv6/seg6_hmac.c:325
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_rthdr4
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff820ee860-ffffffff820ee941: seg6_push_hmac (STB_GLOBAL)
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
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffff800010d52958)
Location: net/ipv6/seg6_hmac.c:327
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffff800010d52958-ffff800010d52a18: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (c0e52ba4)
Location: net/ipv6/seg6_hmac.c:327
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
c0e52ba4-c0e52ca0: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (c000000000e8b050)
Location: net/ipv6/seg6_hmac.c:327
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
c000000000e8b050-c000000000e8b110: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffe00088a8e0)
Location: net/ipv6/seg6_hmac.c:327
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffe00088a8e0-ffffffe00088a982: seg6_push_hmac (STB_GLOBAL)
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
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a256e0)
Location: net/ipv6/seg6_hmac.c:327
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81a256e0-ffffffff81a25781: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff819e24a0)
Location: net/ipv6/seg6_hmac.c:327
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff819e24a0-ffffffff819e2541: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a90160)
Location: net/ipv6/seg6_hmac.c:327
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81a90160-ffffffff81a90201: seg6_push_hmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seg6_push_hmac(struct net *net, struct in6_addr *saddr, struct ipv6_sr_hdr *srh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a9d430)
Location: net/ipv6/seg6_hmac.c:327
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
**Symbols:**

```
ffffffff81a9d430-ffffffff81a9d658: seg6_push_hmac (STB_GLOBAL)
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
