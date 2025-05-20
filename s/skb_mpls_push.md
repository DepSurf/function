# Function: <code>skb_mpls_push</code>

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
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ea2b0)
Location: net/core/skbuff.c:5473
Inline: False
```
**Symbols:**

```
ffffffff818ea2b0-ffffffff818ea492: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191c430)
Location: net/core/skbuff.c:5486
Inline: False
```
**Symbols:**

```
ffffffff8191c430-ffffffff8191c60e: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5591
Inline: False
```
**Symbols:**

```
ffffffff819f4a85-ffffffff819f4a9d: skb_mpls_push.cold (STB_LOCAL)
ffffffff819f0530-ffffffff819f07ba: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5726
Inline: False
```
**Symbols:**

```
ffffffff81c309fe-ffffffff81c30a16: skb_mpls_push.cold (STB_LOCAL)
ffffffff819f0280-ffffffff819f0517: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5814
Inline: False
```
**Symbols:**

```
ffffffff81c22cd3-ffffffff81c22ceb: skb_mpls_push.cold (STB_LOCAL)
ffffffff819d4bc0-ffffffff819d4e53: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5889
Inline: False
```
**Symbols:**

```
ffffffff81d3525b-ffffffff81d35273: skb_mpls_push.cold (STB_LOCAL)
ffffffff81a84950-ffffffff81a84be3: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5810
Inline: False
```
**Symbols:**

```
ffffffff81f0183b-ffffffff81f01853: skb_mpls_push.cold (STB_LOCAL)
ffffffff81bfa970-ffffffff81bfabc2: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da9800)
Location: net/core/skbuff.c:6012
Inline: False
```
**Symbols:**

```
ffffffff81da9800-ffffffff81da9a6b: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e18300)
Location: net/core/skbuff.c:6063
Inline: False
```
**Symbols:**

```
ffffffff81e18300-ffffffff81e1856b: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed57a0)
Location: net/core/skbuff.c:6216
Inline: False
```
**Symbols:**

```
ffffffff81ed57a0-ffffffff81ed5a0b: skb_mpls_push (STB_GLOBAL)
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
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb6a28)
Location: net/core/skbuff.c:5486
Inline: False
```
**Symbols:**

```
ffff800010bb6a28-ffff800010bb6bf0: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd3884)
Location: net/core/skbuff.c:5486
Inline: False
```
**Symbols:**

```
c0cd3884-c0cd3a44: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8e300)
Location: net/core/skbuff.c:5486
Inline: False
```
**Symbols:**

```
c000000000c8e300-c000000000c8e540: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007466ce)
Location: net/core/skbuff.c:5486
Inline: False
```
**Symbols:**

```
ffffffe0007466ce-ffffffe000746864: skb_mpls_push (STB_GLOBAL)
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
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bc430)
Location: net/core/skbuff.c:5486
Inline: False
```
**Symbols:**

```
ffffffff818bc430-ffffffff818bc60e: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81876370)
Location: net/core/skbuff.c:5486
Inline: False
```
**Symbols:**

```
ffffffff81876370-ffffffff8187654e: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190d430)
Location: net/core/skbuff.c:5486
Inline: False
```
**Symbols:**

```
ffffffff8190d430-ffffffff8190d60e: skb_mpls_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_mpls_push(struct sk_buff *skb, __be32 mpls_lse, __be16 mpls_proto, int mac_len, bool ethernet);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192e560)
Location: net/core/skbuff.c:5486
Inline: False
```
**Symbols:**

```
ffffffff8192e560-ffffffff8192e73e: skb_mpls_push (STB_GLOBAL)
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
<b>Param added. </b>
<code>int mac_len</code>
</li>
<li>
<b>Param added. </b>
<code>bool ethernet</code>
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
