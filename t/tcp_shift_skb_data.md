# Function: <code>tcp_shift_skb_data</code>

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
In net/ipv4/tcp_input.c (ffffffff8176ef21)
Location: net/ipv4/tcp_input.c:1334
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff817d8cb6)
Location: net/ipv4/tcp_input.c:1339
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff818094c5)
Location: net/ipv4/tcp_input.c:1385
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff818299ce)
Location: net/ipv4/tcp_input.c:1391
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff818a8c59)
Location: net/ipv4/tcp_input.c:1355
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff818fdf57)
Location: net/ipv4/tcp_input.c:1382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff8192c064)
Location: net/ipv4/tcp_input.c:1368
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff8198f3b9)
Location: net/ipv4/tcp_input.c:1393
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff819c60f9)
Location: net/ipv4/tcp_input.c:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *tcp_shift_skb_data(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, u32 start_seq, u32 end_seq, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab5950)
Location: net/ipv4/tcp_input.c:1398
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81ab5950-ffffffff81ab5c7e: tcp_shift_skb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *tcp_shift_skb_data(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, u32 start_seq, u32 end_seq, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac0cb0)
Location: net/ipv4/tcp_input.c:1504
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81ac0cb0-ffffffff81ac0fe0: tcp_shift_skb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *tcp_shift_skb_data(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, u32 start_seq, u32 end_seq, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aabc60)
Location: net/ipv4/tcp_input.c:1504
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81aabc60-ffffffff81aabf8e: tcp_shift_skb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *tcp_shift_skb_data(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, u32 start_seq, u32 end_seq, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b680a0)
Location: net/ipv4/tcp_input.c:1536
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81b680a0-ffffffff81b68466: tcp_shift_skb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *tcp_shift_skb_data(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, u32 start_seq, u32 end_seq, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf7200)
Location: net/ipv4/tcp_input.c:1545
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81cf7200-ffffffff81cf75c0: tcp_shift_skb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *tcp_shift_skb_data(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, u32 start_seq, u32 end_seq, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebbc90)
Location: net/ipv4/tcp_input.c:1544
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81ebbc90-ffffffff81ebc044: tcp_shift_skb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *tcp_shift_skb_data(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, u32 start_seq, u32 end_seq, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1a110)
Location: net/ipv4/tcp_input.c:1543
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81f1a110-ffffffff81f1a4d9: tcp_shift_skb_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *tcp_shift_skb_data(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, u32 start_seq, u32 end_seq, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fde8e0)
Location: net/ipv4/tcp_input.c:1577
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81fde8e0-ffffffff81fdeca9: tcp_shift_skb_data (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffff800010c79a00)
Location: net/ipv4/tcp_input.c:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (c0d89fb4)
Location: net/ipv4/tcp_input.c:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (c000000000d81b94)
Location: net/ipv4/tcp_input.c:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffe0007dbe80)
Location: net/ipv4/tcp_input.c:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff81965f69)
Location: net/ipv4/tcp_input.c:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff8191fa59)
Location: net/ipv4/tcp_input.c:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff819d0739)
Location: net/ipv4/tcp_input.c:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/ipv4/tcp_input.c (ffffffff819da2c9)
Location: net/ipv4/tcp_input.c:1396
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
