# Function: <code>tcp_adjust_pcount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81774e80)
Location: net/ipv4/tcp_output.c:1088
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81774e80-ffffffff81774f85: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e1e20)
Location: net/ipv4/tcp_output.c:1088
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff817e1e20-ffffffff817e1f21: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81812320)
Location: net/ipv4/tcp_output.c:1107
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81812320-ffffffff81812421: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81831c30)
Location: net/ipv4/tcp_output.c:1183
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81831c30-ffffffff81831d24: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b0e50)
Location: net/ipv4/tcp_output.c:1224
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff818b0e50-ffffffff818b0f04: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81906470)
Location: net/ipv4/tcp_output.c:1227
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81906470-ffffffff81906525: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81934580)
Location: net/ipv4/tcp_output.c:1215
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81934580-ffffffff81934635: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:1213
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81998930-ffffffff819989e1: tcp_adjust_pcount (STB_LOCAL)
ffffffff8199ebd2-ffffffff8199ebe5: tcp_adjust_pcount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819cefb0)
Location: net/ipv4/tcp_output.c:1232
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff819cefb0-ffffffff819cf066: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abafe0)
Location: net/ipv4/tcp_output.c:1295
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81abafe0-ffffffff81abb096: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac6380)
Location: net/ipv4/tcp_output.c:1462
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81ac6380-ffffffff81ac6436: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab1580)
Location: net/ipv4/tcp_output.c:1462
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81ab1580-ffffffff81ab1636: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b6e530)
Location: net/ipv4/tcp_output.c:1462
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81b6e530-ffffffff81b6e5e6: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81cfd920)
Location: net/ipv4/tcp_output.c:1459
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81cfd920-ffffffff81cfda04: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec2560)
Location: net/ipv4/tcp_output.c:1456
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81ec2560-ffffffff81ec2644: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f20b60)
Location: net/ipv4/tcp_output.c:1458
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81f20b60-ffffffff81f20c44: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fe5260)
Location: net/ipv4/tcp_output.c:1519
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81fe5260-ffffffff81fe5344: tcp_adjust_pcount (STB_LOCAL)
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
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c81ab8)
Location: net/ipv4/tcp_output.c:1232
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffff800010c81ab8-ffff800010c81bb4: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d90fb8)
Location: net/ipv4/tcp_output.c:1232
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
c0d90fb8-c0d910ac: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d8cb30)
Location: net/ipv4/tcp_output.c:1232
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
c000000000d8cb30-c000000000d8cc48: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e38da)
Location: net/ipv4/tcp_output.c:1232
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffe0007e38da-ffffffe0007e39b2: tcp_adjust_pcount (STB_LOCAL)
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
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8196ee20)
Location: net/ipv4/tcp_output.c:1232
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff8196ee20-ffffffff8196eed6: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81928910)
Location: net/ipv4/tcp_output.c:1232
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81928910-ffffffff819289c6: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d95f0)
Location: net/ipv4/tcp_output.c:1232
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff819d95f0-ffffffff819d96a6: tcp_adjust_pcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_adjust_pcount(struct sock *sk, const struct sk_buff *skb, int decr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e3250)
Location: net/ipv4/tcp_output.c:1232
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff819e3250-ffffffff819e3306: tcp_adjust_pcount (STB_LOCAL)
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
