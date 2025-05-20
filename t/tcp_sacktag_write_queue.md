# Function: <code>tcp_sacktag_write_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176f330)
Location: net/ipv4/tcp_input.c:1590
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8176f330-ffffffff8176fc49: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d90f0)
Location: net/ipv4/tcp_input.c:1598
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff817d90f0-ffffffff817d9a79: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81809920)
Location: net/ipv4/tcp_input.c:1645
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81809920-ffffffff8180a2b1: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81829e30)
Location: net/ipv4/tcp_input.c:1651
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81829e30-ffffffff8182a73b: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a9050)
Location: net/ipv4/tcp_input.c:1625
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff818a9050-ffffffff818a98a3: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fe380)
Location: net/ipv4/tcp_input.c:1649
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff818fe380-ffffffff818febcb: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192c480)
Location: net/ipv4/tcp_input.c:1635
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8192c480-ffffffff8192ccdb: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:1656
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8198f830-ffffffff81990077: tcp_sacktag_write_queue (STB_LOCAL)
ffffffff81997f92-ffffffff81997fff: tcp_sacktag_write_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c6570)
Location: net/ipv4/tcp_input.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819c6570-ffffffff819c6dfc: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab5e50)
Location: net/ipv4/tcp_input.c:1661
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ab5e50-ffffffff81ab66c7: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac11b0)
Location: net/ipv4/tcp_input.c:1767
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ac11b0-ffffffff81ac194d: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aac160)
Location: net/ipv4/tcp_input.c:1767
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81aac160-ffffffff81aac8fe: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b68640)
Location: net/ipv4/tcp_input.c:1801
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81b68640-ffffffff81b693e1: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf77c0)
Location: net/ipv4/tcp_input.c:1810
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81cf77c0-ffffffff81cf85be: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebc270)
Location: net/ipv4/tcp_input.c:1809
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ebc270-ffffffff81ebd06e: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1a6e0)
Location: net/ipv4/tcp_input.c:1808
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81f1a6e0-ffffffff81f1b4ec: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fdeeb0)
Location: net/ipv4/tcp_input.c:1842
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81fdeeb0-ffffffff81fdfcbc: tcp_sacktag_write_queue (STB_LOCAL)
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
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7ad60)
Location: net/ipv4/tcp_input.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffff800010c7ad60-ffff800010c7b614: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8a464)
Location: net/ipv4/tcp_input.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c0d8a464-c0d8ae84: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d820e0)
Location: net/ipv4/tcp_input.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c000000000d820e0-c000000000d82bc8: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dc1e2)
Location: net/ipv4/tcp_input.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffe0007dc1e2-ffffffe0007dc942: tcp_sacktag_write_queue (STB_LOCAL)
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
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819663e0)
Location: net/ipv4/tcp_input.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819663e0-ffffffff81966c6c: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191fed0)
Location: net/ipv4/tcp_input.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8191fed0-ffffffff8192075c: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d0bb0)
Location: net/ipv4/tcp_input.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819d0bb0-ffffffff819d143c: tcp_sacktag_write_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_sacktag_write_queue(struct sock *sk, const struct sk_buff *ack_skb, u32 prior_snd_una, struct tcp_sacktag_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819da740)
Location: net/ipv4/tcp_input.c:1659
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819da740-ffffffff819dafcc: tcp_sacktag_write_queue (STB_LOCAL)
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
