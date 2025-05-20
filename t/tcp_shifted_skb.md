# Function: <code>tcp_shifted_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176ec50)
Location: net/ipv4/tcp_input.c:1240
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff8176ec50-ffffffff8176eead: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d89a0)
Location: net/ipv4/tcp_input.c:1243
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff817d89a0-ffffffff817d8c39: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81809180)
Location: net/ipv4/tcp_input.c:1285
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81809180-ffffffff81809448: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818296a0)
Location: net/ipv4/tcp_input.c:1291
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff818296a0-ffffffff81829959: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a8970)
Location: net/ipv4/tcp_input.c:1256
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff818a8970-ffffffff818a8bfc: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fdc70)
Location: net/ipv4/tcp_input.c:1283
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff818fdc70-ffffffff818fdefc: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192bd60)
Location: net/ipv4/tcp_input.c:1269
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff8192bd60-ffffffff8192c007: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198f000)
Location: net/ipv4/tcp_input.c:1279
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff8198f000-ffffffff8198f36d: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c5d30)
Location: net/ipv4/tcp_input.c:1282
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff819c5d30-ffffffff819c60a4: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab0e70)
Location: net/ipv4/tcp_input.c:1284
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff81ab0e70-ffffffff81ab1209: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abbec0)
Location: net/ipv4/tcp_input.c:1390
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff81abbec0-ffffffff81abc253: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa6e90)
Location: net/ipv4/tcp_input.c:1390
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff81aa6e90-ffffffff81aa71fe: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b63490)
Location: net/ipv4/tcp_input.c:1422
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff81b63490-ffffffff81b637fb: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf2740)
Location: net/ipv4/tcp_input.c:1431
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff81cf2740-ffffffff81cf2a6f: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb69a0)
Location: net/ipv4/tcp_input.c:1430
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff81eb69a0-ffffffff81eb6ce6: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f14dc0)
Location: net/ipv4/tcp_input.c:1429
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff81f14dc0-ffffffff81f15106: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd9300)
Location: net/ipv4/tcp_input.c:1463
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff81fd9300-ffffffff81fd9646: tcp_shifted_skb (STB_LOCAL)
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
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c795f0)
Location: net/ipv4/tcp_input.c:1282
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffff800010c795f0-ffff800010c79998: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8890c)
Location: net/ipv4/tcp_input.c:1282
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
c0d8890c-c0d88da8: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d81620)
Location: net/ipv4/tcp_input.c:1282
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
c000000000d81620-c000000000d81ab8: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dbb30)
Location: net/ipv4/tcp_input.c:1282
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffe0007dbb30-ffffffe0007dbe46: tcp_shifted_skb (STB_LOCAL)
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
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81965ba0)
Location: net/ipv4/tcp_input.c:1282
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81965ba0-ffffffff81965f14: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191f690)
Location: net/ipv4/tcp_input.c:1282
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff8191f690-ffffffff8191fa04: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d0370)
Location: net/ipv4/tcp_input.c:1282
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff819d0370-ffffffff819d06e4: tcp_shifted_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tcp_shifted_skb(struct sock *sk, struct sk_buff *prev, struct sk_buff *skb, struct tcp_sacktag_state *state, unsigned int pcount, int shifted, int mss, bool dup_sack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d9f00)
Location: net/ipv4/tcp_input.c:1282
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff819d9f00-ffffffff819da274: tcp_shifted_skb (STB_LOCAL)
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
<b>Param added. </b>
<code>struct sk_buff *prev</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, state, pcount, shifted, mss, dup_sack</code> ➡️ <code>sk, prev, skb, state, pcount, shifted, mss, dup_sack</code>
</li>
</ul>
</details>
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
