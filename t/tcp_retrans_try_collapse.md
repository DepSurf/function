# Function: <code>tcp_retrans_try_collapse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817784eb)
Location: net/ipv4/tcp_output.c:2513
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e5660)
Location: net/ipv4/tcp_output.c:2549
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81815aed)
Location: net/ipv4/tcp_output.c:2673
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81835e97)
Location: net/ipv4/tcp_output.c:2748
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b5494)
Location: net/ipv4/tcp_output.c:2797
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190aba9)
Location: net/ipv4/tcp_output.c:2772
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81938e5a)
Location: net/ipv4/tcp_output.c:2802
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199d09e)
Location: net/ipv4/tcp_output.c:2829
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d3b5e)
Location: net/ipv4/tcp_output.c:2856
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_retrans_try_collapse(struct sock *sk, struct sk_buff *to, int space);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac0330)
Location: net/ipv4/tcp_output.c:2925
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81ac0330-ffffffff81ac0477: tcp_retrans_try_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_retrans_try_collapse(struct sock *sk, struct sk_buff *to, int space);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acbd90)
Location: net/ipv4/tcp_output.c:3097
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81acbd90-ffffffff81acbeda: tcp_retrans_try_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_retrans_try_collapse(struct sock *sk, struct sk_buff *to, int space);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab6fd0)
Location: net/ipv4/tcp_output.c:3102
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81ab6fd0-ffffffff81ab7119: tcp_retrans_try_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_retrans_try_collapse(struct sock *sk, struct sk_buff *to, int space);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b741c0)
Location: net/ipv4/tcp_output.c:3102
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81b741c0-ffffffff81b74306: tcp_retrans_try_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_retrans_try_collapse(struct sock *sk, struct sk_buff *to, int space);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d03670)
Location: net/ipv4/tcp_output.c:3098
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81d03670-ffffffff81d039fc: tcp_retrans_try_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_retrans_try_collapse(struct sock *sk, struct sk_buff *to, int space);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec85b0)
Location: net/ipv4/tcp_output.c:3100
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81ec85b0-ffffffff81ec895c: tcp_retrans_try_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_retrans_try_collapse(struct sock *sk, struct sk_buff *to, int space);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f270d0)
Location: net/ipv4/tcp_output.c:3182
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
**Symbols:**

```
ffffffff81f270d0-ffffffff81f2747d: tcp_retrans_try_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_retrans_try_collapse(struct sock *sk, struct sk_buff *to, int space);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81febac0)
Location: net/ipv4/tcp_output.c:3240
Inline: False
```
**Symbols:**

```
ffffffff81febac0-ffffffff81febe6d: tcp_retrans_try_collapse (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c8658c)
Location: net/ipv4/tcp_output.c:2856
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d95a44)
Location: net/ipv4/tcp_output.c:2856
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d92bec)
Location: net/ipv4/tcp_output.c:2856
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e7ba6)
Location: net/ipv4/tcp_output.c:2856
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819739ce)
Location: net/ipv4/tcp_output.c:2856
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192d49e)
Location: net/ipv4/tcp_output.c:2856
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819de19e)
Location: net/ipv4/tcp_output.c:2856
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e7e1e)
Location: net/ipv4/tcp_output.c:2856
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
