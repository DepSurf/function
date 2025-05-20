# Function: <code>ipv6_push_exthdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff817f2fc0)
Location: net/ipv6/exthdrs.c:680
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
```
**Symbols:**

```
ffffffff817f2fc0-ffffffff817f3035: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81861e00)
Location: net/ipv6/exthdrs.c:707
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81861e00-ffffffff81861e77: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81893d70)
Location: net/ipv6/exthdrs.c:923
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81893d70-ffffffff81893de7: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff818ba360)
Location: net/ipv6/exthdrs.c:925
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff818ba360-ffffffff818ba3d7: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff8193d340)
Location: net/ipv6/exthdrs.c:975
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff8193d340-ffffffff8193d3b7: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81996350)
Location: net/ipv6/exthdrs.c:962
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81996350-ffffffff819963c9: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819ccc60)
Location: net/ipv6/exthdrs.c:962
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff819ccc60-ffffffff819cccd9: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a3b720)
Location: net/ipv6/exthdrs.c:958
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81a3b720-ffffffff81a3b795: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a723a0)
Location: net/ipv6/exthdrs.c:958
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81a723a0-ffffffff81a72415: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6bb90)
Location: net/ipv6/exthdrs.c:1155
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81b6bb90-ffffffff81b6bc02: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b7a600)
Location: net/ipv6/exthdrs.c:1150
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81b7a600-ffffffff81b7a672: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b69050)
Location: net/ipv6/exthdrs.c:1150
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81b69050-ffffffff81b690c2: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81c30ca0)
Location: net/ipv6/exthdrs.c:1198
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81c30ca0-ffffffff81c30d12: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81dceae0)
Location: net/ipv6/exthdrs.c:1199
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81dceae0-ffffffff81dceb60: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81f9fcb0)
Location: net/ipv6/exthdrs.c:1199
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81f9fcb0-ffffffff81f9fd30: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff82000790)
Location: net/ipv6/exthdrs.c:1166
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff82000790-ffffffff82000810: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820cf5d0)
Location: net/ipv6/exthdrs.c:1171
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff820cf5d0-ffffffff820cf650: ipv6_push_exthdr (STB_LOCAL)
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
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffff800010d3ac60)
Location: net/ipv6/exthdrs.c:958
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffff800010d3ac60-ffff800010d3acd0: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c0e3d5f4)
Location: net/ipv6/exthdrs.c:958
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
c0e3d5f4-c0e3d64c: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c000000000e6e3d0)
Location: net/ipv6/exthdrs.c:958
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
c000000000e6e3d0-c000000000e6e45c: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffe0008779e4)
Location: net/ipv6/exthdrs.c:958
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffe0008779e4-ffffffe000877a4c: ipv6_push_exthdr (STB_LOCAL)
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
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a11a30)
Location: net/ipv6/exthdrs.c:958
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81a11a30-ffffffff81a11aa5: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819ce7f0)
Location: net/ipv6/exthdrs.c:958
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff819ce7f0-ffffffff819ce865: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a7c4b0)
Location: net/ipv6/exthdrs.c:958
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81a7c4b0-ffffffff81a7c525: ipv6_push_exthdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipv6_push_exthdr(struct sk_buff *skb, u8 *proto, u8 type, struct ipv6_opt_hdr *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a88d00)
Location: net/ipv6/exthdrs.c:958
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_frag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81a88d00-ffffffff81a88d75: ipv6_push_exthdr (STB_LOCAL)
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
