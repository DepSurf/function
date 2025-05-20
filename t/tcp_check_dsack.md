# Function: <code>tcp_check_dsack</code>

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
In net/ipv4/tcp_input.c (ffffffff8176f3dc)
Location: net/ipv4/tcp_input.c:1051
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff817d9199)
Location: net/ipv4/tcp_input.c:1053
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff818099c9)
Location: net/ipv4/tcp_input.c:1094
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff81829ed3)
Location: net/ipv4/tcp_input.c:1099
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff818a90be)
Location: net/ipv4/tcp_input.c:1067
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff818fe3f1)
Location: net/ipv4/tcp_input.c:1094
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff8192c4f1)
Location: net/ipv4/tcp_input.c:1080
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff8198f8a6)
Location: net/ipv4/tcp_input.c:1090
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff819c65e2)
Location: net/ipv4/tcp_input.c:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab5ec2)
Location: net/ipv4/tcp_input.c:1095
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_check_dsack(struct sock *sk, const struct sk_buff *ack_skb, struct tcp_sack_block_wire *sp, int num_sacks, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aba980)
Location: net/ipv4/tcp_input.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81aba980-ffffffff81abaabd: tcp_check_dsack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_check_dsack(struct sock *sk, const struct sk_buff *ack_skb, struct tcp_sack_block_wire *sp, int num_sacks, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa5c60)
Location: net/ipv4/tcp_input.c:1209
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81aa5c60-ffffffff81aa5da7: tcp_check_dsack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcp_check_dsack(struct sock *sk, const struct sk_buff *ack_skb, struct tcp_sack_block_wire *sp, int num_sacks, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b61fd0)
Location: net/ipv4/tcp_input.c:1241
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81b61fd0-ffffffff81b62162: tcp_check_dsack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcp_check_dsack(struct sock *sk, const struct sk_buff *ack_skb, struct tcp_sack_block_wire *sp, int num_sacks, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf0be0)
Location: net/ipv4/tcp_input.c:1250
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81cf0be0-ffffffff81cf0d8f: tcp_check_dsack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_check_dsack(struct sock *sk, const struct sk_buff *ack_skb, struct tcp_sack_block_wire *sp, int num_sacks, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb53a0)
Location: net/ipv4/tcp_input.c:1249
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81eb53a0-ffffffff81eb554f: tcp_check_dsack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_check_dsack(struct sock *sk, const struct sk_buff *ack_skb, struct tcp_sack_block_wire *sp, int num_sacks, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f137d0)
Location: net/ipv4/tcp_input.c:1248
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81f137d0-ffffffff81f1397f: tcp_check_dsack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_check_dsack(struct sock *sk, const struct sk_buff *ack_skb, struct tcp_sack_block_wire *sp, int num_sacks, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd7cb0)
Location: net/ipv4/tcp_input.c:1282
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
**Symbols:**

```
ffffffff81fd7cb0-ffffffff81fd7e5f: tcp_check_dsack (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffff800010c7ade0)
Location: net/ipv4/tcp_input.c:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (c0d8a4e0)
Location: net/ipv4/tcp_input.c:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (c000000000d82184)
Location: net/ipv4/tcp_input.c:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffe0007dc242)
Location: net/ipv4/tcp_input.c:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff81966452)
Location: net/ipv4/tcp_input.c:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff8191ff42)
Location: net/ipv4/tcp_input.c:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff819d0c22)
Location: net/ipv4/tcp_input.c:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
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
In net/ipv4/tcp_input.c (ffffffff819da7b2)
Location: net/ipv4/tcp_input.c:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
