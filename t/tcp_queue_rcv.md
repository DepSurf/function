# Function: <code>tcp_queue_rcv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, int hdrlen, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176cc40)
Location: net/ipv4/tcp_input.c:4467
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff8176cc40-ffffffff8176cd77: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, int hdrlen, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817da100)
Location: net/ipv4/tcp_input.c:4531
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff817da100-ffffffff817da237: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, int hdrlen, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180a590)
Location: net/ipv4/tcp_input.c:4564
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff8180a590-ffffffff8180a6c7: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, int hdrlen, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182b430)
Location: net/ipv4/tcp_input.c:4524
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff8182b430-ffffffff8182b58b: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, int hdrlen, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a9bd0)
Location: net/ipv4/tcp_input.c:4501
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff818a9bd0-ffffffff818a9d2e: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, int hdrlen, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fecd0)
Location: net/ipv4/tcp_input.c:4601
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff818fecd0-ffffffff818fee31: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192cf10)
Location: net/ipv4/tcp_input.c:4618
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff8192cf10-ffffffff8192d02d: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81990310)
Location: net/ipv4/tcp_input.c:4629
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81990310-ffffffff8199042d: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c7090)
Location: net/ipv4/tcp_input.c:4680
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff819c7090-ffffffff819c71ad: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab1c20)
Location: net/ipv4/tcp_input.c:4718
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81ab1c20-ffffffff81ab1d3d: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abcbe0)
Location: net/ipv4/tcp_input.c:4856
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81abcbe0-ffffffff81abccfd: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa8260)
Location: net/ipv4/tcp_input.c:4866
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81aa8260-ffffffff81aa837d: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b63e20)
Location: net/ipv4/tcp_input.c:4900
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81b63e20-ffffffff81b63f45: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf2b40)
Location: net/ipv4/tcp_input.c:4921
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81cf2b40-ffffffff81cf2c5a: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb7140)
Location: net/ipv4/tcp_input.c:4934
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81eb7140-ffffffff81eb725a: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f15560)
Location: net/ipv4/tcp_input.c:4939
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81f15560-ffffffff81f1567a: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd9bc0)
Location: net/ipv4/tcp_input.c:5071
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81fd9bc0-ffffffff81fd9d00: tcp_queue_rcv (STB_LOCAL)
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
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c79f80)
Location: net/ipv4/tcp_input.c:4680
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffff800010c79f80-ffff800010c7a0c0: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d87684)
Location: net/ipv4/tcp_input.c:4680
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
c0d87684-c0d877b4: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d83410)
Location: net/ipv4/tcp_input.c:4680
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
c000000000d83410-c000000000d835c8: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dcb82)
Location: net/ipv4/tcp_input.c:4680
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffe0007dcb82-ffffffe0007dcc7c: tcp_queue_rcv (STB_LOCAL)
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
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81966f00)
Location: net/ipv4/tcp_input.c:4680
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81966f00-ffffffff8196701d: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819209f0)
Location: net/ipv4/tcp_input.c:4680
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff819209f0-ffffffff81920b0d: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d16d0)
Location: net/ipv4/tcp_input.c:4680
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff819d16d0-ffffffff819d17ed: tcp_queue_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_queue_rcv(struct sock *sk, struct sk_buff *skb, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819db260)
Location: net/ipv4/tcp_input.c:4680
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff819db260-ffffffff819db37d: tcp_queue_rcv (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int hdrlen</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, hdrlen, fragstolen</code> ➡️ <code>sk, skb, fragstolen</code>
</li>
</ul>
</details>
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
