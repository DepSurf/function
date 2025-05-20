# Function: <code>tcp_update_skb_after_send</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b584e)
Location: net/ipv4/tcp_output.c:1017
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/ipv4/tcp_output.c (ffffffff8190b096)
Location: net/ipv4/tcp_output.c:1013
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819344e0)
Location: net/ipv4/tcp_output.c:978
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff819344e0-ffffffff81934574: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81998170)
Location: net/ipv4/tcp_output.c:978
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81998170-ffffffff81998200: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819ceb40)
Location: net/ipv4/tcp_output.c:982
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff819ceb40-ffffffff819cebd0: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abad10)
Location: net/ipv4/tcp_output.c:1045
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81abad10-ffffffff81abada0: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac60b0)
Location: net/ipv4/tcp_output.c:1199
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81ac60b0-ffffffff81ac6140: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab12b0)
Location: net/ipv4/tcp_output.c:1199
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81ab12b0-ffffffff81ab1343: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b6e110)
Location: net/ipv4/tcp_output.c:1199
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81b6e110-ffffffff81b6e1a3: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81cfd550)
Location: net/ipv4/tcp_output.c:1198
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81cfd550-ffffffff81cfd5f4: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec2120)
Location: net/ipv4/tcp_output.c:1195
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81ec2120-ffffffff81ec21c4: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f20690)
Location: net/ipv4/tcp_output.c:1197
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81f20690-ffffffff81f20734: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fe4cf0)
Location: net/ipv4/tcp_output.c:1242
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81fe4cf0-ffffffff81fe4d94: tcp_update_skb_after_send (STB_LOCAL)
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
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c81540)
Location: net/ipv4/tcp_output.c:982
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffff800010c81540-ffff800010c815f4: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d90954)
Location: net/ipv4/tcp_output.c:982
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
c0d90954-c0d90a74: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d8c480)
Location: net/ipv4/tcp_output.c:982
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
c000000000d8c480-c000000000d8c51c: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e33c8)
Location: net/ipv4/tcp_output.c:982
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffe0007e33c8-ffffffe0007e3460: tcp_update_skb_after_send (STB_LOCAL)
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
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8196e9b0)
Location: net/ipv4/tcp_output.c:982
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff8196e9b0-ffffffff8196ea40: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819284a0)
Location: net/ipv4/tcp_output.c:982
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff819284a0-ffffffff81928530: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d9180)
Location: net/ipv4/tcp_output.c:982
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff819d9180-ffffffff819d9210: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock *sk, struct sk_buff *skb, u64 prior_wstamp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e2de0)
Location: net/ipv4/tcp_output.c:982
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff819e2de0-ffffffff819e2e70: tcp_update_skb_after_send (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
