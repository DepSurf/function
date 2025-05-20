# Function: <code>udp_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff **udp_gro_receive(struct sk_buff **head, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8178b460)
Location: net/ipv4/udp_offload.c:293
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff8178b460-ffffffff8178b582: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff **udp_gro_receive(struct sk_buff **head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff817f84e0)
Location: net/ipv4/udp_offload.c:250
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff817f84e0-ffffffff817f8623: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff **udp_gro_receive(struct sk_buff **head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81829390)
Location: net/ipv4/udp_offload.c:252
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81829390-ffffffff818294e0: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff **udp_gro_receive(struct sk_buff **head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8184ab50)
Location: net/ipv4/udp_offload.c:255
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff8184ab50-ffffffff8184ac94: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff **udp_gro_receive(struct sk_buff **head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff818ca7f0)
Location: net/ipv4/udp_offload.c:247
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff818ca7f0-ffffffff818ca939: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff **udp_gro_receive(struct sk_buff **head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81920360)
Location: net/ipv4/udp_offload.c:346
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81920360-ffffffff819204b1: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8194f050)
Location: net/ipv4/udp_offload.c:397
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff8194f050-ffffffff8194f2f4: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819b3840)
Location: net/ipv4/udp_offload.c:406
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff819b3840-ffffffff819b3b3f: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819ea570)
Location: net/ipv4/udp_offload.c:406
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff819ea570-ffffffff819ea86f: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad82d0)
Location: net/ipv4/udp_offload.c:447
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81ad82d0-ffffffff81ad84cf: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ae57a0)
Location: net/ipv4/udp_offload.c:509
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81ae57a0-ffffffff81ae59a5: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad0a80)
Location: net/ipv4/udp_offload.c:509
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81ad0a80-ffffffff81ad0c9e: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81b8f4a0)
Location: net/ipv4/udp_offload.c:509
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81b8f4a0-ffffffff81b8f6be: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81d207b0)
Location: net/ipv4/udp_offload.c:537
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81d207b0-ffffffff81d209c4: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ee7a10)
Location: net/ipv4/udp_offload.c:538
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81ee7a10-ffffffff81ee7c24: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81f47290)
Location: net/ipv4/udp_offload.c:545
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81f47290-ffffffff81f4749d: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8200d3d0)
Location: net/ipv4/udp_offload.c:545
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff8200d3d0-ffffffff8200d5d6: udp_gro_receive (STB_GLOBAL)
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
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffff800010ca0128)
Location: net/ipv4/udp_offload.c:406
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffff800010ca0128-ffff800010ca0470: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (c0dad078)
Location: net/ipv4/udp_offload.c:406
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
c0dad078-c0dad398: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (c000000000db3920)
Location: net/ipv4/udp_offload.c:406
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
c000000000db3920-c000000000db3d28: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffe0007fc876)
Location: net/ipv4/udp_offload.c:406
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffe0007fc876-ffffffe0007fcb0e: udp_gro_receive (STB_GLOBAL)
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
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8198a3e0)
Location: net/ipv4/udp_offload.c:406
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff8198a3e0-ffffffff8198a6df: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81943ea0)
Location: net/ipv4/udp_offload.c:406
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81943ea0-ffffffff8194419f: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819f4bb0)
Location: net/ipv4/udp_offload.c:406
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff819f4bb0-ffffffff819f4eaf: udp_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *udp_gro_receive(struct list_head *head, struct sk_buff *skb, struct udphdr *uh, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819fed80)
Location: net/ipv4/udp_offload.c:406
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff819fed80-ffffffff819ff091: udp_gro_receive (STB_GLOBAL)
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
<b>Param added. </b>
<code>udp_lookup_t lookup</code>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sk_buff **head</code> ➡️ <code>struct list_head *head</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct sk_buff **</code> ➡️ <code>struct sk_buff *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sock *sk</code>
</li>
<li>
<b>Param removed. </b>
<code>udp_lookup_t lookup</code>
</li>
</ul>
</details>
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
