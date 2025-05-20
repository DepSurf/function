# Function: <code>tcp_rcv_established</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81772b40)
Location: net/ipv4/tcp_input.c:5228
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81772b40-ffffffff817732ba: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dfa60)
Location: net/ipv4/tcp_input.c:5287
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff817dfa60-ffffffff817e014b: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180fe30)
Location: net/ipv4/tcp_input.c:5372
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8180fe30-ffffffff8181051c: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182fd10)
Location: net/ipv4/tcp_input.c:5363
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8182fd10-ffffffff81830473: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818af5b0)
Location: net/ipv4/tcp_input.c:5295
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff818af5b0-ffffffff818afb3c: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81904c60)
Location: net/ipv4/tcp_input.c:5450
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81904c60-ffffffff81905280: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81932e20)
Location: net/ipv4/tcp_input.c:5493
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81932e20-ffffffff8193345f: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819966d0)
Location: net/ipv4/tcp_input.c:5498
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff819966d0-ffffffff81996d4f: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cd250)
Location: net/ipv4/tcp_input.c:5549
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff819cd250-ffffffff819cd8cf: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab93b0)
Location: net/ipv4/tcp_input.c:5591
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81ab93b0-ffffffff81ab9a33: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac47b0)
Location: net/ipv4/tcp_input.c:5723
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81ac47b0-ffffffff81ac4e3b: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aaf8a0)
Location: net/ipv4/tcp_input.c:5731
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81aaf8a0-ffffffff81aaff27: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:5765
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81d3acb9-ffffffff81d3accd: tcp_rcv_established.cold (STB_LOCAL)
ffffffff81b6c640-ffffffff81b6cd07: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:5823
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81f07566-ffffffff81f0757b: tcp_rcv_established.cold (STB_LOCAL)
ffffffff81cfbaa0-ffffffff81cfc1cb: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:5845
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff820aefde-ffffffff820aeff3: tcp_rcv_established.cold (STB_LOCAL)
ffffffff81ec0620-ffffffff81ec0d4b: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:5852
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff821303d4-ffffffff821303e9: tcp_rcv_established.cold (STB_LOCAL)
ffffffff81f1eb90-ffffffff81f1f2bb: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:5998
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff82211dfd-ffffffff82211e12: tcp_rcv_established.cold (STB_LOCAL)
ffffffff81fe3220-ffffffff81fe3983: tcp_rcv_established (STB_GLOBAL)
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
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7fd90)
Location: net/ipv4/tcp_input.c:5549
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffff800010c7fd90-ffff800010c80440: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8ef5c)
Location: net/ipv4/tcp_input.c:5549
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
c0d8ef5c-c0d8f600: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d8a810)
Location: net/ipv4/tcp_input.c:5549
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
c000000000d8a810-c000000000d8afc8: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e1e48)
Location: net/ipv4/tcp_input.c:5549
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffe0007e1e48-ffffffe0007e2432: tcp_rcv_established (STB_GLOBAL)
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
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196d0c0)
Location: net/ipv4/tcp_input.c:5549
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8196d0c0-ffffffff8196d73f: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81926bb0)
Location: net/ipv4/tcp_input.c:5549
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81926bb0-ffffffff8192722f: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d7890)
Location: net/ipv4/tcp_input.c:5549
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff819d7890-ffffffff819d7f0f: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_rcv_established(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819e14b0)
Location: net/ipv4/tcp_input.c:5549
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff819e14b0-ffffffff819e1b48: tcp_rcv_established (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int len</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct tcphdr *th</code>
</li>
</ul>
</details>
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
