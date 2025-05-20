# Function: <code>tcp_sacktag_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, const struct skb_mstamp *xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176c290)
Location: net/ipv4/tcp_input.c:1153
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff8176c290-ffffffff8176c4b9: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, const struct skb_mstamp *xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d7b40)
Location: net/ipv4/tcp_input.c:1155
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff817d7b40-ffffffff817d7d8c: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, const struct skb_mstamp *xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81807ae0)
Location: net/ipv4/tcp_input.c:1197
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81807ae0-ffffffff81807d2c: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81829440)
Location: net/ipv4/tcp_input.c:1203
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81829440-ffffffff81829691: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a8750)
Location: net/ipv4/tcp_input.c:1172
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff818a8750-ffffffff818a896d: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fda30)
Location: net/ipv4/tcp_input.c:1199
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff818fda30-ffffffff818fdc67: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192bb20)
Location: net/ipv4/tcp_input.c:1185
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff8192bb20-ffffffff8192bd57: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198edd0)
Location: net/ipv4/tcp_input.c:1195
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff8198edd0-ffffffff8198effd: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c5740)
Location: net/ipv4/tcp_input.c:1198
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff819c5740-ffffffff819c596d: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aaffe0)
Location: net/ipv4/tcp_input.c:1200
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81aaffe0-ffffffff81ab020d: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abb070)
Location: net/ipv4/tcp_input.c:1305
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81abb070-ffffffff81abb29b: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa6030)
Location: net/ipv4/tcp_input.c:1305
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81aa6030-ffffffff81aa625b: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b62410)
Location: net/ipv4/tcp_input.c:1337
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81b62410-ffffffff81b62643: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf16d0)
Location: net/ipv4/tcp_input.c:1346
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81cf16d0-ffffffff81cf1938: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb5ee0)
Location: net/ipv4/tcp_input.c:1345
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81eb5ee0-ffffffff81eb6148: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f14300)
Location: net/ipv4/tcp_input.c:1344
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81f14300-ffffffff81f14565: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd87e0)
Location: net/ipv4/tcp_input.c:1378
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff81fd87e0-ffffffff81fd8a45: tcp_sacktag_one (STB_LOCAL)
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
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c77df8)
Location: net/ipv4/tcp_input.c:1198
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffff800010c77df8-ffff800010c78048: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d85a3c)
Location: net/ipv4/tcp_input.c:1198
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
c0d85a3c-c0d85c84: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d812f0)
Location: net/ipv4/tcp_input.c:1198
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
c000000000d812f0-c000000000d81620: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007db946)
Location: net/ipv4/tcp_input.c:1198
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffe0007db946-ffffffe0007dbb30: tcp_sacktag_one (STB_LOCAL)
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
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819655b0)
Location: net/ipv4/tcp_input.c:1198
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff819655b0-ffffffff819657dd: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191f0a0)
Location: net/ipv4/tcp_input.c:1198
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff8191f0a0-ffffffff8191f2cd: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cfd80)
Location: net/ipv4/tcp_input.c:1198
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff819cfd80-ffffffff819cffad: tcp_sacktag_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u8 tcp_sacktag_one(struct sock *sk, struct tcp_sacktag_state *state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d9910)
Location: net/ipv4/tcp_input.c:1198
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
**Symbols:**

```
ffffffff819d9910-ffffffff819d9b3d: tcp_sacktag_one (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct skb_mstamp *xmit_time</code> ➡️ <code>u64 xmit_time</code>
</li>
</ul>
</details>
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
