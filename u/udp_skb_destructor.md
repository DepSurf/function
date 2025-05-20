# Function: <code>udp_skb_destructor</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81824c40)
Location: net/ipv4/udp.c:1209
Inline: False
```
**Symbols:**

```
ffffffff81824c40-ffffffff81824c59: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81845a60)
Location: net/ipv4/udp.c:1241
Inline: False
```
**Symbols:**

```
ffffffff81845a60-ffffffff81845a87: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c54a0)
Location: net/ipv4/udp.c:1248
Inline: False
```
**Symbols:**

```
ffffffff818c54a0-ffffffff818c54c7: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191d790)
Location: net/ipv4/udp.c:1318
Inline: False
```
**Symbols:**

```
ffffffff8191d790-ffffffff8191d7b7: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194c710)
Location: net/ipv4/udp.c:1386
Inline: False
```
**Symbols:**

```
ffffffff8194c710-ffffffff8194c737: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b0eb0)
Location: net/ipv4/udp.c:1373
Inline: False
```
**Symbols:**

```
ffffffff819b0eb0-ffffffff819b0ed7: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e79c0)
Location: net/ipv4/udp.c:1408
Inline: False
```
**Symbols:**

```
ffffffff819e79c0-ffffffff819e79e7: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad430a)
Location: net/ipv4/udp.c:1414
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81ad3ef0-ffffffff81ad3f17: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae087a)
Location: net/ipv4/udp.c:1464
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81ae0430-ffffffff81ae0457: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81acc850)
Location: net/ipv4/udp.c:1483
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81acc450-ffffffff81acc477: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b8b0e0)
Location: net/ipv4/udp.c:1484
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81b8ace0-ffffffff81b8ad07: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1aed6)
Location: net/ipv4/udp.c:1484
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81d1a240-ffffffff81d1a273: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee2476)
Location: net/ipv4/udp.c:1495
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81ee0ed0-ffffffff81ee0f03: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f41f76)
Location: net/ipv4/udp.c:1467
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81f407e0-ffffffff81f40813: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82007e06)
Location: net/ipv4/udp.c:1442
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff82006430-ffffffff82006463: udp_skb_destructor (STB_GLOBAL)
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
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9b8c0)
Location: net/ipv4/udp.c:1408
Inline: False
```
**Symbols:**

```
ffff800010c9b8c0-ffff800010c9b908: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da75a4)
Location: net/ipv4/udp.c:1408
Inline: False
```
**Symbols:**

```
c0da75a4-c0da75d4: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000daafc0)
Location: net/ipv4/udp.c:1408
Inline: False
```
**Symbols:**

```
c000000000daafc0-c000000000daaff0: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f9bec)
Location: net/ipv4/udp.c:1408
Inline: False
```
**Symbols:**

```
ffffffe0007f9bec-ffffffe0007f9c28: udp_skb_destructor (STB_GLOBAL)
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
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81987830)
Location: net/ipv4/udp.c:1408
Inline: False
```
**Symbols:**

```
ffffffff81987830-ffffffff81987857: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819412f0)
Location: net/ipv4/udp.c:1408
Inline: False
```
**Symbols:**

```
ffffffff819412f0-ffffffff81941317: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f2000)
Location: net/ipv4/udp.c:1408
Inline: False
```
**Symbols:**

```
ffffffff819f2000-ffffffff819f2027: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void udp_skb_destructor(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f9180)
Location: net/ipv4/udp.c:1408
Inline: False
```
**Symbols:**

```
ffffffff819f9180-ffffffff819f91a7: udp_skb_destructor (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
