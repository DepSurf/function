# Function: <code>tcp_skb_mark_lost_uncond_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81770cb0)
Location: net/ipv4/tcp_input.c:910
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff81770cb0-ffffffff81770d0b: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dcc20)
Location: net/ipv4/tcp_input.c:912
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff817dcc20-ffffffff817dcc7b: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180cd20)
Location: net/ipv4/tcp_input.c:952
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
**Symbols:**

```
ffffffff8180cd20-ffffffff8180cd9b: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182cf90)
Location: net/ipv4/tcp_input.c:957
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff8182cf90-ffffffff8182cff2: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818abea0)
Location: net/ipv4/tcp_input.c:926
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff818abea0-ffffffff818abf02: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819013d0)
Location: net/ipv4/tcp_input.c:953
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
ffffffff819013d0-ffffffff81901432: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192f4c0)
Location: net/ipv4/tcp_input.c:939
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
ffffffff8192f4c0-ffffffff8192f522: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819929f0)
Location: net/ipv4/tcp_input.c:949
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
ffffffff819929f0-ffffffff81992a52: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c9530)
Location: net/ipv4/tcp_input.c:952
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
ffffffff819c9530-ffffffff819c959a: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab5710)
Location: net/ipv4/tcp_input.c:954
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff81ab5710-ffffffff81ab577a: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7c428)
Location: net/ipv4/tcp_input.c:952
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
ffff800010c7c428-ffff800010c7c4d8: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8b394)
Location: net/ipv4/tcp_input.c:952
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
c0d8b394-c0d8b440: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d85f60)
Location: net/ipv4/tcp_input.c:952
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
c000000000d85f60-c000000000d86008: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007ded38)
Location: net/ipv4/tcp_input.c:952
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
ffffffe0007ded38-ffffffe0007dedc8: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
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
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819693a0)
Location: net/ipv4/tcp_input.c:952
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
ffffffff819693a0-ffffffff8196940a: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81922e90)
Location: net/ipv4/tcp_input.c:952
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
ffffffff81922e90-ffffffff81922efa: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d3b70)
Location: net/ipv4/tcp_input.c:952
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
ffffffff819d3b70-ffffffff819d3bda: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_skb_mark_lost_uncond_verify(struct tcp_sock *tp, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dd750)
Location: net/ipv4/tcp_input.c:952
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
**Symbols:**

```
ffffffff819dd750-ffffffff819dd7ba: tcp_skb_mark_lost_uncond_verify (STB_GLOBAL)
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
