# Function: <code>__skb_free_datagram_locked</code>

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
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81774620)
Location: net/core/datagram.c:304
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81774620-ffffffff81774722: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a1920)
Location: net/core/datagram.c:312
Inline: False
```
**Symbols:**

```
ffffffff817a1920-ffffffff817a1a22: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817bfe60)
Location: net/core/datagram.c:335
Inline: True
```
**Symbols:**

```
ffffffff817bfe60-ffffffff817bff6e: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81839a10)
Location: net/core/datagram.c:336
Inline: True
```
**Symbols:**

```
ffffffff81839a10-ffffffff81839b30: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81884150)
Location: net/core/datagram.c:334
Inline: True
```
**Symbols:**

```
ffffffff81884150-ffffffff81884263: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a45d0)
Location: net/core/datagram.c:334
Inline: True
```
**Symbols:**

```
ffffffff818a45d0-ffffffff818a46e3: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818efd50)
Location: net/core/datagram.c:333
Inline: True
```
**Symbols:**

```
ffffffff818efd50-ffffffff818efe69: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81921d70)
Location: net/core/datagram.c:333
Inline: True
```
**Symbols:**

```
ffffffff81921d70-ffffffff81921e89: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/datagram.c (ffffffff819f4e10)
Location: net/core/datagram.c:330
Inline: True
```
**Symbols:**

```
ffffffff819f4e10-ffffffff819f4eda: __skb_free_datagram_locked.part.0 (STB_LOCAL)
ffffffff819f4ee0-ffffffff819f4f5f: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/datagram.c (ffffffff819f4740)
Location: net/core/datagram.c:330
Inline: True
```
**Symbols:**

```
ffffffff819f4740-ffffffff819f480a: __skb_free_datagram_locked.part.0 (STB_LOCAL)
ffffffff819f4900-ffffffff819f497f: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819da9d0)
Location: net/core/datagram.c:330
Inline: True
```
**Symbols:**

```
ffffffff819da9d0-ffffffff819dab06: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8b050)
Location: net/core/datagram.c:330
Inline: True
```
**Symbols:**

```
ffffffff81a8b050-ffffffff81a8b186: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c007c0)
Location: net/core/datagram.c:327
Inline: True
```
**Symbols:**

```
ffffffff81c007c0-ffffffff81c00937: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81dafaf0)
Location: net/core/datagram.c:326
Inline: True
```
**Symbols:**

```
ffffffff81dafaf0-ffffffff81dafc00: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e1fd60)
Location: net/core/datagram.c:326
Inline: True
```
**Symbols:**

```
ffffffff81e1fd60-ffffffff81e1fe70: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81edd410)
Location: net/core/datagram.c:327
Inline: True
```
**Symbols:**

```
ffffffff81edd410-ffffffff81edd520: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbc410)
Location: net/core/datagram.c:333
Inline: True
```
**Symbols:**

```
ffff800010bbc410-ffff800010bbc534: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd8960)
Location: net/core/datagram.c:333
Inline: True
```
**Symbols:**

```
c0cd8960-c0cd8a60: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c947b0)
Location: net/core/datagram.c:333
Inline: False
```
**Symbols:**

```
c000000000c947b0-c000000000c9496c: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074b120)
Location: net/core/datagram.c:333
Inline: True
```
**Symbols:**

```
ffffffe00074b120-ffffffe00074b232: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c1d70)
Location: net/core/datagram.c:333
Inline: True
```
**Symbols:**

```
ffffffff818c1d70-ffffffff818c1e89: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187bcb0)
Location: net/core/datagram.c:333
Inline: True
```
**Symbols:**

```
ffffffff8187bcb0-ffffffff8187bdc9: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81912d70)
Location: net/core/datagram.c:333
Inline: True
```
**Symbols:**

```
ffffffff81912d70-ffffffff81912e89: __skb_free_datagram_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __skb_free_datagram_locked(struct sock *sk, struct sk_buff *skb, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81933ef0)
Location: net/core/datagram.c:333
Inline: True
```
**Symbols:**

```
ffffffff81933ef0-ffffffff81934009: __skb_free_datagram_locked (STB_GLOBAL)
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
