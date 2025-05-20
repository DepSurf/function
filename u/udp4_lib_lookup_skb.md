# Function: <code>udp4_lib_lookup_skb</code>

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
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f6b50)
Location: net/ipv4/udp.c:571
Inline: False
```
**Symbols:**

```
ffffffff817f6b50-ffffffff817f6bb7: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81827ab0)
Location: net/ipv4/udp.c:572
Inline: False
```
**Symbols:**

```
ffffffff81827ab0-ffffffff81827b17: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81849270)
Location: net/ipv4/udp.c:560
Inline: False
```
**Symbols:**

```
ffffffff81849270-ffffffff818492cc: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c8d10)
Location: net/ipv4/udp.c:563
Inline: False
```
**Symbols:**

```
ffffffff818c8d10-ffffffff818c8d82: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191ee70)
Location: net/ipv4/udp.c:537
Inline: False
```
**Symbols:**

```
ffffffff8191ee70-ffffffff8191eedf: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194c580)
Location: net/ipv4/udp.c:503
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff8194c580-ffffffff8194c5ef: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b0b50)
Location: net/ipv4/udp.c:487
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff819b0b50-ffffffff819b0bc0: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e7780)
Location: net/ipv4/udp.c:487
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff819e7780-ffffffff819e77f0: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad3a50)
Location: net/ipv4/udp.c:493
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
**Symbols:**

```
ffffffff81ad3a50-ffffffff81ad3ac1: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae3770)
Location: net/ipv4/udp.c:544
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81ae3770-ffffffff81ae37e1: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ace780)
Location: net/ipv4/udp.c:544
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81ace780-ffffffff81ace7f7: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b8d150)
Location: net/ipv4/udp.c:545
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81b8d150-ffffffff81b8d1c7: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1e2d0)
Location: net/ipv4/udp.c:545
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81d1e2d0-ffffffff81d1e360: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee5350)
Location: net/ipv4/udp.c:552
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81ee5350-ffffffff81ee53e5: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f44af0)
Location: net/ipv4/udp.c:564
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff81f44af0-ffffffff81f44bc7: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(const struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8200ab40)
Location: net/ipv4/udp.c:534
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
```
**Symbols:**

```
ffffffff8200ab40-ffffffff8200ac17: udp4_lib_lookup_skb (STB_GLOBAL)
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
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9b2a0)
Location: net/ipv4/udp.c:487
Inline: False
```
**Symbols:**

```
ffff800010c9b2a0-ffff800010c9b340: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0dab918)
Location: net/ipv4/udp.c:487
Inline: False
```
**Symbols:**

```
c0dab918-c0dab9b8: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000db0d50)
Location: net/ipv4/udp.c:487
Inline: False
```
**Symbols:**

```
c000000000db0d50-c000000000db0e1c: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007fa38c)
Location: net/ipv4/udp.c:487
Inline: False
```
**Symbols:**

```
ffffffe0007fa38c-ffffffe0007fa40a: udp4_lib_lookup_skb (STB_GLOBAL)
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
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819875f0)
Location: net/ipv4/udp.c:487
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff819875f0-ffffffff81987660: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819410b0)
Location: net/ipv4/udp.c:487
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff819410b0-ffffffff81941120: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f1dc0)
Location: net/ipv4/udp.c:487
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff819f1dc0-ffffffff819f1e30: udp4_lib_lookup_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup_skb(struct sk_buff *skb, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819fd5d0)
Location: net/ipv4/udp.c:487
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp_gro_complete
  - net/ipv4/udp_offload.c:udp_gro_receive
```
**Symbols:**

```
ffffffff819fd5d0-ffffffff819fd640: udp4_lib_lookup_skb (STB_GLOBAL)
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
