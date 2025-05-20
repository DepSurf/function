# Function: <code>ip6_frag_next</code>

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
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a012f0)
Location: net/ipv6/ip6_output.c:686
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a012f0-ffffffff81a014cf: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a37ed0)
Location: net/ipv6/ip6_output.c:686
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a37ed0-ffffffff81a380af: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2dee0)
Location: net/ipv6/ip6_output.c:687
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b2dee0-ffffffff81b2e0bf: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3c930)
Location: net/ipv6/ip6_output.c:724
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b3c930-ffffffff81b3cb0f: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b29da0)
Location: net/ipv6/ip6_output.c:755
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81b29da0-ffffffff81b29f7f: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81bef970)
Location: net/ipv6/ip6_output.c:736
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81bef970-ffffffff81befb4f: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81d884d0)
Location: net/ipv6/ip6_output.c:758
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81d884d0-ffffffff81d886be: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81f56190)
Location: net/ipv6/ip6_output.c:771
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81f56190-ffffffff81f5637e: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81fb5b70)
Location: net/ipv6/ip6_output.c:772
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81fb5b70-ffffffff81fb5d5e: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff82083240)
Location: net/ipv6/ip6_output.c:782
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff82083240-ffffffff8208342e: ip6_frag_next (STB_GLOBAL)
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
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cf86a0)
Location: net/ipv6/ip6_output.c:686
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffff800010cf86a0-ffff800010cf8884: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0dffda4)
Location: net/ipv6/ip6_output.c:686
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
c0dffda4-c0dfff78: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e206b0)
Location: net/ipv6/ip6_output.c:686
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
c000000000e206b0-c000000000e2092c: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe00084440a)
Location: net/ipv6/ip6_output.c:686
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffe00084440a-ffffffe0008445cc: ip6_frag_next (STB_GLOBAL)
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
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819d7560)
Location: net/ipv6/ip6_output.c:686
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff819d7560-ffffffff819d773f: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81994320)
Location: net/ipv6/ip6_output.c:686
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81994320-ffffffff819944ff: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a41fe0)
Location: net/ipv6/ip6_output.c:686
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a41fe0-ffffffff81a421bf: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *ip6_frag_next(struct sk_buff *skb, struct ip6_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a4dc70)
Location: net/ipv6/ip6_output.c:686
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
**Symbols:**

```
ffffffff81a4dc70-ffffffff81a4de4f: ip6_frag_next (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
