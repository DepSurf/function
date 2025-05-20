# Function: <code>ip_frag_next</code>

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
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197b260)
Location: net/ipv4/ip_output.c:684
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff8197b260-ffffffff8197b3de: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b1bd0)
Location: net/ipv4/ip_output.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff819b1bd0-ffffffff819b1d58: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9c460)
Location: net/ipv4/ip_output.c:681
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81a9c460-ffffffff81a9c5e8: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa62c0)
Location: net/ipv4/ip_output.c:688
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81aa62c0-ffffffff81aa6448: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a91480)
Location: net/ipv4/ip_output.c:689
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81a91480-ffffffff81a91608: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: net/ipv4/ip_output.c:676
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81d3a172-ffffffff81d3a187: ip_frag_next.cold (STB_LOCAL)
ffffffff81b4c830-ffffffff81b4c9d5: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: net/ipv4/ip_output.c:676
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81f068f0-ffffffff81f06905: ip_frag_next.cold (STB_LOCAL)
ffffffff81cd9ef0-ffffffff81cda0ad: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: net/ipv4/ip_output.c:676
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff820ae3d1-ffffffff820ae3e6: ip_frag_next.cold (STB_LOCAL)
ffffffff81e9a6a0-ffffffff81e9a85d: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: net/ipv4/ip_output.c:678
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff8212f8f1-ffffffff8212f906: ip_frag_next.cold (STB_LOCAL)
ffffffff81ef9020-ffffffff81ef91dd: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: net/ipv4/ip_output.c:679
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff8221167b-ffffffff82211690: ip_frag_next.cold (STB_LOCAL)
ffffffff81fbcf40-ffffffff81fbd0fd: ip_frag_next (STB_GLOBAL)
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
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c624f8)
Location: net/ipv4/ip_output.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffff800010c624f8-ffff800010c626f0: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d71da4)
Location: net/ipv4/ip_output.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
c0d71da4-c0d71f48: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d65970)
Location: net/ipv4/ip_output.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
c000000000d65970-c000000000d65bac: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007ca13a)
Location: net/ipv4/ip_output.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffe0007ca13a-ffffffe0007ca2d2: ip_frag_next (STB_GLOBAL)
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
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81951a40)
Location: net/ipv4/ip_output.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81951a40-ffffffff81951bc8: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190b530)
Location: net/ipv4/ip_output.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff8190b530-ffffffff8190b6b8: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bc210)
Location: net/ipv4/ip_output.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff819bc210-ffffffff819bc398: ip_frag_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *ip_frag_next(struct sk_buff *skb, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c5b20)
Location: net/ipv4/ip_output.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff819c5b20-ffffffff819c5ca8: ip_frag_next (STB_GLOBAL)
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
