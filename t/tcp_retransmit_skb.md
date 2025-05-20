# Function: <code>tcp_retransmit_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81778ba0)
Location: net/ipv4/tcp_output.c:2647
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
```
**Symbols:**

```
ffffffff81778ba0-ffffffff81778c27: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e5ce0)
Location: net/ipv4/tcp_output.c:2688
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff817e5ce0-ffffffff817e5daf: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81816160)
Location: net/ipv4/tcp_output.c:2808
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81816160-ffffffff8181622f: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81836500)
Location: net/ipv4/tcp_output.c:2885
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81836500-ffffffff818365cd: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b5b50)
Location: net/ipv4/tcp_output.c:2942
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff818b5b50-ffffffff818b5c1d: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190b2e0)
Location: net/ipv4/tcp_output.c:2923
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff8190b2e0-ffffffff8190b3ab: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81939590)
Location: net/ipv4/tcp_output.c:2954
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81939590-ffffffff81939654: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199d880)
Location: net/ipv4/tcp_output.c:2985
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff8199d880-ffffffff8199d93f: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d4350)
Location: net/ipv4/tcp_output.c:3016
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819d4350-ffffffff819d440f: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac0bd0)
Location: net/ipv4/tcp_output.c:3085
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81ac0bd0-ffffffff81ac0c8f: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acc640)
Location: net/ipv4/tcp_output.c:3257
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81acc640-ffffffff81acc6ff: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab7800)
Location: net/ipv4/tcp_output.c:3254
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81ab7800-ffffffff81ab78bf: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b74a20)
Location: net/ipv4/tcp_output.c:3254
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81b74a20-ffffffff81b74adc: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d04180)
Location: net/ipv4/tcp_output.c:3259
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81d04180-ffffffff81d04249: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec90e0)
Location: net/ipv4/tcp_output.c:3261
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81ec90e0-ffffffff81ec91a9: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f27c00)
Location: net/ipv4/tcp_output.c:3343
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81f27c00-ffffffff81f27cc9: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fec690)
Location: net/ipv4/tcp_output.c:3407
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff81fec690-ffffffff81fec77e: tcp_retransmit_skb (STB_GLOBAL)
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
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c86e28)
Location: net/ipv4/tcp_output.c:3016
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffff800010c86e28-ffff800010c86f1c: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d9623c)
Location: net/ipv4/tcp_output.c:3016
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
c0d9623c-c0d96340: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d936c0)
Location: net/ipv4/tcp_output.c:3016
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
c000000000d936c0-c000000000d937f0: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e8342)
Location: net/ipv4/tcp_output.c:3016
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffe0007e8342-ffffffe0007e841e: tcp_retransmit_skb (STB_GLOBAL)
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
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819741c0)
Location: net/ipv4/tcp_output.c:3016
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819741c0-ffffffff8197427f: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192dc90)
Location: net/ipv4/tcp_output.c:3016
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff8192dc90-ffffffff8192dd4f: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819de990)
Location: net/ipv4/tcp_output.c:3016
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819de990-ffffffff819dea4f: tcp_retransmit_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_retransmit_skb(struct sock *sk, struct sk_buff *skb, int segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e8630)
Location: net/ipv4/tcp_output.c:3016
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
**Symbols:**

```
ffffffff819e8630-ffffffff819e86ef: tcp_retransmit_skb (STB_GLOBAL)
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
<code>int segs</code>
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
