# Function: <code>tcp_mark_skb_lost</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81916dc0)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff81916dc0-ffffffff81916e0e: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819455a0)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff819455a0-ffffffff819455ee: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819a9ba0)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff819a9ba0-ffffffff819a9bee: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819e0860)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff819e0860-ffffffff819e08ae: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81acdf68)
Location: net/ipv4/tcp_recovery.c:5
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
```
**Symbols:**

```
ffffffff81acdfd0-ffffffff81ace01e: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac0810)
Location: net/ipv4/tcp_input.c:1045
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff81ac0810-ffffffff81ac08a1: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aab6d0)
Location: net/ipv4/tcp_input.c:1045
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff81aab6d0-ffffffff81aab761: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b67b10)
Location: net/ipv4/tcp_input.c:1077
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff81b67b10-ffffffff81b67ba1: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf6bf0)
Location: net/ipv4/tcp_input.c:1086
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff81cf6bf0-ffffffff81cf6cae: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebb630)
Location: net/ipv4/tcp_input.c:1085
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff81ebb630-ffffffff81ebb6ee: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f19ab0)
Location: net/ipv4/tcp_input.c:1084
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff81f19ab0-ffffffff81f19b6e: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fde280)
Location: net/ipv4/tcp_input.c:1118
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff81fde280-ffffffff81fde33e: tcp_mark_skb_lost (STB_GLOBAL)
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
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffff800010c945e0)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffff800010c945e0-ffff800010c9466c: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c0da2e18)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
c0da2e18-c0da2e8c: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c000000000da4d50)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
c000000000da4d50-c000000000da4e14: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffe0007f3a32)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffe0007f3a32-ffffffe0007f3ab8: tcp_mark_skb_lost (STB_GLOBAL)
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
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819806d0)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff819806d0-ffffffff8198071e: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff8193a190)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff8193a190-ffffffff8193a1de: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819eaea0)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff819eaea0-ffffffff819eaeee: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_mark_skb_lost(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819f4d20)
Location: net/ipv4/tcp_recovery.c:5
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
ffffffff819f4d20-ffffffff819f4d6e: tcp_mark_skb_lost (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
