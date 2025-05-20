# Function: <code>udp6_lib_lookup_skb</code>

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
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81851ff0)
Location: net/ipv6/udp.c:290
Inline: False
```
**Symbols:**

```
ffffffff81851ff0-ffffffff81852053: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81883db0)
Location: net/ipv6/udp.c:290
Inline: False
```
**Symbols:**

```
ffffffff81883db0-ffffffff81883e13: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818aa090)
Location: net/ipv6/udp.c:300
Inline: False
```
**Symbols:**

```
ffffffff818aa090-ffffffff818aa0e9: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8192caa0)
Location: net/ipv6/udp.c:304
Inline: False
```
**Symbols:**

```
ffffffff8192caa0-ffffffff8192cb1d: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81985b50)
Location: net/ipv6/udp.c:274
Inline: False
```
**Symbols:**

```
ffffffff81985b50-ffffffff81985bcd: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bc180)
Location: net/ipv6/udp.c:238
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff819bc180-ffffffff819bc1fd: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a2acd0)
Location: net/ipv6/udp.c:224
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81a2acd0-ffffffff81a2ad4a: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a61830)
Location: net/ipv6/udp.c:224
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81a61830-ffffffff81a618aa: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b5a230)
Location: net/ipv6/udp.c:227
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81b5a230-ffffffff81b5a2ac: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b68ee0)
Location: net/ipv6/udp.c:279
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81b68ee0-ffffffff81b68f59: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b57050)
Location: net/ipv6/udp.c:279
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81b57050-ffffffff81b570c9: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81c1e600)
Location: net/ipv6/udp.c:281
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81c1e600-ffffffff81c1e679: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81dbae30)
Location: net/ipv6/udp.c:283
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81dbae30-ffffffff81dbaec1: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81f8aef0)
Location: net/ipv6/udp.c:297
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81f8aef0-ffffffff81f8af86: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81feb5c0)
Location: net/ipv6/udp.c:308
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81feb5c0-ffffffff81feb666: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff820b9280)
Location: net/ipv6/udp.c:275
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff820b9280-ffffffff820b9326: udp6_lib_lookup_skb (STB_GLOBAL)
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
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffff800010d24bd8)
Location: net/ipv6/udp.c:224
Inline: False
```
**Symbols:**

```
ffff800010d24bd8-ffff800010d24c70: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c0e2b95c)
Location: net/ipv6/udp.c:224
Inline: False
```
**Symbols:**

```
c0e2b95c-c0e2b9ec: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c000000000e574a0)
Location: net/ipv6/udp.c:224
Inline: False
```
**Symbols:**

```
c000000000e574a0-c000000000e5758c: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffe0008688fe)
Location: net/ipv6/udp.c:224
Inline: False
```
**Symbols:**

```
ffffffe0008688fe-ffffffe000868970: udp6_lib_lookup_skb (STB_GLOBAL)
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
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a00ec0)
Location: net/ipv6/udp.c:224
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81a00ec0-ffffffff81a00f3a: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bdc80)
Location: net/ipv6/udp.c:224
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff819bdc80-ffffffff819bdcfa: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a6b940)
Location: net/ipv6/udp.c:224
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81a6b940-ffffffff81a6b9ba: udp6_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a77f50)
Location: net/ipv6/udp.c:224
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff81a77f50-ffffffff81a77fca: udp6_lib_lookup_skb (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sk_buff *skb</code> ➡️ <code>const struct sk_buff *skb</code>
</li>
</ul>
</details>
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
