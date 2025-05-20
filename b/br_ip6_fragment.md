# Function: <code>br_ip6_fragment</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_ct_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_ct_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81a48510)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
ffffffff81a48510-ffffffff81a48851: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81a7f0c0)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
ffffffff81a7f0c0-ffffffff81a7f432: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81b79d80)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
ffffffff81b79d80-ffffffff81b7a0d1: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81b88cd0)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
ffffffff81b88cd0-ffffffff81b89021: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81b77af0)
Location: net/ipv6/netfilter.c:117
Inline: False
```
**Symbols:**

```
ffffffff81b77af0-ffffffff81b77e45: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81c42610)
Location: net/ipv6/netfilter.c:117
Inline: False
```
**Symbols:**

```
ffffffff81c42610-ffffffff81c42965: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81de1070)
Location: net/ipv6/netfilter.c:122
Inline: False
```
**Symbols:**

```
ffffffff81de1070-ffffffff81de14ea: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81fb34d0)
Location: net/ipv6/netfilter.c:122
Inline: False
```
**Symbols:**

```
ffffffff81fb34d0-ffffffff81fb394a: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff82013bc0)
Location: net/ipv6/netfilter.c:122
Inline: False
```
**Symbols:**

```
ffffffff82013bc0-ffffffff820140e1: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff820e2d20)
Location: net/ipv6/netfilter.c:122
Inline: False
```
**Symbols:**

```
ffffffff820e2d20-ffffffff820e3238: br_ip6_fragment (STB_GLOBAL)
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
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffff800010d4a370)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
ffff800010d4a370-ffff800010d4a698: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (c0e4b96c)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
c0e4b96c-c0e4bcec: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (c000000000e80350)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
c000000000e80350-c000000000e807d8: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffe000883892)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
ffffffe000883892-ffffffe000883b10: br_ip6_fragment (STB_GLOBAL)
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
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81a1e750)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
ffffffff81a1e750-ffffffff81a1eac2: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff819db510)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
ffffffff819db510-ffffffff819db882: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81a891d0)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
ffffffff81a891d0-ffffffff81a89542: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int br_ip6_fragment(struct net *net, struct sock *sk, struct sk_buff *skb, struct nf_bridge_frag_data *data, int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff81a95e30)
Location: net/ipv6/netfilter.c:115
Inline: False
```
**Symbols:**

```
ffffffff81a95e30-ffffffff81a961a2: br_ip6_fragment (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct nf_ct_bridge_frag_data *data</code> ➡️ <code>struct nf_bridge_frag_data *data</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*output)(struct net *, struct sock *, const struct nf_ct_bridge_frag_data *, struct sk_buff *)</code> ➡️ <code>int (*output)(struct net *, struct sock *, const struct nf_bridge_frag_data *, struct sk_buff *)</code>
</li>
</ul>
</details>
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
